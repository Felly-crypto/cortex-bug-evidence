### Project
cortex

### Description
cortex cache size accepts the global --verbose flag, but the default and verbose runs print the same cache size output.

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
1. Make sure the cache contains at least one visible entry.
2. Run cortex cache size --color never.
3. Run cortex --verbose cache size --color never.
4. Compare the two output blocks.

### Expected Behavior
The verbose size command should print extra diagnostic detail compared with the default size command.

### Actual Behavior
The verbose size command prints the same visible size output as the default run.

### Additional Context
The full screenshot shows both runs in one frame and ends with OUTPUTS_IDENTICAL=True after comparing the saved outputs.
