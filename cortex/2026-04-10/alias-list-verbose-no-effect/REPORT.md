# [BUG] [v0.0.7] cortex alias list --verbose produces identical output to the default run

cortex alias list accepts the global --verbose flag, but the default and verbose runs print the same alias listing.

Default command: C:\Users\DELL\AppData\Local\Cortex\cortex.exe alias list --color never
Verbose command: C:\Users\DELL\AppData\Local\Cortex\cortex.exe --verbose alias list --color never

Files:
- 01-full-evidence.png
- 02-close-up.png
- transcript.txt
- verbose-off.txt
- verbose-on.txt
- draft.md
