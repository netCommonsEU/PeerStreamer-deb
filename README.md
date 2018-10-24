# PeerStreamer-ng deb package

This provides build-tool for packaging [PeerStreamer-ng](https://github.com/netCommonsEU/PeerStreamer-ng) in a deb archive.
It has been tested on Ubuntu server 18.04.

# Installation

```
$>./peerstreamer-ng.buildeb
$>sudo dpkg -i PeerStramer-ng_${ARCH}.deb
$>sudo systemctl start peerstreamer
```
You may want to enable PeerStreamer-ng at startup, just use:
```
$>sudo systemctl enable peerstreamer
```

## Caveats

Working can be prevented by previous installation of python eggs _serf_ and _serf-python_.
Uninstall them before installing PeerStreamer-ng.
