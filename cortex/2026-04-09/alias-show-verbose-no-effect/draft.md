### Project
cortex

### Description
cortex alias show accepts the global --verbose flag, but the default and verbose runs print the same alias details.

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
1. Create a test alias such as testalias.
2. Run cortex alias show testalias --color never.
3. Run cortex --verbose alias show testalias --color never.
4. Compare the two output blocks.

### Expected Behavior
The verbose run should include extra diagnostic detail beyond the default alias details.

### Actual Behavior
The verbose run prints the same visible alias details as the default run.

### Additional Context
The full screenshot shows both runs in one frame and ends with OUTPUTS_IDENTICAL=True after comparing the saved outputs.
