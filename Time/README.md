<h1>Time</h1>

### Fixing Time Clock
```xml
timedatectl status
```

### Install Network Time Protocol 
```xml
 sudo pacman -S ntp
```

### Activating NTP
```xml
sudo timedatectl set-ntp true
```

### Listing Time Zones
```xml
timedatectl list-timezones
```

### Setting Time Zone
```xml
sudo timedatectl set-timezone America/Sao_Paulo
```