# Self-signed Certificate Generation

## Application

N/A

## Description

Self-signed certificates used by Docker images.

## Build notes

Command used to generare self signed certs (tested with OpenSSL v3.5.0):-

```bash
openssl req \
  -x509 \
  -newkey 'rsa:4096' \
  -sha256 \
  -days '3650' \
  -nodes \
  -keyout './self-signed.key' \
  -out './self-signed.crt' \
  -subj '/CN=localhost'
```

## Notes

N/A

If you appreciate my work, then please consider buying me a beer  :D

[![PayPal donation](https://www.paypal.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=MM5E27UX6AUU4)
