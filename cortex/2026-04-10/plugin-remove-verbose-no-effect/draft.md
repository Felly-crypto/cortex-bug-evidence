### Project
cortex

### Description
cortex plugin remove accepts the global --verbose flag, but the default and verbose runs print the same removal success output.

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
1. Create a disposable plugin directory such as verboseplugremove20260410.
2. Run cortex plugin remove verboseplugremove20260410 --yes --color never.
3. Recreate the disposable plugin, then run cortex --verbose plugin remove verboseplugremove20260410 --yes --color never.
4. Compare the two output blocks.

### Expected Behavior
The verbose remove should print extra diagnostic detail compared with the default remove.

### Actual Behavior
The verbose remove prints the same visible removal success line as the default run.

### Additional Context
The full screenshot shows both runs in one frame and ends with OUTPUTS_IDENTICAL=True after comparing the saved outputs.
