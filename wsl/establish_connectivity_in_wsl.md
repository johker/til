# Fix connectivity

1. Create a file: /etc/wsl.conf with the contents
```bash
[network]
generateResolvConf = false
```
2. In a cmd window, run ```wsl --shutdown``` and restart WSL
3. Puthe following line in the file /etc/resolv.conf
```bash
nameserver 8.8.8.8 # Google DNS server / ALternative: own DNS 
```

