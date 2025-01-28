# Fail2Ban Rules

一个 Fail2Ban 规则库，保护您的服务器！

## 使用方法

执行以下命令安装 Fail2Ban：

### Ubuntu/Debian

```bash
apt install fail2ban
systemctl enable --now fail2ban
```

### Fedora/RedHat

```bash
yum install epel-release
yum install fail2ban
systemctl enable --now fail2ban
```
### Arch Linux

```bash
pacman -S fail2ban
systemctl enable --now fail2ban
```
### OpenSUSE

```bash
zypper install fail2ban
systemctl enable --now fail2ban
```

### Alpine Linux

```bash
apk add fail2ban
rc-update add fail2ban
rc-service fail2ban start
```

### Void Linux

```bash
xbps-install -S fail2ban
ln -s /etc/sv/fail2ban /var/service/
```

