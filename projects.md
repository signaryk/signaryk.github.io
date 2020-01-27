---
layout: page
title: "Projects"
permalink: /projects/
---
## Current Projects

**Arch Linux ARM**: Porting the Arch Linux ARM distribution to the Pinebook Pro platform. Creating Docker images and build scripts for reproducible builds of the root filesystem, kernel, and u-boot.

**This Website**: A home for projects I work on and reports of things things I find interesting. It also contains an online, expanded version of my résumé that contains the current version of the printed document. 

**Distributed Compiling with Distcc**: Testing the usage of `distcc` with a small home cluster of aarch64-based computers and x86-based computers with an aarch64 cross-compiler. Testing by compiling and packaging the Linux kernel with patches for the Pinebook Pro with Arch Linux's `makepkg`. 

**WireGuard**: Testing the in-development WireGuard VPN protocol to provide secure, remote access to personal computing resources.


## Past Projects 

**ARM CPU Architecture**: Studying the ARM CPU architecture through Assembly programming and Verilog behaviour modelling (part of academic coursework). The final result of the laboratory portion of the course produced a single-cycle processor that can execute LEGv8 instructions (a modified ARMv8 instruction set).

**Singularity**: testing and documenting the usage of the Singularity container platform for researchers as an unprivileged alternative to Docker. The software is able to run Docker containers without requiring root access, the user being part of a group that is able to gain root access, or using a privileged daemon. It maintains the users UID inside the container and does not allow the usage of setuid binaries. 

**Kerberos-Authenticated Printing with CUPS**: Authenticating for printers belonging to an SMB printer share from Linux workstations with Active Directory user logins. 