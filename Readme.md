# Dotfiles
---

Welcome to my dotfiles repository! This project is a collection of my personal configuration files for various tools and environments. It's designed to streamline my workflow, boost productivity, and ensure consistency across different machines.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Scripts](#scripts)
  - [Tmux Session Popup](#tmux-session-popup)
- [Contributing](#contributing)
- [License](#license)

## Features

- Tmux configurations to enhance your terminal experience.
- Custom scripts for efficient session management and navigation.
- Modular and easy-to-expand setup.

## Installation

To get started with these dotfiles, clone the repository and follow the instructions for each tool or script:

```bash
git clone https://github.com/aria-dev/dotfiles.git
cd dotfiles
```

## Usage
Included with the scripts individually

## Scripts

### Tmux Session Popup

**Location**: `script/tmux/tmux-session-popup.sh`

This script creates a popup window in tmux that lists all tmux sessions using `fzf`. It allows you to switch to the selected session in the current tmux window without creating nested tmux sessions.

**Usage:**

To use the tmux session popup script, simply follow the instructions to add it to your tmux config:
[tmux-session-popup.sh](./script/tmux/tmux-session-popup.sh)

This will open a new tmux window with the session switcher.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or additional scripts you'd like to share, feel free to open a pull request or issue.

## License

This project is licensed under the [MIT License](LICENSE).

---
