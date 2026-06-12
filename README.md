## settings-json

A simple collection of IDE settings (settings.json) designed to make it easy to share and apply consistent editor configuration across machines.

### Purpose
Provide a ready-to-use settings.json that enhances the IDE experience and can be copied to another PC to keep settings consistent.

### Contents
- settings.json (JSONC) — curated editor settings, keybindings, formatting rules, and extension recommendations.

### Features
- Editor preferences (tabs, line endings, font, minimap)
- Formatting and linting defaults
- Workspace and project-friendly settings
- Comments allowed via JSONC for easy customization

### Installation
1. Clone or download this repository.
2. Copy the included settings.json to your editor's user settings path:
   - macOS: ~/Library/Application Support/Code/User/settings.json
   - Windows: %APPDATA%\Code\User\settings.json
   - Linux: ~/.config/Code/User/settings.json
   - For Code - OSS replace "Code" with "Code - OSS".
   - Or place as .vscode/settings.json inside a project folder to apply per-workspace.
3. Restart your editor (if open) to apply settings.

### Usage
- Edit settings.json to adjust preferences (comments allowed).
- Commit your modified settings.json to this repo to share with other machines.
- Optionally sync via cloud storage or dotfiles manager.

### Example (snippet)
```jsonc
{
  // Editor
  "editor.tabSize": 2,
  "editor.insertSpaces": true,
  "files.eol": "\n",

  // Formatting
  "editor.formatOnSave": true,

  // Appearance
  "workbench.colorTheme": "Default Dark+"
}
```

### Contributing
- Fork the repo, create a branch for your changes, and open a pull request.
- Keep changes focused and add comments in JSONC explaining non-obvious settings.
- Add or update README when adding new groups of settings or extension recommendations.

### License
This repository is provided under the MIT License — see LICENSE for details.

### Contact
Open an issue or pull request on GitHub for questions, suggestions, or fixes.
