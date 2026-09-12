# CalmCode Icons Assets

Shared SVG icon pack for editor integrations.

This repository stores the reusable asset files used by VS Code, Zed and other tools.

## Structure

- `icons/` — SVG files for files, folders, and language icons
- `LICENSE` — license

## Usage

Platform repos should include this repository as a git submodule and reference icons like:

- `./assets/icons/file.svg`
- `../assets/icons/folder.svg`

## Notes

Keep the shared assets centralized here so that theme packages do not duplicate the same SVG files.
