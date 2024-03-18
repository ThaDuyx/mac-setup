# 🍏 macOS setup
## OS Setup
- ⚙️ System Settings
  - 📋 **General**  
    - **Handoff** On
    - **AirDrop:** Contacts only
    - **Airplay:** On same network
  - 💻 **Desktop & Dock**  
    - **Minimise windows using:** Scale Effect
    - **Minimise windows into application icon:** Off
    - **Automatically hide and show the Dock:** On
    - **Animate opening applications:** Off
    - **Show indicator for open applications:** Off
    - **Show suggested and recent apps in Dock:** Off
    - **Click wallpaper to reveal desktop:** Only in Stage Manager
    - **Stage Manager:** Off
  - 🖥️ **Displays**  
    - **Show resolutions as list(Advanced...)**: On
  - 🖱️ **Trackpad**  
    - **Tap to click:** On
- 🔦 **Finder**
  - General
    - Show these on the desktop -> Select None
    - New Finder windows show -> Home Folder
  - Advanced
    - Show all filename extensions -> Yes
    - Show warning before changing an extension -> No
    - When performing a search -> Search the current folder
  - View
    - Show Status Bar
    - Show Path Bar
    - Show Tab Bar


## Applications setup
### 🍺 Homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
[Homebrew](https://brew.sh) for installing packages.
### 🔍 Raycast
```
brew install raycast
```
Raycast replaces the Spotlight function.  
Install the raycast [Brew](https://www.raycast.com/nhojb/brew) plugin afterwards.  
Change the keyboard shortcut @ System Settings -> Keyboard -> Keyboard shortcuts -> Spotlight -> Uncheck `CMD+SPACE`
### 👨🏼‍💻 iterm2
```
brew install iterm2
```
iterm2 replaces the mac-os terminal application.
### 💾 oh-my-zsh
Open source framework for managing zsh configuration and terminal.
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### 🍻 Brew installs
Download `dev.txt`, `apps.txt` or `prod.txt` depending on the mac setup and run the following:
```
xargs brew install < file.txt
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
