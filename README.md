# ddclient-aarch64

Tested on Orange Pi 3B Ubuntu 24.04

Configs for:

https://www.noip.com

https://desec.io

## pi-hole

If you start a pihole on your home server, possibly you'll face something like this:

````
ddclient-dedyn  | WARNING:  found neither IPv4 nor IPv6 address
ddclient-dedyn  | WARNING:  Could not determine an IP for mydedyn.dedyn.io

ddclient-noip   | WARNING:  found neither IPv4 nor IPv6 address
ddclient-noip   | WARNING:  Could not determine an IP for myddns.ddns.net
````

Don't worry.. just do restart and all will be fine:
````
docker-compose restart
````

