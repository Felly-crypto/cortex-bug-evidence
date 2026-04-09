# [BUG] [v0.0.7] cortex upgrade --check --verbose produces identical output to the default run

cortex upgrade --check accepts the global --verbose flag, but the default and verbose runs print the same update-check output.

Default command: C:\Users\DELL\AppData\Local\Cortex\cortex.exe upgrade --check --color never
Verbose command: C:\Users\DELL\AppData\Local\Cortex\cortex.exe --verbose upgrade --check --color never

Files:
- 01-full-evidence.png
- 02-close-up.png
- transcript.txt
- verbose-off.txt
- verbose-on.txt
- draft.md
