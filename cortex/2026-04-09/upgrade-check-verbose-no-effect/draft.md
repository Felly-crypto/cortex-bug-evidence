### Project
cortex

### Description
cortex upgrade --check accepts the global --verbose flag, but the default and verbose runs print the same update-check output.

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
1. Run cortex upgrade --check --color never.
2. Run cortex --verbose upgrade --check --color never.
3. Compare the two update-check output blocks.
4. Confirm the screenshot ends with OUTPUTS_IDENTICAL=True.

### Expected Behavior
The verbose check should print extra diagnostic detail compared with the default check.

### Actual Behavior
The verbose check prints the same visible update-check output as the default check.

### Additional Context
The full screenshot shows both runs in one frame and ends with OUTPUTS_IDENTICAL=True after comparing the saved outputs.
