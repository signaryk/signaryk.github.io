---
layout: portfolio
title: "Portfolio"
permalink: /portfolio/
cwd: portfolio
---
# Projects
Some of my projects can be found on my [GitHub](https://github.com/signaryk) profile.

## Operating Systems
**Arch Linux ARM**: I am working on porting [Arch Linux ARM](https://archlinuxarm.org) to the 
[Pinebook Pro](https://www.pine64.org/pinebook-pro/), a previously unsupported
platform. In order to do this, I'm creating a repository to host binary packages of patched mainline Linux 
kernel, u-boot, and other necessary firmware files. I am also working on writing shell scripts and creating
[Docker](https://www.docker.com) images to help me automate the build work.

**Cross-compiling with `distcc`**: To support my efforts in maintaining a platform for Arch Linux ARM, I'm
using the program `distcc` to distribute builds from a slower-compiling ARM-based SBC to a cross-compiler
on an x86-based workstation. This significantly speeds up build times for large packages such as the Linux
kernel.

**WireGuard**: I have been testing the relatively new [WireGuard](https://wireguard.com) 
VPN protocol in order to access my personal
computing resources securely while away from home and secure my Internet traffic on untrusted networks. Since
the protocol has no support for DHCP, IP addresses must be statically assigned. In order to create a
functioning network, I've had to learn a bit about RFC 1918 IPv4 addressing, CIDR, and IPv6 addressing. 

**Void Linux Binary Packages**: I have contributed to updating a few packages for the 
[Void Linux](https://voidlinux.org) distribution.
Most of this work involved updating build templates, testing the resulting package by compiling and installing
a locally-built version of the package based off the template, and following the project's Git workflow for
submitting changes to templates for automatic package building. 

## Programming
**Academic assignments**: In my academic career I've worked on many programming assignments in C++ designed
to help me explore general programming principles and practices, data structures and algorithms, and 
interacting with the operating system through POSIX APIs in the C and C++ standard libraries. My most ambitious
project has been writing a client process which can concurrently send requests and receive data from a remote 
server via TCP/IP, and safely write the received data to a file even with 15,000 threads working on the same
file.

**Go**: In a self-guided course of study, I am learning the [Go programming language](https://golang.org) 
by implementing some of the topics learned in past computer science courses in Go instead of C++. As an
example, I've written a solution to a version of the classic reader-writer problem in Go, with 200 threads
(known as "goroutines" in Go) concurrently either producing data or consuming that data. This solution has
two implementations, one utilising mutexes and thread locking, and the other using Go's native "channels"
to share data in a thread-safe manner.  

## Web
**Personal website**: Using the [Jekyll](https://github.com/jekyll/jekyll) static website generator, I've 
constructed two websites, 
[Silver Knoll](https://silverknoll.net) and [TAMU](http://people.tamu.edu/~william.luke21), which serve as my
digital contact card, resume, and portfolio.

**NextCloud**: I host an instance of [NextCloud](https://nextcloud.com) on a VPS provider in order to store 
my files remotely and maintain access to them from any of my devices.

**Email**: In the past I ran my own SMTP and IMAP servers to manage my @silverknoll.net email address.
