# Establish connectivity to github is WSL

1. Create a file: /etc/wsl.conf with the contents
```bash
	[network]
	generateResolvConf = false
```
2. In a cmd window, run ```wsl --shutdown```
3. Restart WSL2
4. Create a file: /etc/resolv.conf. If it exists, replace existing one with this new file.
5. Put the following line in the file /etc/resolv.conf
```bash
nameserver 8.8.8.8 # Google DNS server / ALternative: own DNS 
```

