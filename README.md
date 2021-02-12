# Prerequisites

- [Package Control](https://packagecontrol.io/installation)
- [Python](https://www.python.org/downloads/)
- [Node.js](https://nodejs.org/en/download/)

# Install

```bash
# Linux
git clone https://github.com/keyansheng/sublime-config $HOME/.config/sublime-text-3/Packages/User
echo '#!/bin/bash
prettier --check .' > $HOME/.config/sublime-text-3/Packages/User/.git/hooks/pre-commit

# macOS
git clone https://github.com/keyansheng/sublime-config "$HOME/Library/Application Support/Sublime Text 3/Packages/User"
echo '#!/bin/bash
prettier --check .' > "$HOME/Library/Application Support/Sublime Text 3/Packages/User/.git/hooks/pre-commit"

# Windows
git clone https://github.com/keyansheng/sublime-config "$HOME/AppData/Roaming/Sublime Text 3/Packages/User"
echo '#!/bin/bash
prettier --check .' > "$HOME/AppData/Roaming/Sublime Text 3/Packages/User/.git/hooks/pre-commit"

# Install formatters
pip install black
npm install --global prettier
```

# Update

```bash
# Linux
cd $HOME/.config/sublime-text-3/Packages/User
git pull

# macOS
cd "$HOME/Library/Application Support/Sublime Text 3/Packages/User"
git pull

# Windows
cd "$HOME/AppData/Roaming/Sublime Text 3/Packages/User"
git pull
```
