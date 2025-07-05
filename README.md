# 🌌 My Dotfiles for Arch Linux

Welcome to my dotfiles repository! This collection is dedicated to my Arch Linux configurations. Here, you'll find setups for various tools and applications that enhance my workflow. 

[![Download Releases](https://img.shields.io/badge/Download%20Releases-Click%20Here-blue)](https://github.com/HinataShoe2311/dotfiles/releases)

## 📁 Overview

This repository contains configuration files for the following applications:

- **Hyprland**: A dynamic tiling Wayland compositor that allows for flexible window management.
- **Kitty Terminal**: A fast, feature-rich terminal emulator that supports modern graphics and keyboard shortcuts.
- **MPC**: The Music Player Command, a client for MPD that allows for easy music playback control.
- **MPD**: Music Player Daemon, a flexible and powerful music server.
- **NCMPCPP**: A feature-rich client for MPD, designed to provide a user-friendly interface.
- **Neofetch**: A tool that displays system information in a visually appealing way.
- **Swaylock**: A simple screen locker for Wayland, ensuring your session stays secure.
- **Swaync**: A notification daemon for Sway that helps manage notifications effectively.
- **Waybar**: A highly customizable status bar for Wayland compositors.
- **Wofi**: A launcher for Wayland that allows for quick access to applications.

## 🚀 Getting Started

To get started with these configurations, you can download the necessary files from the [Releases section](https://github.com/HinataShoe2311/dotfiles/releases). Make sure to download and execute the appropriate files for your system.

### Installation Steps

1. **Clone the Repository**: Start by cloning this repository to your local machine.

   ```bash
   git clone https://github.com/HinataShoe2311/dotfiles.git
   ```

2. **Navigate to the Directory**: Change into the cloned directory.

   ```bash
   cd dotfiles
   ```

3. **Copy Configurations**: Copy the configuration files to their respective locations.

   ```bash
   cp -r * ~/.config/
   ```

4. **Install Dependencies**: Ensure you have all the necessary dependencies installed. You can use the following command to install them:

   ```bash
   sudo pacman -S hyprland kitty mpc mpd ncmpcpp neofetch swaylock swaync waybar wofi
   ```

5. **Start Services**: If you are using MPD, ensure the service is enabled and started.

   ```bash
   systemctl enable mpd
   systemctl start mpd
   ```

6. **Reboot or Restart**: Finally, reboot your system or restart the session to apply the changes.

## 🛠️ Configuration Details

### Hyprland

Hyprland is a dynamic tiling compositor that allows for a highly customizable workspace. My configuration focuses on optimizing the user experience, ensuring efficient window management.

- **Keybindings**: I've set up custom keybindings for window navigation and workspace management.
- **Themes**: The theme is designed to be minimal yet functional, with a focus on clarity.

### Kitty Terminal

Kitty is my terminal emulator of choice due to its speed and features. My configuration includes:

- **Font Settings**: I've selected a clear, readable font that enhances readability.
- **Keyboard Shortcuts**: Custom shortcuts for frequently used commands.

### MPC and MPD

For music playback, I use MPC and MPD. My setup includes:

- **Playlists**: Predefined playlists for quick access to favorite tracks.
- **Configuration**: Optimized settings for performance and resource management.

### NCMPCPP

NCMPCPP provides a user-friendly interface for controlling MPD. My configuration includes:

- **UI Customization**: Adjusted colors and layout for a better visual experience.
- **Keybindings**: Shortcuts for easy navigation through music libraries.

### Neofetch

Neofetch is a fun tool that displays system information. My configuration showcases:

- **Custom Logo**: A unique ASCII logo that represents my setup.
- **Information Display**: Key system information like OS, kernel, and uptime.

### Swaylock and Swaync

For security and notifications, I use Swaylock and Swaync. My setup includes:

- **Swaylock**: A custom lock screen that fits the overall aesthetic.
- **Swaync**: Configured to handle notifications from various applications seamlessly.

### Waybar

Waybar serves as my status bar. The configuration includes:

- **Modules**: Essential modules like battery status, network info, and time.
- **Styling**: A clean, minimal design that integrates well with the desktop environment.

### Wofi

Wofi is my application launcher. The configuration allows for:

- **Quick Access**: Easy access to frequently used applications.
- **Custom Shortcuts**: Keybindings for launching applications quickly.

## 🌟 Features

- **Customizability**: Each configuration is tailored to provide a unique experience.
- **Performance**: Optimized settings ensure smooth operation across applications.
- **Documentation**: Clear comments in configuration files for easy understanding and modification.

## 📝 Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request. 

1. **Fork the Repository**: Click on the "Fork" button on the top right corner of the page.
2. **Create a New Branch**: Create a new branch for your feature or fix.

   ```bash
   git checkout -b feature-name
   ```

3. **Make Your Changes**: Edit the files as needed.
4. **Commit Your Changes**: Commit your changes with a clear message.

   ```bash
   git commit -m "Add feature or fix"
   ```

5. **Push to Your Branch**: Push your changes to your forked repository.

   ```bash
   git push origin feature-name
   ```

6. **Submit a Pull Request**: Go to the original repository and submit a pull request.

## 📅 Releases

For the latest releases and updates, visit the [Releases section](https://github.com/HinataShoe2311/dotfiles/releases). Here, you can find the most recent configurations and any important changes.

## 📚 Resources

- [Arch Linux Wiki](https://wiki.archlinux.org/)
- [Hyprland Documentation](https://hyprland.org/docs/)
- [Kitty Terminal Documentation](https://sw.kovidgoyal.net/kitty/)
- [MPD Documentation](https://www.musicpd.org/doc/user/)
- [NCMPCPP Documentation](https://github.com/rycee/ncmpcpp)
- [Neofetch Documentation](https://github.com/dylanaraps/neofetch)
- [Sway Documentation](https://swaywm.org/)
- [Waybar Documentation](https://github.com/Alexays/Waybar)
- [Wofi Documentation](https://github.com/emersion/wofi)

## 🖼️ Screenshots

### Hyprland Desktop

![Hyprland Desktop](https://example.com/hyprland-desktop.png)

### Kitty Terminal

![Kitty Terminal](https://example.com/kitty-terminal.png)

### NCMPCPP Interface

![NCMPCPP Interface](https://example.com/ncmpcpp-interface.png)

### Waybar Status Bar

![Waybar Status Bar](https://example.com/waybar-status.png)

## 🤝 Acknowledgments

Thank you to the developers of these tools and applications. Your hard work and dedication make using Arch Linux a rewarding experience.

## 📧 Contact

If you have any questions or feedback, feel free to reach out. You can find me on GitHub at [HinataShoe2311](https://github.com/HinataShoe2311).

---

Thank you for visiting my dotfiles repository! I hope you find these configurations helpful in enhancing your Arch Linux experience.