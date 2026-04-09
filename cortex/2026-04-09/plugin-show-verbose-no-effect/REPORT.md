# Plugin Show Verbose No Effect

## Bug
cortex plugin show accepts the global --verbose flag, but the verbose run prints the same visible output as the default run.

## Evidence
- Full screenshot: $rawBase/01-full-evidence.png
- Close-up: $rawBase/02-close-up.png

## Repro Commands
- cortex plugin show verboseplugshow20260409 --color never
- cortex --verbose plugin show verboseplugshow20260409 --color never

## Result
Both runs print the same output, and the captured proof ends with OUTPUTS_IDENTICAL=True.
