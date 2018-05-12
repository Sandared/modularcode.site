---
title: The Workspace
layout: nested
lprev: prerequisites
lnext: background
description: Setup a bnd workspace
---

{% include shared_content/workspace.md %}

## Existing Setup

The standard OSGi enRoute setup uses a Maven repository and a number of indexed repositories. You can find these definitions in `./cnf/ext/enroute.bnd` and `./cnf/ext/enroute-distro.bnd`. Look at the created plugins. In this tutorial, we will replace the Release repository and the Maven Central repository by overwriting the values for their plugin definitions.

In a company wide setup it is recommended to create a custom workspace that has this setup.

## Next

In the next section of this quick start tutorial we will create a sample application. 
