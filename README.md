https://raw.githubusercontent.com/User058/User058/main/install.## Features

- **Automated Installation**: One-command setup for all dependencies and configurations.
- **SSH & WebSocket Management**: Create, renew, lock/unlock, and delete SSH accounts with WebSocket and SSL support.
- **SlowDNS Support**: DNS tunneling for SSH connections, perfect for bypassing network restrictions.
- **Service Control**: Start, stop, and restart core services (SSH, Nginx, Dropbear, Stunnel, WebSocket Proxy, etc.).
- **Domain & SSL Automation**: Easily set or change your VPS domain and auto-issue SSL certificates.
- **System Information**: View detailed system, network, and service status.
- **Banner & Response Editing**: Customize SSH banners and HTTP 101 responses.
- **Scheduled Maintenance**: Automated cron jobs for rebooting and cleaning expired accounts.
- **Modern & Interactive UI**: Features a user-friendly, interactive CLI menu for seamless VPS management.
 **High Performance WebSocket Proxy**: Handles high load more efficiently than other scripts by using a Go-based WebSocket proxy instead of Python.
- **SSHGuard Protection**: Protects your SSH service from brute-force attacks automatically.

---


## Installation

> **Note:** AutoScriptX is intended for fresh Ubuntu/Debian VPS environments. **You must run as root.**
> 
> If not already root, run:
> 
> ```bash
> sudo su
> ```

Then install AutoScriptX with:

```bash
bash <(curl -Ls https://raw.githubusercontent.com/User058/User058/main/install.sh)
```

Follow the prompts to set your domain and complete the setup.

---

## Usage


After installation, launch the main menu with either command:

```bash
autoscriptx
# or
asx
```

### Menu Options
- Create, delete, renew, lock/unlock SSH accounts
- Edit SSH banner and HTTP 101 response
- Change domain and auto-issue SSL
- Setup and manage SlowDNS (DNS tunneling)
- Manage services (start/stop/restart)
- View system information