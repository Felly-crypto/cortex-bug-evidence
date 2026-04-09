### Project
cortex

### Description
cortex agent copy respects the source agent name, but it ignores CORTEX_HOME for the destination path and writes the copied agent to C:\Users\DELL\.cortex\agents.

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
2. Run cortex agent copy demo cpyhm09 --color never.
3. Check whether the copied agent exists in the default personal agents directory and in the custom CORTEX_HOME directory.
4. Compare the printed Location line with the existence checks.

### Expected Behavior
The copied agent should be written into the active CORTEX_HOME agents directory.

### Actual Behavior
The command prints a Location under C:\Users\DELL\.cortex\agents, and nothing is created in the custom CORTEX_HOME directory.

### Additional Context
The screenshot keeps the command and the follow-up proof in the same frame.
