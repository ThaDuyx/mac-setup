# 🍏 mac-setup
## ⚙️ System Settings
### 📋 General
- **Handoff** On
- **AirDrop:** Contacts only
- **Airplay:** On same network

### 💻 Desktop & Dock
- **Minimise windows using:** Scale Effect
- **Minimise windows into application icon:** Off
- **Automatically hide and show the Dock:** On
- **Animate opening applications:** Off
- **Show indicator for open applications:** Off
- **Show suggested and recent apps in Dock:** Off
- **Click wallpaper to reveal desktop:** Only in Stage Manager
- **Stage Manager:** Off

### 🖥️ Displays
- **Show resolutions as list(Advanced...)**: On

### 🖱️ Trackpad
- **Tap to click:** On

## Applications setup
### 🍺 Homebrew
[Homebrew](https://brew.sh) for installing packages
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
### 🔍 Raycast
```
brew install raycast
```
Install the raycast [Brew](https://www.raycast.com/nhojb/brew) plugin afterwards.
### 👨🏼‍💻 iterm2
```
brew install iterm2
```
### 💾 oh-my-zsh
Open source framework for managing zsh configuration and terminal.
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### 🍻 Brew installs
Download 'dev.txt' or 'apps.txt' depending on the setup and run the following:
```
xargs brew install < apps.txt
```

### 🔥🦊 Firefox
```
brew tap homebrew/cask-versions
brew install homebrew/cask-versions/firefox-developer-edition
```

### Node.js
Double check the latest version on the [nvm](https://github.com/nvm-sh/nvm) GitHub page. 
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
```
Afterwards download wanted node version.
```
nvm install 20
nvm use 20
node --version
```

## 🍎 App Store
- [Dashlane](https://apps.apple.com/dk/app/dashlane-password-manager/id517914548) password vault
- [HotSpot Shield](https://apps.apple.com/dk/app/hotspotshield-vpn-wifi-proxy/id771076721?mt=12) vpn
- [XCode](https://apps.apple.com/dk/app/xcode/id497799835?mt=12) IDE
- [DevCleaner](https://apps.apple.com/dk/app/devcleaner-for-xcode/id1388020431?mt=12) dev clutter organizer
