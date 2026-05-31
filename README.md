# My Sway Rice

This repository contains my personal Sway dotfiles and configuration scripts. 

## 📦 Contents

*   **Window Manager:** [Sway](https://swaywm.org/)
*   **Bar:** [Waybar](https://github.com/Alexays/Waybar)
*   **Terminal:** [foot](https://codeberg.org/dnkl/foot)
*   **Application Launcher:** [Wofi](https://hg.sr.ht/~scoopta/wofi)
*   **Notification Daemon:** [Swaync](https://github.com/ErikReider/SwayNotificationCenter)
*   **Prompt:** [Oh My Posh](https://ohmyposh.dev/)
*   **System Fetch:** [Fastfetch](https://github.com/fastfetch-cli/fastfetch)
*   **Mouse manipulation:** [warpd](https://github.com/rvaiya/warpd)

## 🚀 Installation

1.  Clone this repository:
    ```bash
    git clone <YOUR_REPO_URL>
    cd <YOUR_REPO_NAME>
    ```

2.  Copy the configuration files to your `~/.config` directory:
    ```bash
    cp -r .config/* ~/.config/
    ```

3.  Copy `.bashrc` and `.profile` to your home directory (make backups first!):
    ```bash
    cp .bashrc ~/.bashrc
    cp .profile ~/.profile
    ```

4.  Scripts can be copied or executed as needed from the `Scripts/` folder.

## 🖼️ Wallpaper

The wallpaper is located at `.config/background-d.jpg`. It will automatically be loaded by the Sway configuration file, which expects it to be at `~/.config/background-d.jpg`.

## ⚙️ Scripts

This repository also includes some useful scripts in the `Scripts/` directory for setting up Timeshift, configuring audio, SwayFX, KDE Connect, and more.

---

*Note: Make sure to review the configuration files to adapt them to your specific hardware setup, such as monitor names and resolutions in the Sway config.*
