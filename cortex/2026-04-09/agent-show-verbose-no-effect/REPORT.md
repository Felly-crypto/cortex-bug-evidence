# [BUG] [v0.0.7] cortex agent show --verbose produces identical output to the default run

cortex agent show accepts the global --verbose flag, but the default and verbose runs print the same agent details.

Default command: C:\Users\DELL\AppData\Local\Cortex\cortex.exe agent show demo --color never
Verbose command: C:\Users\DELL\AppData\Local\Cortex\cortex.exe --verbose agent show demo --color never

Files:
- 01-full-evidence.png
- 02-close-up.png
- transcript.txt
- verbose-off.txt
- verbose-on.txt
- draft.md
