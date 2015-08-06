# Install Docker - 32-bit Debian Jessie Host

This repository is dedicated to the task of installing Docker on a 32-bit/i386 host OS that is based on Debian Jessie.  If you are using a 64-bit installation of Linux (or OS X or Windows), there is plenty of support for you elsewhere.

## Prerequisites
You must have Git installed, and you must have Sudo privileges.

## Procedure
Open a terminal window, and enter the following commands:
<pre>
git clone https://github.com/jhsu802701/docker-install-32bit-debian-jessie.git
cd docker-install-32bit-debian-jessie
sh main.sh
</pre>

The screen output is saved in the log directory.

## What's the point?
Most of the material you can read on Docker is geared for those using a 64-bit host OS, which requires a 64-bit computer.  If you are using a 32-bit computer, or if you are using a 64-bit computer with a 32-bit host OS, then this GitHub repository is for you.

## Why would you still use a 32-bit system?
A 64-bit OS needs at least 4 GB of memory to outperform a similar 32-bit OS on a given computer.  Many older computers can only run a 32-bit OS.  Older PCs that do not have at least 4 GB of memory and/or can only run a 32-bit OS are cheaper than newer PCs.  Because desktop PCs depreciate rapidly, used ones provide plenty of value for the money to Linux users.
