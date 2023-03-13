# dotfiles

Operating system configuration files for Akash Vyas.

### Installation

```bash
cd ~
```

Clone the repository.

```bash
git clone git@github.com:akashkvyas/dotfiles.git
```

Run installation script for your operating system. You may need to enter your password several times.

Arch Linux:

```bash
chmod +x ~/dotfiles/config/arch-linux-setup
~/dotfiles/config/arch-linux-setup
```

macOS:
Prior to installation, **System Integrity Protection should be disabled** on the system in order for yabai and skhd to work. Navigate to home directory.

```bash
chmod +x ~/dotfiles/config/macos-setup
~/dotfiles/config/macos-setup
```

### Configuration

Refer to the installation script to add applications and configure the file system.

#### Arch Linux

The dotfiles reside in: `~/dotfiles` (default naming).

##### Applications

#### macOs

The dotfiles reside in: `~/Dotfiles` (for consistency with macOS home directory, default naming in all other folders).

##### Tooling

Several development tools are installed by the system.

##### Window Management

Window management is done through **yabai**, and hotkey's are assigned through **skhd**.

##### Applications

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

#### Documentation

- brew (package manager)
- alacritty (terminal)
- yabai (window manager)
- skhd (hotkey daemon)
- vscode (text editor)
- oh-my-zsh (zsh theming)
- spicetify (spotify theming)

#### File System

##### Naming

### Maintainance

##### Updating

##### Reseting

### Documentation

### Sources
