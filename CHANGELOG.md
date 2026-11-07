# Changelog

## 0.7.7 - 2026-11-07

### Improved

- Show one line per queued message, with an ellipsis when the preview is too long. Hover over it to see the original text.
- Give Steer a curved arrow and replace the remove button with a red trash icon. Both controls are larger.
- Keep Steer transparent at rest and show a subtle background on hover.

## 0.7.6 - 2026-11-07

### Improved

- Match the permissions menu background and outline to the model picker.
- Blend unselected options into the menu background. Highlight the current selection and the option under the pointer, as in the Codex and Claude picker.

## 0.7.5 - 2026-11-07

### Added

- Type `/` at the start of a message to find installed skills and supported commands. Use the arrow keys to navigate and Enter or Tab to select an entry before sending.
- Discover Codex skills and Claude commands automatically from the active workspace. The Codex menu also supports native `/review` and `/compact`.
- When Caveman is installed for the active provider, a rock button appears beside Fast Mode. Choose Normal, Ultra, or Mega on a three-step scale. The extension remembers the setting per conversation and reapplies it to ordinary messages.

### Improved

- Align the fill, markers, and labels on the reasoning effort and Caveman scales.
- Keep the model picker free of scrollbars. It grows or shrinks smoothly when Caveman is toggled, with all model rows still visible.

## 0.7.4 - 2026-11-07

### Improved

- Redesigned Assistants settings and moved the provider, model and effort controls inside the composer.
- Discover model and effort options from Codex and Claude. Show Fast Mode as a lightning toggle when supported by the selected model.
- Drag anywhere on the effort bar and see a red shimmer when Ultra is selected.
- Use a smoother expansion for the changed-files list and label the action Collapse files.

### Fixed

- Keep Jump to present at the bottom while a response is streaming, even when jumping from far back in the chat.
- Show only the loading indicator while detecting assistants.
- Match the IDE Context hover to Upload, use a slightly stronger color when checked, and clear the hover highlight when the pointer leaves.

## 0.7.3 - 2026-11-07

### Fixed

- Let chat content scroll through the composer fade instead of clipping above it.
- Keep the final line fully readable above the fade when jumping to the present.

### Improved

- Soften the rounded hover backgrounds on Undo, View changes and the file-list toggle.
- Move the partial-capture explanation from the change card to the Undo tooltip, including when Undo is disabled. File capture limits and Undo safeguards remain in place.

## 0.7.2 - 2026-11-07

### Fixed

- Render attached IDE context as formatted code blocks, preserving indentation without displaying Markdown fences.
- Resolve bare file names using the IDE context attached to each response, including older messages and additional project folders, instead of inventing missing root-level paths.
- Open the correct file or folder in File Explorer and keep file-menu actions separate from opening the editor.
- Show friendly file-action errors beside the affected file instead of displaying raw exceptions above the composer.
- Give user messages more space above their bubbles and increase the gap between the last message and the composer.
- Match the composer shadow and chat fade to the active theme background.

### Improved

- Replace the old AI monogram with a new conversation-and-spark icon.
- Preserve the icon's original colors in Visual Studio menus and include 16/32 px image sources for display scaling.

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
