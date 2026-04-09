### Project
cortex

### Description
cortex agent export accepts the global --verbose flag, but the default export and the verbose export print the exact same success output.

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
1. Make sure a personal agent like demo exists.
2. Run cortex agent export demo --output tmp-agent-export-proof.md --color never.
3. Run cortex --verbose agent export demo --output tmp-agent-export-proof.md --color never.
4. Compare the two output blocks.

### Expected Behavior
The verbose export should print extra diagnostic detail compared with the default export.

### Actual Behavior
The verbose export prints the same visible success line as the default export.

### Additional Context
The full screenshot shows both runs in one frame and ends with OUTPUTS_IDENTICAL=True after comparing the saved outputs.
