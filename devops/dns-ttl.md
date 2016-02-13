# DNS TTL Fields
Within the dig output, you can find the TTL field proceeds the record type.  
```bash
$ dig www.google.com
...
; ANSWER SECTION:
www.google.com.		254	IN	A	216.58.192.4
```

Look for the answer section, and see the time in seconds before a refresh will occur.

