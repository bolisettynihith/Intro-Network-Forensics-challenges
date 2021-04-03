## Forensics 150: admin panel

**Challenge**

We captured some traffic logging into the admin panel, can you find the password?

**Solution**

They've provided a pcap file, there's a POST to
/login which looks obvious. Following the stream as HTTP shows the password
quite clearly.

**Flag**
```
picoCTF{n0ts3cur3_894a6546}
```
