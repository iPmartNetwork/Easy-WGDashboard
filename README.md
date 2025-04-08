### Easy-WGDashboard Server & Panel Installer

This script automates the installation and configuration of a WireGuard VPN server, WGDashboard, and related dependencies on a Linux system. It is designed to work on Ubuntu (20.10, 20.04, 22.04) and Debian 11, providing users with an interactive and fully configured WireGuard VPN server and management dashboard.

#### Features

- **Automated Installation**: Installs and configures WireGuard, WGDashboard, and other necessary packages.
- **Interactive Setup**: Guides the user through the setup, asking for hostname, username, passwords, and preferred network configuration options.
- **IPv4/IPv6 Configuration**: Supports generation and configuration of both IPv4 and IPv6 addresses.
- **Firewall Configuration**: Sets up UFW rules for WireGuard, dashboard, and SSH access.
- **Automatic Service Management**: Configures WireGuard and dashboard services to run on boot, with monitoring for config changes.
- **IPv6 Support**: Detects and configures IPv6 if available.

#### Requirements

- Supported OS: **Ubuntu 20.10/20.04/22.04 or Debian 11**
- Network Access: Requires internet access to download dependencies.
- User Privileges: Must be run as **root** or with **sudo**.

### Usage

1. **Download the Script**: Clone the repository or download the script file.

```
 apt update && apt install git -y && git clone https://github.com/iPmartNetwork/Easy-WGDashboard && cd Easy-WGDashboard && chmod +x install.sh && ./install.sh 
 ```
