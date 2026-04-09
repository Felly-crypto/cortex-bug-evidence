# [BUG] [v0.0.7] cortex agent export --verbose produces identical output to the default run

cortex agent export accepts the global --verbose flag, but the default export and the verbose export print the exact same success output.

Default command: C:\Users\DELL\AppData\Local\Cortex\cortex.exe agent export demo --output "C:\Users\DELL\Desktop\ClaudeFelly\tmp-agent-export-proof.md" --color never
Verbose command: C:\Users\DELL\AppData\Local\Cortex\cortex.exe --verbose agent export demo --output "C:\Users\DELL\Desktop\ClaudeFelly\tmp-agent-export-proof.md" --color never

Files:
- 01-full-evidence.png
- 02-close-up.png
- transcript.txt
- verbose-off.txt
- verbose-on.txt
- draft.md
