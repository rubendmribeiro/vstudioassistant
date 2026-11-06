# Changelog

## 0.7.1 - 2026-11-06

### Improved

- Give context menus a darker background and a subtle rounded outline to separate them from the chat.
- Keep menu text and hover states readable in both dark and light Visual Studio themes.

## 0.7.0 - 2026-11-06

### Added

- Automatic discovery of current local Codex desktop projects, including their names, colored icons, emoji and additional folders.
- New Chat and Create project from solution actions fixed at the bottom of the project picker.
- Bundled vector icons for all 30 current Codex project icon choices.

### Fixed

- Exclude historical duplicate project records and refresh names and icons when reopening the picker.
- Decode the Claude installer correctly when its script is downloaded as binary content.
- Let Codex installer subprocesses find the extension's private Node runtime.
- Show actual installer failure details instead of only an exit code.
- Display chat images with a thin rounded outline, without a surrounding card.
- Jump to the present automatically when sending, queueing or steering a message.
- Match the Jump to present outline to the live changed-files badge.
- Give Undo and View changes a darker hover background with rounded corners.
- Remove the extra installation description and center Cancel in light red.

## 0.6.0

- Cleaner live activity that collapses when a reply finishes.
- File review per reply, with line counts, View changes and guarded Undo.
- Live changes summary and smoother chat navigation.
