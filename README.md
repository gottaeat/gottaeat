## projects
### systems
- [apathy](https://github.com/gottaeat/apathy)
  Independent homegrown operating system featuring Linux in its core,
  supplemented with musl libc and a standalone LLVM suite.
- [bootstrap-standalone-llvm](https://github.com/gottaeat/bootstrap-standalone-llvm)
  Containerized boostrapper to build a non-GNU, standalone, self-hosting and
  portable* LLVM suite.
- [openwrt-builds](https://github.com/gottaeat/openwrt-builds)
  Containerized OpenWRT squashFS and toolchain builder with jinja2 templating
  support for rootfs default overrides.
### automation
- [setboxes](https://github.com/gottaeat/setboxes)
  Ansible playbook, and utilities utilizing libVirt, to generate Arch Linux
  based per-target rootfs images and to maintain once written to baremetal.
- [cloudvirt](https://github.com/gottaeat/cloudvirt)
  CloudVirt creates and destroys cloud-init powered x86_64 VMs utilizing the
  libVirt API.
### protocol implementations
- [bands](https://github.com/gottaeat/bands)
  RFC 1459 and 2812 compliant (with a bit of IRCv3), concurrent IRC bot with
  extensive and extendable features.
### networking
- [genwg](https://github.com/gottaeat/genwg)
  WireGuard client and server configuration generator that creates BIND zones
  for servers with A and PTR records for the clients, supports WG over FakeTCP
  and has system DNS resolver awareness beyond just systemd-resolved.
- [wya](https://github.com/gottaeat/wya)
  Dockerized IP ASN and geolocation lookup tool built with Flask and GeoLite2
  databases.
- [zonegen](https://github.com/gottaeat/zonegen)
  DDNS implementation for OpenWRT odhcpd to be able to update BIND via rndc on
  every DHCP lease action without external dependencies.
- [mss-nfqws](https://github.com/gottaeat/mss-nfqws)
  DPI circumvention tool ported to Meson with sane SystemD support, OpenWRT
  packaging and pre-builts.
### production services
- [mserv](https://github.com/gottaeat/mserv)
  Dockerized secure-out-of-the-box production quality SMTP+IMAP4 server
- [docker-recursive-bind](https://github.com/gottaeat/docker-recursive-bind)
  Dockerized configurable recursive BIND9 named installation. 
### misc utilities
- [irc-docker](https://github.com/gottaeat/irc-docker)
  Set-up and forget docker container for deploying IRSSI+tmux, exposed via
  rootless sshd.
- [ioquake3-docker](https://github.com/gottaeat/ioquake3-docker)
  Containerized ioQuake3 server setup.
