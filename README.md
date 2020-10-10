# iOS In-house app distribution server in Flask


### Creating python virtual environment

```bash
$ python3.8 -m venv venv
```

### Creating SSL context keys
You can get more instructions [here](https://www.suse.com/support/kb/doc/?id=000018152)

```bash
$ openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout debug_key.pem -out debug_cert.pem
```