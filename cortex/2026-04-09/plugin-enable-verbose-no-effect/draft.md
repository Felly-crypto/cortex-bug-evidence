### Project
cortex

### Description
cortex plugin enable accepts the global --verbose flag, but the default and verbose runs print the same enable success output.

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
1. Make sure a disabled plugin such as sample-one exists.
2. Run cortex plugin enable sample-one --color never.
3. Disable it again, then run cortex --verbose plugin enable sample-one --color never.
4. Compare the two output blocks.

### Expected Behavior
The verbose enable should print extra diagnostic detail compared with the default enable.

### Actual Behavior
The verbose enable prints the same visible success line as the default enable.

### Additional Context
The full screenshot shows both runs in one frame and ends with OUTPUTS_IDENTICAL=True after comparing the saved outputs.
