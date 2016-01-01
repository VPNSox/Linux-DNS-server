# Linux-DNS-server
This script with install a local DNS server on you GNU/Linux computer, and will directly communicate with the root servers securely (using DNSSEC).


## Use

All those scripts must be run as root.

### Arch - Unbound
```
wget https://raw.githubusercontent.com/Angristan/Linux-DNS-server/master/arch-unbound.sh
chmod +x arch-unbound.sh
./arch-unbound.sh
```

### Arch - PowerDNS
```
wget https://raw.githubusercontent.com/Angristan/Linux-DNS-server/master/arch-powerdns.sh
chmod +x arch-powerdns.sh
./arch-powerdns.sh
```

### Arch - BIND
```
wget https://raw.githubusercontent.com/Angristan/ArchLinux-DNS-server/master/arch-bind.sh
chmod +x arch-bind.sh
./arch-bind.sh
```

### Debian / Ubuntu - Unbound
```
wget https://raw.githubusercontent.com/Angristan/ArchLinux-DNS-server/master/debian-unbound.sh
chmod +x debian-unbound.sh
./debian-unbound.sh
```

Note : you must run `apt-get remove resolvconf ubuntu-minimal` before runnig this script on Ubuntu.


## License

[The unlicense](https://github.com/Angristan/ArchLinux-DNS-server/blob/master/LICENSE)  : do whatever you want with the code.
