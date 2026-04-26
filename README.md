# VS Code Configuration

This is my personal Visual Studio Code settings.json, might add later extensions and snippets.

## Description

This repository serves as a centralized backup and documentation of my VS Code environment. It is designed to ensure a consistent coding experience across different machines and to automate the setup process for my development workflow.

The goals of this project are:
* To maintain a version-controlled backup of `settings.json`.

## Project Structure

The configuration files are organized by their role in the editor:
* `settings.json`: The core editor configuration (UI, font, formatting rules).

## Getting Started

### Dependencies

* Visual Studio Code (latest version recommended).
* Optional: A font with ligatures (e.g., Fira Code or JetBrains Mono) if specified in settings.

### Installing

1. Clone the file to your local machine.

2. Locate your local VS Code configuration folder:
   * Windows: `%APPDATA%\Code\User\`
   * macOS: `$HOME/Library/Application Support/Code/User/`
   * Linux: `$HOME/.config/Code/User/`

3. Copy the files from this repo into the folder mentioned above.

### Executing program

Once the files are copied:
1. Restart Visual Studio Code or reload the window (`Ctrl+R` or `Cmd+R`).
2. To install the recommended extensions, open the Command Palette (`Ctrl+Shift+P`), type "Extensions: Show Recommended Extensions", and install the workspace recommendations.

## Help

If a specific setting isn't applying, ensure there are no syntax errors (missing commas or braces) in the JSON files.
If a shortcut conflicts with your OS, you may need to manually adjust the `keybindings.json`.

## Authors

* GitHub: [@Frascaz](https://github.com/Frascaz)
* Instagram: [@Frascazzz](https://www.instagram.com/luca_frascaz/)

## Version History

* 0.1
    * Initial Release: Added base settings, theme preferences, and essential extension list.

## License

This project has no license.
