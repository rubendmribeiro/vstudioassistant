# AI Assistant

Codex and Claude, right inside Visual Studio 2022 and 2026.

![AI Assistant](assets/native-chat.png)

A native sidebar for chatting about your code, working with your projects and reviewing changes without leaving the IDE.

## Download

Download the VSIX from the [latest release](https://github.com/rubendmribeiro/vstudioassistant/releases/latest). Close Visual Studio before installing it, then open **View > AI Assistant**.

Your existing Codex or Claude account is required. Missing CLIs can be installed from the extension, and existing CLI sign-ins are reused.

## Features

- Choose your assistant, model, effort and access level.
- Discover local Codex projects with names, icons and additional folders.
- Attach files, paste images and include editor context.
- Keep searchable local conversations with selectable text and file previews.
- Follow streamed activity, queue follow-ups and steer an active Codex response.
- Answer questions and approvals in the chat.
- Review changed files in the native diff editor and undo captured text changes.

Project names and icons refresh when you reopen the project picker. Undo checks for later edits before restoring captured text files; some project files can be outside the capture limits.

## Feedback and fixes

- [Report a bug](https://github.com/rubendmribeiro/vstudioassistant/issues/new?template=bug_report.yml)
- [Suggest a feature](https://github.com/rubendmribeiro/vstudioassistant/issues/new?template=feature_request.yml)
- [Read the changelog](CHANGELOG.md)
- [Browse releases and downloads](https://github.com/rubendmribeiro/vstudioassistant/releases)
- [See resolved issues](https://github.com/rubendmribeiro/vstudioassistant/issues?q=is%3Aissue%20is%3Aclosed)

This public repository hosts documentation, feedback and compiled releases. The extension's source code is maintained in a separate private repository. The automatic source archives on GitHub releases contain only this public repository's documentation.

An independent extension. Not affiliated with OpenAI or Anthropic.
