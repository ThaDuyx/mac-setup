# 🍏 macOS setup
## OS Setup
- ⚙️ **System Settings**
  - 📋 General  
    - _Handoff:_ `On`
    - _AirDrop:_ `Contacts only`
    - _Airplay:_ `On same network`
  - 💻 Desktop & Dock
    - _Minimise windows using:_ `Scale Effect`
    - _Minimise windows into application icon:_`Off`
    - _Automatically hide and show the Dock:_ `On`
    - _Animate opening applications:_ `Off`
    - _Show indicator for open applications:_ `Off`
    - _Show suggested and recent apps in Dock:_ `Off`
    - _Click wallpaper to reveal desktop:_`Only in Stage Manager`
    - _Stage Manager:_ `Off`
  - 🖥️ Displays  
    - _Show resolutions as list(Advanced...):_ `On`
  - 🖱️ Trackpad
    - _Tap to click:_ `On`
- 🔦 **Finder**
  - 📋 General
    - _Show these on the desktop:_ `Select None`
    - _New Finder windows show:_ `Home Folder`
  - Advanced
    - _Show all filename extensions:_ `Yes`
    - _Show warning before changing an extension:_ `No`
    - _When performing a search:_ `Search the current folder`
  - View
    - _Show Status Bar_
    - _Show Path Bar_
    - _Show Tab Bar_


## Applications setup
### 🍺 Homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
[Homebrew](https://brew.sh) for installing packages.  
Add Homebrew to your PATH in ~/.zprofile:
```
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"
```
and check that Homebrew is installed properly.
```
brew doctor
```

### 🔍 Raycast
```
brew install raycast
```
Raycast replaces the Spotlight function.  
Install the raycast [Brew](https://www.raycast.com/nhojb/brew) plugin afterwards.  
Change the keyboard shortcut @ System Settings -> Keyboard -> Keyboard shortcuts -> Spotlight -> Uncheck `CMD+SPACE`
### 👨🏼‍💻 iterm2 & warp
```
brew install iterm2
brew install warp
```
iterm2 and warp replaces the mac-os terminal application.
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

### 🐍 Python
```
brew install python
```
To select interpreter, type `python`, `python2` or `python3` into the terminal.
```
python --version
```
To check the version


### 🎶 Node.js
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
- [Final Cut Pro](https://apps.apple.com/dk/app/final-cut-pro/id424389933?mt=12) video editor
- [HotSpot Shield](https://apps.apple.com/dk/app/hotspotshield-vpn-wifi-proxy/id771076721?mt=12) vpn
- [XCode](https://apps.apple.com/dk/app/xcode/id497799835?mt=12) IDE
- [DevCleaner](https://apps.apple.com/dk/app/devcleaner-for-xcode/id1388020431?mt=12) dev clutter organizer
