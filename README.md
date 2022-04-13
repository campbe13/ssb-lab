## Brute force against ssh

You will be running cowrie in a container on your system.  Use ssb and the wordlists in the directory here
to run a brute force check against your system.

1. on port 8222 (against the honeypot)
2. on port 22 against your sshd


### Install bSecure Shell Bruteforcer — A faster & simpler way to bruteforce SSH server.
ssb
```
curl -sSfL 'https://git.io/kitabisa-ssb' | sh -s -- -b /usr/local/bin
```
#### Usage
```
 ssb [-p port] [-w wordlist.txt] [-t timeout]
      [-c concurrent] [-r retries] [-o output] [user@]hostname
```




