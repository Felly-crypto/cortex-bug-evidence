# Agent Install Verbose No Effect

## Bug
cortex agent install accepts the global --verbose flag, but the verbose run prints the same visible output as the default run.

## Evidence
- Full screenshot: $rawBase/01-full-evidence.png
- Close-up: $rawBase/02-close-up.png

## Repro Commands
- cortex agent install proofagent20260409 --registry http://127.0.0.1:8765 --color never
- cortex --verbose agent install proofagent20260409 --registry http://127.0.0.1:8765 --color never

## Result
Both runs print the same output, and the captured proof ends with OUTPUTS_IDENTICAL=True.
