# dotfiles

Operating system configuration files for Akash Vyas.

### Installation

Navigate to home directory.

```bash
cd ~
```

Clone the repository.

```bash
git clone git@github.com:akashkvyas/dotfiles.git
```

Run installation script for your operating system.

```bash
# Arch Linux
chmod +x ~/dotfiles/config/arch-linux-setup
~/dotfiles/config/arch-linux-setup
```

```bash
# macOS
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

![image-20230312224045327](/Users/akashkv/Library/Application Support/typora-user-images/image-20230312224045327.png)

- Apple
  - All apps orginally included in the fresh install except Messages, Facetime, Chess.
- Utilities
  - Included in the fresh install.
  - Add any installed browsers to utilites.
- Social
  - Messages, FaceTime, Discord, Zoom, Slack
- Development
  - Alacritty, Visual Studio Code, Typora
- Office
  - OneDrive, Word, OneNote, PowerPoint, Excel, Outlook
- Other
  - Spotify, Chess
  - Note: Spotify is themed with **spicetify**. 

#### File System

##### Naming

### Maintainance

##### Updating

##### Reseting

### Documentation

### Sources

