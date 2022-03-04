+++
title = "About Me"
description = "Christiano Haesbaert"
date = "2022-03-04"
aliases = ["about", "about-me"]
author = "Christiano Haesbaert"
+++

I'm a BSD-kernel/ocaml/parallel-programmer type of person (yes, we
exist!). I was involved with multiple opensource projects, most
importantly [OpenBSD](https://www.openbsd.org) and
[MirageOS](https://mirage.io).

## OpenBSD

In [OpenBSD](https://www.openbsd.org) I worked on general kernel bug
fixing, mostly scheduler and network, because of this involvement I
got invited to join [genua](https://genua.eu), where I worked for a
9.9 years. At [genua](https://genua.eu) I led the project to
parallelize the [OpenBSD](https://www.openbsd.org) kernel network
stack, we started from a completely single threaded kernel and today
the kernel scales up to a factor of 15. I got to write very
interesting things like lockless
[pf(4)](https://man.openbsd.org/pf.4),
[pfsync(4)](https://man.openbsd.org/pfsync.4) as well as rewrite
allocators, packet queues, drivers and more to scale with multiple
cores. I also rewrote the whole interrupt handler layer of
[Bitrig](https://www.bitrig.org) and implemented kernel preemption (it
worked, I swear !)

## MirageOS

I got involved with [MirageOS](https://mirage.io) in 2014 after
hearing from a friend that "Anil is writing DNS with unikernels", at
the time I was looking for a break from kernel hacking and this seemed
like a good bet, I then bought [Real World
Ocaml](https://dev.realworldocaml.org/) to learn the basics and
quickly fell in love with the language.

Since then I've had the privilege of authoring some projects which are
now incorporated into mainstream MirageOS:

* [charrua-dhcp](https://github.com/mirage/charrua) - DHCP as a
  library, also used by [Docker
  Desktop](https://https://www.docker.com/products/docker-desktop)
* [awa-ssh](https://github.com/mirage/awa-ssh) - SSH as a library
* [rawlink](https://github.com/haesbaert/rawlink) - an interface for BPF/AF_PACKET

### Interviews

I gave a couple of interviews about [MirageOS](https://mirage.io) and
[awa-ssh](https://github.com/mirage/awa-ssh)
* [Functional Geekery Episode 99](https://www.functionalgeekery.com/episode-99-christiano-haesbaert/)
* [Mirage Profiles 004](https://mirage.metaebene.me/2017/12/07/mp004-christiano-haesbaert/)

## OpenMDNS

[OpenMDNS](https://github.com/haesbaert/mdnsd) is a full stack
implementation of MDNS/DNS-SD and it was my bachelor thesis, it aimed
to be a replacement for Bonjour and Avahi.
