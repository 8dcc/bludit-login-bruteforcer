## Bludit login bruteforcer
I made this script for the blunder machine (https://www.hackthebox.eu/home/machines/profile/254). It can be used to bruteforce bludit logins.

### Installation
```git clone https://github.com/r4v10l1/bludit_login_bruteforcer```

```cd bludit_login_bruteforcer```

```python3 bludit_exploit.py <target> <wordlist>```

### Notes
- <b>Target:</b>
  - <b>The target must be in this format:</b> ```http://IP```
  - <b>You can use IP or hostname, but do not type "/" at he end:</b><del> ```http://example.com/```</del> >> ```http://example.com```
- <b>The worlist must be in .txt format.</b>
- <b>The username is admin, you can edit this in the code easily.</b>
