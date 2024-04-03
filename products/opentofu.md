---
title: OpenTofu
category: app
tags: cncf
iconSlug: opentofu
permalink: /opentofu
alternate_urls:
-   /tofu
-   /open-tofu
versionCommand: tofu --version
changelogTemplate: https://github.com/opentofu/opentofu/blob/v__LATEST__/CHANGELOG.md
releaseDateColumn: true

auto:
  methods:
  -   git: https://github.com/opentofu/opentofu.git

# eol(x) = releaseDate(x+2)
releases:
-   releaseCycle: "1.6"
    releaseDate: 2024-01-09
    eol: false # releaseDate(1.8)
    latest: "1.6.2"
    latestReleaseDate: 2024-02-22

---

> [OpenTofu](https://opentofu.org/) is a fork of Terraform that is open-source, community-driven, and managed by the Linux Foundation.

In their 2024-01-22 meeting, the OpenTofu Technical Steering Committee (TSC) [decided to adopt
the same support policy as Terraform](https://github.com/opentofu/opentofu/blob/main/TSC_SUMMARY.md#agenda-2):
patches for the most recent major release, as well as up to two prior ones. So up to three releases
will be supported at any given point in time.