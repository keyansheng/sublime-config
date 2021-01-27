# Prerequisites

- [Package Control](https://packagecontrol.io/installation)
- [Python](https://www.python.org/downloads/)
- [Node.js](https://nodejs.org/en/download/)

# Install (PowerShell/Bash)

```bash
# Linux
cd ~/.config/sublime-text-3/Packages

# macOS
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages

# Windows
cd ~/AppData/Roaming/'Sublime Text 3'/Packages

# all operating systems
mv User User-backup
git clone https://github.com/keyansheng/sublime-settings User
cd User
echo '#!/bin/bash
prettier --check .' > .git/hooks/pre-commit
pip install black
npm install --global prettier
```

# Update (PowerShell/Bash)

```bash
# Linux
cd ~/.config/sublime-text-3/Packages/User

# macOS
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User

# Windows
cd ~/AppData/Roaming/'Sublime Text 3'/Packages/User

# all operating systems
git pull
```
