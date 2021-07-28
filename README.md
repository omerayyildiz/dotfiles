# Full Installion Guide for My Mac

## System Preferences

### General

- Theme: Dark
- Sidebar icon size: Small
- Ask to save before closing: Checked

### Desktop & Screen Saver

- Screen Saver: Drift (Option Color: Desktop)
- Hot Corner: Bottom Left: Mission Control
- Hot Corner: Bottom Right: Desktop

### Dock & Menu Bar

![Dock](/images/Dock.png)

- Double-click a window's title bar: Zoom
- Minimize windows into application icon: Unchecked
- Animate opening applications: Checked
- Automatically hide and show the Dock: Unchecked
- Show indicator lights for open applications: Checked
- Show recent applications in Dock: Unchecked
- Automatically hide and show the menu bar: Checked
- Set menu bar icons

### Mission Control

- Group windows by application: Checked

### Apple ID

![Purchases](/images/icloud.png)

### Siri

- Show Siri in menu bar: Unchecked

### Spotlight

- Set your indexing order

### Internet Accounts

- Add new account (Google, Company, Workspace, Outlook, School Mail)

### Security & Privacy

- Set lock message

### Trackpad

- Tap to click

### Mouse

![Mouse](/images/Mouse.png)

---

## Safari

### General

- Open safe downloads: Unchecked

### Extensions

- Install Extensions

### Advanced

- Show Develop menu in menu bar: Checked

### Start Page

- Favorites: Checked
- Reading List: Checked

---

## App Store

- Polyglot
- DuckDuckGo Privacy Essentials
- WhatFont
- Amphetamine
- Encrypto
- Slack
- Hotspot Shield VPN
- WhatsApp
- Telegram
- Grammarly
- Swift Playgrounds
- Twitter
- Pages
- Numbers
- The Unarchiver

---

## Install Apps

### General Usage

- Google Chrome
- Firefox
- Zoom
- AnyDesk
- AppCleaner
- Steam (Close startup settings)
- Spotify
- Discord
- Notion
- Macs Fan Control
- Neat Download Manager
- Android File Transfer
- PDFsam Basic
- Zoho Mail
- coconutBattery
- Malwarebytes
- Keka
- CleanMyMac X

### Development

- Visual Studio Code
- CLion
- RubyMine
- Docker Desktop

### Design

- Creative Cloud Desktop
- Adobe Photoshop
- Adobe Illustrator
- Adobe XD
- Adobe InDesign
- Adobe Acrobat DC
- Figma
- Aseprite
- SF Symbols

---

## Set Development Preferences

### Terminal

- Download Terminal Theme ([omerayyildiz.terminal](https://gist.github.com/omerayyildiz/00cc126d604a484ca56b708d2efa7cf9))
- Install [Oh My Zsh](https://ohmyz.sh)
- Install [Powerlevel10k](https://github.com/romkatv/powerlevel10k)
- Install [Git Plugin](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git)
- Install [Transfer Plugin](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/transfer)
- Install [Zsh Autosuggestions](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md)
- Install [Zsh Syntax Highlighting](https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md)
- Install [Emoji Plugin](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/emoji)
- Install Xcode Command Line Tools (`xcode-select --install`)
- Install [Brew](https://brew.sh/)
- Install [Node](https://nodejs.org/en/)
- Install [Yarn](https://yarnpkg.com/en/docs/install)
- Install [Vimrc](https://github.com/amix/vimrc)
- Set .gitconfig:

```
[user]
     name = Ömer Ayyıldız
     email = oayyildiz416@gmail.com
     signingkey = { GPG KEY HERE }
[init]
     defaultBranch = main
```

- Set GitHub SSH Key

```bash
mkdir .ssh && cd .ssh
```

```bash
ssh-keygen -t ed25519 -C "your_email@example.com"
```

```bash
eval "$(ssh-agent -s)"
```

```bash
touch config
```

```yaml
Host *
     AddKeysToAgent yes
     UseKeychain yes
     IdentityFile ~/.ssh/id_ed25519
```

```bash
ssh-add -K ~/.ssh/id_ed25519
```

- Install GitHub CLI (`brew install gh`)
- Install Ruby (`brew install ruby`)
- Install Bundler (`gem install bundler`)
- Install [Speedtest CLI](https://www.speedtest.net/apps/cli)
- For SSH Server Connection:

```yaml
Host omerayyildiz
     HostName { Server IP here }
     Port 22
     User root
     IdentityFile ~/.ssh/private_key
```

### Update Development Tools

- Update Docker Desktop
- Set RubyMine

---

## Set Design Preferences

- Photoshop Workspace
- Illustrator Workspace
- XD Plugins
- Install Fonts from `tools/fonts`
- Set Brush-Set `tools/brush-set`

---

## Optional Apps

- Google Classroom
- Microsoft Teams

---

## Last Steps

- Close all startup apps (use CleanMyMac X)
- Clean macOS Cache (use CleanMyMac X)
- Reboot

---

## EXTRA
- My VSCode Extensions:
```
aaron-bond.better-comments-2.1.0
alefragnani.bookmarks-13.1.0
azemoh.one-monokai-0.5.0
coenraads.bracket-pair-colorizer-2-0.2.1
davidanson.vscode-markdownlint-0.42.1
esbenp.prettier-vscode-8.0.1
esbenp.prettier-vscode-8.1.0
frenco.vscode-vercel-1.0.3
github.copilot-1.2.2126
github.copilot-1.2.2148
github.vscode-pull-request-github-0.28.0
hediet.vscode-drawio-1.6.1
icrawl.discord-vscode-5.7.0
kasik96.swift-0.2.0
mechatroner.rainbow-csv-1.9.1
ms-azuretools.vscode-docker-1.15.0
ms-vscode-remote.remote-containers-0.187.1
ms-vscode-remote.remote-ssh-0.65.7
ms-vscode-remote.remote-ssh-edit-0.65.7
ms-vscode.vscode-typescript-next-4.4.20210715
ms-vscode.vscode-typescript-next-4.4.20210727
octref.vetur-0.34.1
pkief.material-icon-theme-4.8.0
ritwickdey.liveserver-5.6.1
tabnine.tabnine-vscode-3.4.17
```

---

## Thanks Copilot for helping me with this README file!
