# [BUG] [v0.0.7] cortex agent create --non-interactive ignores CORTEX_HOME and writes to the default personal agents directory

cortex agent create --non-interactive accepts CORTEX_HOME in the environment, but it still writes the new agent to the default personal agents directory under C:\Users\DELL\.cortex\agents instead of the custom home.

Files:
- 01-full-evidence.png
- 02-close-up.png
- transcript.txt
- issue-body.md
