# zram-config

### install:
```
sudo apt install zram-config
```

### edit:
```
sudo gedit /usr/bin/init-zram-swapping
```

### swappiness
```
sudo bash -c "echo 'vm.swappiness = 5' >> /etc/sysctl.conf"
```
