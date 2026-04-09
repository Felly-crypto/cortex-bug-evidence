### Project
cortex

### Description
cortex plugin disable accepts the global --verbose flag, but a normal run and a verbose run print the exact same output. In the screenshot, both commands disable the same plugin, and the visible output blocks are identical.

### Error Message
None.

### Debug Logs
None.

### System Information
- OS: Windows 11
- Cortex version: cortex 0.0.7 (ac6398e 2026-02-05)

### Screenshots
![Full evidence](https://raw.githubusercontent.com/Felly-crypto/cortex-bug-evidence/main/cortex/2026-04-09/plugin-disable-verbose-no-effect/01-full-evidence.png)

![Close-up](https://raw.githubusercontent.com/Felly-crypto/cortex-bug-evidence/main/cortex/2026-04-09/plugin-disable-verbose-no-effect/02-close-up.png)

### Steps to Reproduce
1. Install a plugin so cortex plugin disable <name> has normal output.
2. Run cortex plugin disable verboseplugdisable20260409 --color never.
3. Re-enable the plugin.
4. Run cortex --verbose plugin disable verboseplugdisable20260409 --color never.
5. Compare the two output blocks.

### Expected Behavior
The verbose run should print extra diagnostic detail compared with the default run.

### Actual Behavior
The verbose run prints the same visible output as the default run.

### Additional Context
The full screenshot shows both commands in one frame and ends with OUTPUTS_IDENTICAL=True after comparing the two saved outputs.
