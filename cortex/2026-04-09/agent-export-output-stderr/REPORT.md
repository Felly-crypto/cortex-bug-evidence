# [BUG] [v0.0.7] cortex agent export --output prints its success message to stderr instead of stdout

cortex agent export writes the exported file successfully, but the normal success message goes to stderr while stdout stays empty. That makes the command harder to script consistently.

Files:
- 01-full-evidence.png
- 02-close-up.png
- transcript.txt
- issue-body.md
