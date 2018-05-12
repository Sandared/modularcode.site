---
title: Continuous Integration
layout: nested
lprev: nexus
lnext: start
description: Use Continuous Integration to release snapshots and master releases
---
# Continuous Integration

In this section we take a look at how to setup Continuous Integration to release to a Maven Nexus or Artifactory repository.

## Strategy

In the previous section we setup a Release repository that pointed to a Nexus. We can reuse this exact settings. The only thing we need to ensure is that we call the release operation in our continuous build.



