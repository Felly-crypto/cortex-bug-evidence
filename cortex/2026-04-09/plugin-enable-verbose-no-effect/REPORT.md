# [BUG] [v0.0.7] cortex plugin enable --verbose produces identical output to the default run

cortex plugin enable accepts the global --verbose flag, but the default and verbose runs print the same enable success output.

Default command: C:\Users\DELL\AppData\Local\Cortex\cortex.exe plugin enable sample-one --color never
Verbose command: C:\Users\DELL\AppData\Local\Cortex\cortex.exe --verbose plugin enable sample-one --color never

Files:
- 01-full-evidence.png
- 02-close-up.png
- transcript.txt
- verbose-off.txt
- verbose-on.txt
- draft.md
