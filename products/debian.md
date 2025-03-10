---
permalink: /debian
layout: post
title: Debian
command: lsb_release --release
category: os
link: https://wiki.debian.org/DebianReleases
activeSupportColumn: false
releaseColumn: true
releaseDateColumn: true
sortReleasesBy: 'release'
releases:
  - releaseCycle: 'Debian 11 "Bullseye"'
    release: 2021-08-14
    eol: 2026-08-15
    latest: "11.1"
    link: https://www.debian.org/News/2021/20211009
  - releaseCycle: 'Debian 10 "Buster"'
    release: 2019-07-06
    eol: 2024-06-01
    latest: "10.11"
    link: https://www.debian.org/News/2021/2021100902
  - releaseCycle: 'Debian 9 "Stretch"'
    # Debian has its LTS and non-LTS version in same time
    # We are keeping both of them until non-LTS reaches EOL
    release: 2017-06-17
    eol: 2022-06-30
    lts: true
    latest: "9.13"
    link: https://lists.debian.org/debian-announce/2020/msg00004.html
  - releaseCycle: 'Debian 9 "Stretch"'
    # Debian has its LTS and non-LTS version in same time
    # We are keeping both of them until non-LTS reaches EOL
    release: 2017-06-17
    eol: 2020-01-01
    latest: "9.13"
    link: https://lists.debian.org/debian-announce/2020/msg00004.html
  - releaseCycle: 'Debian 8 "Jessie"'
    release: 2015-04-26
    eol: 2020-06-30
    lts: true
    latest: "8.11"
    link: https://www.debian.org/News/2015/20150426
  - releaseCycle: 'Debian 7 "Wheezy"'
    release: 2013-05-04
    eol: 2018-05-31
    lts: true
    link: https://www.debian.org/News/2013/20130504
  - releaseCycle: 'Debian 6 "Squeeze"'
    release: 2011-02-06
    eol: 2016-02-29
    lts: true
    link: https://www.debian.org/News/2011/20110205a

---

> [Debian](https://www.debian.org/) is a free operating system for your computer. The Debian Stable branch is the most popular edition for personal computers and network servers, and is used as the basis for many other Linux distributions.

At any given time, there is one stable release of Debian, which has the support of the Debian security team. When a new stable version is released, the security team will usually cover the previous version for a year or so, while they also cover the new/current version. Only stable is recommended for production use.

[Debian Long Term Support (LTS)](https://wiki.debian.org/LTS) is a project to extend the lifetime of all Debian stable releases to (at least) 5 years. Debian LTS will not be handled by the Debian security team, but by a separate group of volunteers and companies interested in making it a success. Not all packages of the Debian archive are supported by LTS, the [debian-security-support](https://wiki.debian.org/LTS/Using#Check_for_unsupported_packages) package can check for unsupported packages.

A commercial offering for [Extended Long Term Support](https://wiki.debian.org/LTS/Extended) is available
