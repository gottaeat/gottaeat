# projects
## osdev and tooling
- [apathy](https://github.com/gottaeat/apathy)
  Independent homegrown operating system featuring Linux in its core,
  supplemented with musl libc and a standalone LLVM suite.
- [bootstrap-standalone-llvm](https://github.com/gottaeat/bootstrap-standalone-llvm)
  Containerized boostrapper to build a non-GNU, standalone, self-hosting and
  portable LLVM suite.
- [openwrt-builds](https://github.com/gottaeat/openwrt-builds)
  Containerized OpenWRT squashFS and toolchain builder with jinja2 templating
  support for rootfs default overrides.
- [wrt-sdk-build](https://github.com/gottaeat/wrt-sdk-build)
  OpenWRT SDK builder, useful for building SDK targets other than the officially
  supplied x86_64 ones.

## protocol implementations
- [bands](https://github.com/gottaeat/bands)
  RFC 1459 and 2812 compliant (with a bit of IRCv3), concurrent IRC bot with
  extensive and extendable features.

## automation and cloud 
- [setboxes](https://github.com/gottaeat/setboxes)
  Ansible playbook, and utilities utilizing libVirt, to generate Arch Linux
  based per-target rootfs images and to maintain once written to baremetal.
- [cloudvirt](https://github.com/gottaeat/cloudvirt)
  CloudVirt creates and destroys cloud-init powered x86_64 VMs utilizing the
  libVirt API.
- [genutm](https://github.com/gottaeat/genutm)
  GenUTM creates aarch64 Linux VMs that run via Apple Virtualization Framework
  utilizing UTM bundles, alongside the CIDATA cloud-init ISOs that hold the
  user-data and meta-data YAMLs.

## mail + dns
- [mserv](https://github.com/gottaeat/mserv)
  Dockerized secure-out-of-the-box production quality SMTP+IMAP4 server
- [docker-bind](https://github.com/gottaeat/docker-bind)
  Configurable BIND9 named container that allows for setting up a forwarding or
  recursive nameserver.
- [zonegen](https://github.com/gottaeat/zonegen)
  DDNS implementation for OpenWRT odhcpd to be able to update BIND via rndc on
  every DHCP lease action without external dependencies.

## networking
- [genwg](https://github.com/gottaeat/genwg)
  WireGuard client and server configuration generator that creates BIND zones
  for servers with A and PTR records for the clients, supports WG over FakeTCP
  and has system DNS resolver awareness beyond just systemd-resolved.
- [wya](https://github.com/gottaeat/wya)
  Dockerized IP ASN and geolocation lookup tool built with Flask and GeoLite2
  databases.
- [mss-nfqws](https://github.com/gottaeat/mss-nfqws)
  DPI circumvention tool ported to Meson with sane SystemD support, OpenWRT
  packaging and pre-builts.

## miscellaneous
- [chatbox](https://github.com/gottaeat/chatbox)
  Chatbox sets up an Alpine-based Docker container that starts IRSSI in a tmux
  session and exposes it rootlessly via Dropbear.
- [ioquake3-docker](https://github.com/gottaeat/ioquake3-docker)
  Containerized ioQuake3 server setup.
