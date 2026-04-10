### Project
cortex

### Description
cortex alias list accepts the global --verbose flag, but the default and verbose runs print the same alias listing.

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
1. Create at least one alias so alias list prints visible output.
2. Run cortex alias list --color never.
3. Run cortex --verbose alias list --color never.
4. Compare the two output blocks.

### Expected Behavior
The verbose alias listing should print extra diagnostic detail compared with the default listing.

### Actual Behavior
The verbose alias listing prints the same visible alias listing as the default run.

### Additional Context
The full screenshot shows both runs in one frame and ends with OUTPUTS_IDENTICAL=True after comparing the saved outputs.
