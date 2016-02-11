## Test DNS Resolution  

`dig` and `nslookup` are key tools for testing DNS resolution on a host.  

```bash
$ dig www.google.com @208.67.222.222
```

The example above uses [OpenDNS](https://use.opendns.com/#mac) to test DNS resolution for that particular DNS host.  
This can also be accomplished with `nslookup`.  

```bash
$ nslookup www.google.com 208.67.220.220
```

