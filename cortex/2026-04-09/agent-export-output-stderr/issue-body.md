### Project
cortex

### Description
cortex agent export writes the exported file successfully, but the normal success message goes to stderr while stdout stays empty. That makes the command harder to script consistently.

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
1. Choose a writable output file path.
2. Run cortex agent export demo --output <path> --color never with stdout and stderr redirected to separate files.
3. Print the captured stdout file and stderr file contents.
4. Compare the stream contents with the exported file existence check.

### Expected Behavior
A normal success message for a successful export should go to stdout, with stderr reserved for errors and warnings.

### Actual Behavior
Stdout stays empty, the success message appears in stderr, and the output file is still created.

### Additional Context
The screenshot keeps the command and the follow-up proof in the same frame.
