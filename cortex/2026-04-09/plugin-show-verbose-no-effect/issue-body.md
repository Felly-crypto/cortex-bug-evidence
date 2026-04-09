### Project
cortex

### Description
cortex plugin show accepts the global --verbose flag, but a normal run and a verbose run print the exact same output. In the screenshot, both commands show the same installed plugin, and the visible output blocks are identical.

### Error Message
None.

### Debug Logs
None.

### System Information
- OS: Windows 11
- Cortex version: cortex 0.0.7 (ac6398e 2026-02-05)

### Screenshots
![Full evidence](https://raw.githubusercontent.com/Felly-crypto/cortex-bug-evidence/main/cortex/2026-04-09/plugin-show-verbose-no-effect/01-full-evidence.png)

![Close-up](https://raw.githubusercontent.com/Felly-crypto/cortex-bug-evidence/main/cortex/2026-04-09/plugin-show-verbose-no-effect/02-close-up.png)

### Steps to Reproduce
1. Install a plugin so cortex plugin show <name> has normal output.
2. Run cortex plugin show verboseplugshow20260409 --color never.
3. Run cortex --verbose plugin show verboseplugshow20260409 --color never.
4. Compare the two output blocks.

### Expected Behavior
The verbose run should print extra diagnostic detail compared with the default run.

### Actual Behavior
The verbose run prints the same visible output as the default run.

### Additional Context
The full screenshot shows both commands in one frame and ends with OUTPUTS_IDENTICAL=True after comparing the two saved outputs.
