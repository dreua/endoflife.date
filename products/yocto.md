---
title: Yocto Project
layout: post
category: os
sortReleasesBy: "releaseCycle"
changelogTemplate: "https://docs.yoctoproject.org/migration-guides/migration-__VERSION_NUMBER__.html"
iconSlug: NA

releases:
#  - releaseCycle: "3.5 'kirkstone'"
#    versionNumber: "3.5"
#    cycleShortHand: kirkstone
#    lts: true
#    release: 2022-04-01
#    eol:     2024-04-01
#
#  - releaseCycle: "3.4 'honister'"
#    versionNumber: "3.4"
#    cycleShortHand: honister
#    lts: false
#    release: 2021-10-01
#    eol:     2022-05-01

  - releaseCycle: "3.3 'hardknott'"
    versionNumber: "3.3"
    cycleShortHand: hardknott
    lts: false
    latest: "3.3.3"
    release: 2021-04-01
    eol:     2021-11-01

  - releaseCycle: "3.2 'gatesgarth'"
    versionNumber: "3.2"
    cycleShortHand: gatesgarth
    lts: false
    latest: "3.2.4"
    release: 2020-10-01
    eol:     2021-05-01

  - releaseCycle: "3.1 'dunfell'"
    versionNumber: "3.1"
    cycleShortHand: dunfell
    lts: true
    latest: "3.1.11"
    release: 2020-04-01
    eol:     2024-04-01

  - releaseCycle: "3.0 'zeus'"
    versionNumber: "3.0"
    cycleShortHand: zeus
    lts: false
    latest: "3.0.4"
    release: 2019-10-01
    eol:     2020-08-01

  - releaseCycle: "2.7 'warrior'"
    versionNumber: "2.7"
    cycleShortHand: warrior
    lts: false
    latest: "2.7.4"
    release: 2019-04-01
    eol:     2020-06-01

permalink: /yocto
alternate_urls:
  - /yocto-project
link: https://wiki.yoctoproject.org/wiki/Stable_Release_and_LTS
activeSupportColumn: false
releaseColumn: true
releaseDateColumn: true
eolColumn: Support Status
discontinuedColumn: false
command: bitbake -e | grep '^DISTRO_VERSION\|DISTRO_CODENAME='
---
> The [Yocto Project](https://www.yoctoproject.org/) is a Linux Foundation project that helps developers create custom Linux-based systems and distributions regardless of the hardware architecture.

Long-Term Support (LTS) releases are made usually every 2 years, and maintained for 2 years after their initial release. Minor releases for supported stable and LTS branches (e.g. 3.0.1, 3.0.2, 3.1.1, …) are released on an unscheduled basis, usually when enough significant bug fixes have been accumulated.

After the maintainance window has ended, releases can enter a community support phase if a community maintainer steps up.
Community support is best-effort, and testing usually does not cover all initially supported platforms.
A release enters End-of-Life status if no community maintainer steps up, or when there is no longer an active community maintainer for 2 months.

Yocto stable releases (e.g. 3.0, 3.1, 3.2, 3.3…) are made about every 6 months, usually in April and October.
Stable releases are maintained seven months after the initial release.
