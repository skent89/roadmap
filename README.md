# Packet Product Roadmap

Updated Mar 26, 2015

This document is intended to give a window into the priorities and upcoming
developments at Packet. It is not intended to emphasize specific bug fixes and
ongoing optimizations that we undergo as part of our regular improvement and 
maintenance operations. We view this as a living document, and welcome edits,
suggestions, and feedback!

# Current

These are things that we are actively working on

**API and client portal**
- [ ] PHP API Client
- [ ] Go API Client
- [ ] Ruby API Client
- [ ] API Documentation live

**Network and Facilities**
- [X] EWR, Parsippany Facility online
- [X] NY Metro Fiber Ring Online
- [X] Peering network online
- [X] Bare Metal 1 Servers Deployed
- [ ] San Jose facility online: Q3 2015
- [ ] Network Status page online

**Distributions**
- [ ] Distro: Centos 6
- [X] Distro: Centos 7
- [ ] Distro: Debian 6
- [ ] Distro: Debian 7
- [ ] Distro: Ubuntu 12.04
- [ ] Distro: Ubuntu 14.04
- [ ] Distro: CoreOS
- [ ] Distro: RancherOS

**Labs**
- [ ] PacketBots in the client portal
- [ ] PacketBots return geographic location via GeoIp lookup

**Reliability and performance**
- [ ] Restart system components in case of crash (#2884)

**Mobile Apps**
- [ ] Android App v1
- [ ] iOS App v1

**Platform Integrations**
- [X] [Docker Machine](https://github.com/docker/machine/)
- [ ] [CoreOS](https://coreos.com)
- [ ] [Rancher](http://rancher.com/rancher-os/)
- [ ] [Terraform](https://terraform.io)

# On Deck

These are things that we will focus on next as we complete other tasks
**API and client portal**
- Python API Client
- Per-project / per-device ssh keys
- Userdata profiles (ability to save and reuse userdata configs)

**Network and Facilities**
- Bare Metal 2 Servers Deployed
- Bare Metal 3 Servers Deployed
- San Jose facility online: Q3 2015
- "magic" IPs
- "BYIP": announce your own IP space on our network

**Platform Integrations**
- [Mesosphere](http://mesosphere.com/)
- [Deis](https://deis.io)
- [Kubernetes](https://github.com/GoogleCloudPlatform/kubernetes)
- [Tutum](https://www.tutum.co/)

**Labs**
- Public "internet health" map from PacketBot data

# To Infinity and Beyond!

Some of the things we have on our radar but are not yet slated to start yet are in the following section.

- Amsterdam facility online
- Hong Kong facility online
- [libcloud](http://libcloud.apache.org/) integration
- Organizations / companies in portal
- Cross facility anycast / multicast networking
