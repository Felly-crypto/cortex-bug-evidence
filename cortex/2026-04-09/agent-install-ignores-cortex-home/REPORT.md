# cortex agent install ignores CORTEX_HOME

## Bug
When `CORTEX_HOME` points at a custom profile directory, `cortex agent install` still installs the agent into the default personal directory under `C:\Users\DELL\.cortex\agents`.

## What the evidence shows
- `CORTEX_HOME` is set to a custom temp directory
- the exact `cortex.exe agent install proofagent20260409 --registry http://127.0.0.1:8765` command is visible
- Cortex reports `Location: C:\Users\DELL\.cortex\agents\proofagent20260409.md`
- the follow-up checks show `DEFAULT_EXISTS=True` and `CUSTOM_EXISTS=False`

## Files
- `01-full-evidence.png`
- `02-close-up.png`
- `transcript.txt`
