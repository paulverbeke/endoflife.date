---
title: Coder
category: server-app
iconSlug: coder
permalink: /coder
versionCommand: coder version
releasePolicyLink: https://coder.com/docs/install/releases
changelogTemplate: https://github.com/coder/coder/releases/tag/v__LATEST__
eoasColumn: true
eoasWarnThreshold: 60
eolWarnThreshold: 90

identifiers:
-   repology: coder
-   purl: pkg:github/coder/coder
-   purl: pkg:generic/coder

auto:
  methods:
  -   git: https://github.com/coder/coder.git

# eoas(x) = releaseDate(x+2)
# eol(x) = releaseDate(x+3)
releases:
-   releaseCycle: "2.24"
    releaseDate: 2025-07-01
    eoas: false # releaseDate(2.26)
    eol: false # releaseDate(2.27)
    latest: "2.24.1"
    latestReleaseDate: 2025-07-02

-   releaseCycle: "2.23"
    releaseDate: 2025-06-03
    eoas: false # releaseDate(2.25)
    eol: false # releaseDate(2.26)
    latest: "2.23.2"
    latestReleaseDate: 2025-06-30

-   releaseCycle: "2.22"
    releaseDate: 2025-05-16
    eoas: 2025-07-01
    eol: false # releaseDate(2.25)
    latest: "2.22.1"
    latestReleaseDate: 2025-05-20

-   releaseCycle: "2.21"
    releaseDate: 2025-04-01
    eoas: 2025-06-03
    eol: 2025-07-01
    latest: "2.21.3"
    latestReleaseDate: 2025-04-29

-   releaseCycle: "2.20"
    releaseDate: 2025-03-05
    eoas: 2025-05-16
    eol: 2025-06-03
    latest: "2.20.3"
    latestReleaseDate: 2025-04-29

-   releaseCycle: "2.19"
    releaseDate: 2025-02-04
    eoas: 2025-04-01
    eol: 2025-05-16
    latest: "2.19.3"
    latestReleaseDate: 2025-04-29

-   releaseCycle: "2.18"
    releaseDate: 2024-12-03
    eoas: 2025-03-05
    eol: 2025-04-01
    latest: "2.18.5"
    latestReleaseDate: 2025-01-30

-   releaseCycle: "2.17"
    releaseDate: 2024-11-05
    eoas: 2025-02-04 # releaseDate(2.19)
    eol: 2025-03-05
    latest: "2.17.3"
    latestReleaseDate: 2024-12-13

-   releaseCycle: "2.16"
    releaseDate: 2024-10-01
    eoas: 2024-12-03 # releaseDate(2.18)
    eol: 2025-02-04 # releaseDate(2.19)
    latest: "2.16.1"
    latestReleaseDate: 2024-10-28

-   releaseCycle: "2.15"
    releaseDate: 2024-09-03
    eoas: 2024-11-05 # releaseDate(2.17)
    eol: 2024-12-03 # releaseDate(2.18)
    latest: "2.15.4"
    latestReleaseDate: 2024-10-28

-   releaseCycle: "2.14"
    releaseDate: 2024-08-06
    eoas: 2024-10-01 # releaseDate(2.16)
    eol: 2024-11-05 # releaseDate(2.17)
    latest: "2.14.4"
    latestReleaseDate: 2024-10-28

-   releaseCycle: "2.13"
    releaseDate: 2024-07-02
    eoas: 2024-09-03 # releaseDate(2.15)
    eol: 2024-10-01 # releaseDate(2.16)
    latest: "2.13.5"
    latestReleaseDate: 2024-08-20

-   releaseCycle: "2.12"
    releaseDate: 2024-06-04
    eoas: 2024-08-06 # releaseDate(2.14)
    eol: 2024-09-03 # releaseDate(2.15)
    latest: "2.12.6"
    latestReleaseDate: 2024-08-01

-   releaseCycle: "2.11"
    releaseDate: 2024-05-07
    eoas: 2024-07-02 # releaseDate(2.13)
    eol: 2024-08-06 # releaseDate(2.14)
    latest: "2.11.4"
    latestReleaseDate: 2024-06-24

-   releaseCycle: "2.10"
    releaseDate: 2024-04-03
    eoas: 2024-06-04 # releaseDate(2.12)
    eol: 2024-07-02 # releaseDate(2.13)
    latest: "2.10.3"
    latestReleaseDate: 2024-05-22

-   releaseCycle: "2.9"
    releaseDate: 2024-03-07
    eoas: 2024-05-07 # releaseDate(2.11)
    eol: 2024-06-04 # releaseDate(2.12)
    latest: "2.9.4"
    latestReleaseDate: 2024-04-22

-   releaseCycle: "2.8"
    releaseDate: 2024-02-06
    eoas: 2024-04-03 # releaseDate(2.10)
    eol: 2024-05-07 # releaseDate(2.11)
    latest: "2.8.5"
    latestReleaseDate: 2024-03-09

-   releaseCycle: "2.7"
    releaseDate: 2024-01-01
    eoas: 2024-03-07 # releaseDate(2.9)
    eol: 2024-04-03 # releaseDate(2.10)
    latest: "2.7.3"
    latestReleaseDate: 2024-03-04

---

> [Coder](https://coder.com) is an open-source platform for creating and managing developer workspaces on your preferred
> clouds and servers.

There is a new minor release of Coder on the first Tuesday of each month. Minor releases are
supported for three months with bug and security fixes the first month, major bug and security
fixes the second month, and only security fixes the third month.
