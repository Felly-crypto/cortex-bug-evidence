# cortex import --force still creates a new session ID

- Repro 1: `cortex import C:\Users\DELL\Desktop\ClaudeFelly\tmp-import-force-nobom.json --color never`
  - warns that the original session already exists
  - says it is creating a new session ID
- Repro 2: `cortex import C:\Users\DELL\Desktop\ClaudeFelly\tmp-import-force-nobom.json --force --color never`
  - suppresses the warning
  - still imports as a different new session ID instead of reusing the original ID

Original session ID used in the import file:
- `12345678-1234-1234-1234-1234567890ab`

CLI version:
- `cortex 0.0.7 (ac6398e 2026-02-05)`
