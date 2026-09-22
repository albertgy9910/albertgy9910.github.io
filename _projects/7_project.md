---
layout: page
title: SurfStore
description: A Distributed Cloud Storage Server
img: assets/img/dropbox.jpeg
importance: 2
category: work
---

**SurfStore: Distributed Cloud Storage Server Project (Go, gRPC, RAFT)**  
**[View Project](https://github.com/albertgy9910/SurfStore)**

A Dropbox-like distributed file storage service in Go, using consistent hashing to place blocks across multiple BlockStores and gRPC for client-metadata communication.

- Designed and implemented a Dropbox-like distributed file storage service in Go, using consistent hashing to place blocks across multiple BlockStores and gRPC for client-metadata communication.
- Enhanced fault tolerance by implementing the RAFT consensus protocol over the metadata service, keeping the store available and consistent through simulated leader crashes and network partitions.

<div class="caption">
    The SurfStore project is a scalable, fault-tolerant cloud storage solution developed with Go, featuring distributed storage and gRPC communication.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/dropbox.jpeg" title="SurfStore Project" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
