# FOUNDRY 2.0.0-beta.4

This private-beta checkpoint brings FOUNDRY's dialogs into the same visual system as the main workspace.

## What changed

- Replaced generic information, warning, question, update, and pipeline prompts with a unified branded dialog system.
- Added modern dark surfaces, clearer hierarchy, custom status artwork, refined spacing, and polished interaction states.
- Added platform-appropriate typography for macOS, Windows, and Linux.
- Preserved the existing confirmation boundaries and button behavior.
- Refreshed the beta testing guide and release audit.

## Test focus

- Open several prompts at 70%, 100%, and 120% interface scale.
- Confirm primary, secondary, and cancel actions still perform the expected action.
- Run the pipeline and verify the execution-mode prompt.
- Use **Check for Updates** and confirm this version reports that it is current.

## Packaging status

The macOS beta is an arm64 private-beta build. Production distribution still requires Developer ID signing and notarization. Windows remains pending a native build and test after the GitHub Actions billing restriction is cleared.
