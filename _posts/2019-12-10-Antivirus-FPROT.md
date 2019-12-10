---
layout: post
title: 'Download and use F-PROT antivirus for linux'
tags: ["X-forwarding", "ssh"]
---

## Download 

- visit [here](http://www.f-prot.com/download/home_user/download_fplinux.html)
- download F-PROT Antivirus for Linux Workstations Version 6.2.39 (GZIP-ed TAR file)
- extract TAR file by `tar -xzvf`

## Simple command 
- `fpscan -a`
  - /all	Scan every files found on your computer. 
  Specifying additional paths after this switch has no effect since any path is a subset of all. 
  Boot sectors will also be scanned.

- `fpscan -l`
  - /local	Scan all local disks/partitions. 
  Specifying additional paths causes those paths to be scanned as well.

- `fpscan -n`
   - /network	Scan every files on every network drive/share. 
   Specifying additional paths causes those paths to be scanned as well.

- `fpscan -b`
  - /boot	Scan all boot sectors.
 
---
