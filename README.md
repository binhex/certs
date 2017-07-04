**Application**

N/A

**Description**

Self-signed certificates used by Docker images.

**Build notes**

Command used to generare self signed certs for OpenSSL 1.1.0e:-

```
sudo openssl req -x509 -nodes -days 3650 -newkey rsa:4096 -keyout /tmp/server.key -out /tmp/server.cert
```

**Notes**

N/A

If you appreciate my work, then please consider buying me a beer  :D

[![PayPal donation](https://www.paypal.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=MM5E27UX6AUU4)
