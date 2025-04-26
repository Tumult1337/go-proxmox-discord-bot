# go-proxmox-discord-bot
---

## 🚀 Requirements

- Go 1.20+ installed
- MySQL server running locally (or remote)

---

## 🛠 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Tumult1337/go-proxmox-discord-bot.git
cd go-proxmox-discord-bot
```

### 2. Install Go Dependencies
```bash
go get -u gorm.io/gorm
go get -u gorm.io/driver/mysql
go get -u github.com/go-sql-driver/mysql
```
---

## MySQL Setup

If you don't have MySQL installed:

- **Windows:** [Download Installer](https://dev.mysql.com/downloads/installer/)
- **Linux (Debian/Ubuntu):**
  ```bash
  sudo apt update
  sudo apt install mysql-server
  sudo systemctl start mysql
  sudo systemctl enable mysql
  ```
---


