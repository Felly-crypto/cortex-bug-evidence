# [BUG] [v0.0.7] cortex alias show --verbose produces identical output to the default run

cortex alias show accepts the global --verbose flag, but the default and verbose runs print the same alias details.

Default command: C:\Users\DELL\AppData\Local\Cortex\cortex.exe alias show testalias --color never
Verbose command: C:\Users\DELL\AppData\Local\Cortex\cortex.exe --verbose alias show testalias --color never

Files:
- 01-full-evidence.png
- 02-close-up.png
- transcript.txt
- verbose-off.txt
- verbose-on.txt
- draft.md
