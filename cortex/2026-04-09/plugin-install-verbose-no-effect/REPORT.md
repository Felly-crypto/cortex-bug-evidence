# Plugin Install Verbose No Effect

## Bug
cortex plugin install accepts the global --verbose flag, but the verbose run prints the same visible output as the default run.

## Evidence
- Full screenshot: $rawBase/01-full-evidence.png
- Close-up: $rawBase/02-close-up.png

## Repro Commands
- cortex plugin install verboseplugproof20260409 --color never
- cortex --verbose plugin install verboseplugproof20260409 --color never

## Result
Both runs print the same output, and the captured proof ends with OUTPUTS_IDENTICAL=True.
