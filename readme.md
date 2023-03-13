# dotfiles

Operating system configuration files for Akash Vyas.

## Installation

Navigate to home directory.

```bash
cd ~
```

Clone the repository.

```bash
git clone git@github.com:akashkvyas/dotfiles.git
```

Run installation script for your operating system. You may need to enter your password several times.

#### Arch Linux

```bash
chmod +x ~/dotfiles/config/arch-linux/arch-linux-setup
~/dotfiles/config/arch-linux/arch-linux-setup
```

#### macOS

Prior to installation, **system integrity protection should be disabled** on the system in order for yabai and skhd to work.

```bash
chmod +x ~/dotfiles/config/macos/macos-setup
~/dotfiles/config/macos/macos-setup
```

## Configuration

Refer to the installation script to add applications and configure the file system.

### Tooling

This section details the terminal, shell, window management, and command line tools.

#### Arch Linux

The dotfiles reside in: `~/dotfiles` (default naming).

#### MacOs

The dotfiles reside in: `~/Dotfiles` (for consistency with macOS home directory, default naming in all other folders).

Window management is done through **yabai**, and hotkey's are assigned through **skhd**.

### Applications

This section details the applications/casks installed on the initial system.

#### Arch Linux

#### MacOs

The macOS Launchpad organizes applications installed on the system. Default and addition casks installed by the script are organized in the following categories.

- Apple
  - All apps orginally included in the fresh install except Messages, Facetime, Chess.
- Utilities
  - Included in the fresh install.
  - Add any installed browsers, file system management (google drive) to utilites.
- Social
  - Messages, FaceTime, Discord, Zoom, Slack
- Development
  - Alacritty, Visual Studio Code, Typora
- Office
  - OneDrive, Word, OneNote, PowerPoint, Excel, Outlook, Docs, Slides, Sheets
- Other
  - Spotify, Chess
  - Note: Spotify is themed with **spicetify**.

### Customization

This section details added customizations to the system.

#### Arch Linux

#### MacOs

### Documentation

Relavent documentation links to development tools.

#### Arch Linux

#### MacOs

- brew (package manager)
- alacritty (terminal)
- yabai (window manager)
- skhd (hotkey daemon)
- vscode (text editor)
- oh-my-zsh (zsh theming)
- spicetify (spotify theming)

## File System

##### Naming

## Maintainance

##### Updating

##### Resetting

## Sources
