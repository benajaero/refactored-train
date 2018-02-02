---
title: Why I'm Using Arch As My Base
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
header:
  image: /assets/Arch-Linux.png
---

*Upon careful consideration and research, I've decided to use Arch Linux as the base for my operating system.*

An important aspect in creating an optimal programming environment is the actual virtual virtual environment. The operating system manages processes, memory usage and input/output streams. It's composed of various programs that interlock together to control usage of hardware. There were a number of methods I considered for creating my operating system.

### Entirely hand-written system from scratch

This would entail me personally writing the code for everything including the kernel, shell, etc. This was honestly the most ridiculous route I could choose. Operating Systems such as Ubuntu or Windows are the combined effort of thousands of developers over several decades. To individually write all the components that compose these OS would take much longer than 6 months, probably much longer than a human lifespan. While I could knock up something that somewhat fits the specification of an OS in 6 months, it would be rather barebones, unreliable and unable to dependably run on my hardware. And since I'm actually planning to use the operating system, that would be unsatisfactory.

### Individually Assemble Components (aka Linux From Scratch)

A few years ago, I came across a project designed to promote familiarity with the GNU/Linux subsystems. It's called Linux From Scratch and is comprised of resources that slowly guide the user to assembling their own GNU/Linux system through a rather complex yet simple set of steps. I was originally leaning toward this pathway however there were two complications that I foresaw. 

0. There would be no prebuilt binaries for this system
1. There would be no package manager. At least with a sizable userbase that would contribute packages.

Problem No.0 means that all software on the system has to be separately compiled. Depending on the complexity of the code, how many executables I have to compile and the speed of my system this could take several hours, which is certainly not **optimal**. This is the same problem with a similar GNU/Linux distro known as Gentoo in which source code most be compiled by the user. 

Problem No.1 is similar to the first problem in that installation would be made more difficult than it needs to be. A good package manager automatically handles dependencies and version collision. It makes it easy to install, remove or distribute software. It can quickly become a nightmare to handle thousands of dependencies by hand. While I could install a package manager with the LFS system, it would miss the most important advantage of a package manager, *packages*.


### Using an existing distro as a base

Because of issues 0 and 1, I wasn't sure how to proceed. I wanted the customizability and specialised vibe of a handmade system while also desiring the usability and reliability of an ubiquitous system such as Debian or Fedora. I realised I could build upon an existing distribution to take advantage of it's package manager. The only issue was whether the creation would count as a custom GNU/Linux operating system however I observed that many GNU/Linux distributions or operating systems I had encountered where actually built upon pre-existing distributions. Some notable examples of this are:

* Ubuntu, the beginner-friendly remix of Debian
* Manjaro, the easier to deal with version of Arch Linux
* Linux Mint, a Ubuntu-based operating system

The only thing left was to choose which distribution use. I wanted something relatively light-weight, that afforded customizability and had a powerful package-manager. This left me with Arch Linux which somewhat allows me to assemble my own packages, therefore allowing me to prevent bloat and comes with the iconic *pacman* package manager as well as the support of the extensive *Arch User Repository* or AUR.

