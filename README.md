# Prerequisites

- [Package Control](https://packagecontrol.io/installation)
- [Python](https://www.python.org/downloads/)
- [Node.js](https://nodejs.org/en/download/)

# Install (PowerShell/Bash)

```bash
# Linux
git clone https://github.com/keyansheng/sublime-settings ~/.config/sublime-text-3/Packages/User
echo '#!/bin/bash
prettier --check .' > ~/.config/sublime-text-3/Packages/User/.git/hooks/pre-commit

# macOS
git clone https://github.com/keyansheng/sublime-settings ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User
echo '#!/bin/bash
prettier --check .' > ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/.git/hooks/pre-commit

# Windows
git clone https://github.com/keyansheng/sublime-settings ~/AppData/Roaming/'Sublime Text 3'/Packages/User
echo '#!/bin/bash
prettier --check .' > ~/AppData/Roaming/'Sublime Text 3'/Packages/User/.git/hooks/pre-commit

# Install formatters
pip install black
npm install --global prettier
```

# Update (PowerShell/Bash)

```bash
# Linux
cd ~/.config/sublime-text-3/Packages/User
git pull

# macOS
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User
git pull

# Windows
cd ~/AppData/Roaming/'Sublime Text 3'/Packages/User
git pull
```
