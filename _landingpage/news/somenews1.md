---
layout: news
title: OSGi R7 Highlights - Cluster Information Specification
author: Tim Verbelen
published_at: 2018-04-24
link: https://blog.osgi.org/2018/04/osgi-r7-highlights-cluster-information.html
---
In my experience, one of the most powerful parts of the OSGi specification are the Remote Services and Remote Service Admin, which enable you to develop complex, distributed applications in a modular way. However, in order to deploy such a distributed application, it is key to find out on which devices bundles can be deployed. In previous releases, OSGi specifications for remote management are already available for certain domains (i.e. telecommunications with TR-069 Connector Service) or protocols (i.e., REST Management Service).
With OSGi R7, we now introduce the Cluster Information specification, a protocol-agnostic specification to discover, list and inspect the available devices in a distributed compute environment, and to provision these devices with OSGi bundles.