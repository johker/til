# Monitor TCP Traffic 

I can monitor TCP traffic on a specific port using the tcpdump, e.g. on port 1041


```bash
tcpdump port 1041
```

To get a list with active ports: 

```bash
lsof -i -P -n | grep LISTEN
```

