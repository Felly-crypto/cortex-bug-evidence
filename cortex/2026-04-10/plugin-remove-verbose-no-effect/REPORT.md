# [BUG] [v0.0.7] cortex plugin remove --verbose produces identical output to the default run

cortex plugin remove accepts the global --verbose flag, but the default and verbose runs print the same removal success output.

Default command: C:\Users\DELL\AppData\Local\Cortex\cortex.exe plugin remove verboseplugremove20260410 --yes --color never
Verbose command: C:\Users\DELL\AppData\Local\Cortex\cortex.exe --verbose plugin remove verboseplugremove20260410 --yes --color never

Files:
- 01-full-evidence.png
- 02-close-up.png
- transcript.txt
- verbose-off.txt
- verbose-on.txt
- draft.md
