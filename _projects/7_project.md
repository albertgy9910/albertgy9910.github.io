---
layout: page
title: SurfStore
description: A Distributed Cloud Storage Server
img: assets/img/dropbox.jpeg
importance: 2
category: work
---

**SurfStore: Distributed Cloud Storage Server Project (Jan 2023 - Mar 2023)**  
**[View Project](https://github.com/albertgy9910/SurfStore)**

This project involved the design and implementation of a Dropbox-like cloud-based file storage service using Go. The service features distributed storage and consistent hashing algorithms to manage files efficiently across multiple servers.

- Designed and implemented a Dropbox-like cloud-based file storage service using Go, featuring distributed storage and consistent hashing algorithms for efficient file management.
- Built for large-scale data handling, the project showcased excellent scalability during tests and efficiently met the data storage demands of thousands of users through client-server communication via gRPC.
- Enhanced the system's fault tolerance by implementing the RAFT distributed consensus protocol, which led to a 50% improvement in error recovery efficiency during testing.

<div class="caption">
    The SurfStore project is a scalable, fault-tolerant cloud storage solution developed with Go, featuring distributed storage and gRPC communication.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/dropbox.jpeg" title="SurfStore Project" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This project showcases excellent scalability and fault tolerance, crucial for large-scale data handling.
</div>

<div class="caption">
    The system's architecture includes the implementation of RAFT protocol to ensure fault tolerance and improved error recovery.
</div>
