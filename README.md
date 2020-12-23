# home-server

Definitions to build a raspberry docker based server.

# The environment file

The environment file has the following content:

```
FTP_USER=xxx
FTP_PASS=xxx
```

# Starting docker from server

Start docker-compose with env file:

```
docker-compose -d --env-file ./.prod.env up 
```

# References

[Enable SSH on Raspberry Pi](https://www.raspberrypi.org/documentation/remote-access/ssh/)

[Setting up a wireless LAN via the command line](https://www.raspberrypi.org/documentation/configuration/wireless/wireless-cli.md)

[How To Install Docker On Raspberry Pi](https://phoenixnap.com/kb/docker-on-raspberry-pi)

[External storage configuration](https://www.raspberrypi.org/documentation/configuration/external-storage.md)