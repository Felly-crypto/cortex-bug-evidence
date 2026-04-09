### Project
cortex

### Description
cortex agent create --non-interactive accepts CORTEX_HOME in the environment, but it still writes the new agent to the default personal agents directory under C:\Users\DELL\.cortex\agents instead of the custom home.

### Error Message
None.

### Debug Logs
None.

### System Information
- OS: Windows 11
- Cortex version: cortex 0.0.7 (ac6398e 2026-02-05)

### Screenshots
![Full evidence](RAW_URL_1)

![Close-up](RAW_URL_2)

### Steps to Reproduce
1. Set CORTEX_HOME to a custom temp directory.
2. Run cortex agent create --non-interactive --name crtchm09 --color never.
3. Check whether the created file exists in the default personal agents directory and in the custom CORTEX_HOME directory.
4. Compare the printed path with the existence checks.

### Expected Behavior
The command should write the new agent into the active CORTEX_HOME agents directory.

### Actual Behavior
The command prints and writes the new agent under C:\Users\DELL\.cortex\agents, and nothing is created in the custom CORTEX_HOME directory.

### Additional Context
The screenshot keeps the command and the follow-up proof in the same frame.
