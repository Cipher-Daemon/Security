# Do Not Cache Password

To tell gpg to not cache the password when doing symmetric encryption do the following:

```bash
gpg -c --no-symkey-cache --cipher-algo AES256 [FILE]
```

For decrypting do the same but with the "d" flag

```bash
gpg -d --no-symkey-cache [FILE]
```
