# Investigating - 15 Dec 2017

### General Information

Topic:*The relationship between physical, virtual and abstract computing components*
Research Question: *How do physical and virtual subsystems combine to form an optimal programming environment?*

Goal: My goal is to provide the programming community with tools to improve software development through a custom environment comprised of customised hardware, a customised operating system and a custom programming language.

Global Context: Scientific and technical innovation
For my global context I was originally split between doing *personal and cultural expression* and *scientific and technical innovation*. I had considered doing 'metacognition and abstract thinking' since programming falls under abstract thinking. However, I realised that this context didn't encompass my entire project but rather just a small subsection. After this, I looked at the Scientific and Technical Innovation context since Computer (Technology) Science (scientific) fits under the context. From here, I chose the models/systems/processes subcategory since it best matched my topic.

Personal Interest in Project:

### Questions
*27 Jan 2018*

- What will my outcome or product look like?

The outcome of my project will be a specialized programming environment/setup in both hardware and software. This will be in the form of a custom-built computer, an operating system running on the computer, various software utilies, scripts and configuration files.

- What type of components will I use

> PC Building
> * PCPartpicker to collate parts
> * Parts (CPU, GPU, RAM, etc)
> * Phillips Screwdriver
> * Thermal Paste

> Linux Distribution 
> * GNU/Linux Coreutils
> * Linux Kernel
> * Git Version Control
> * A window manager / tile manager
> * Package Manager 
> * Various scripts
> * Configuration files

> Programming Language 
> * Lexer
> * Parser Generator
> * Compiler

- What techniques/approaches will I use?

> * Abstraction 
> * Generics
> * Modular Programming
> * Extensibility
> * The Unix Philosophy

TODO: Add approaches to learning

- What type of information will I include?

- How will I present the information?

- Will I include visuals?

- Do I need to consider any copyright or intellectual property issues? ▪ Who is the audience?

> GNU/Linux and its deriatives are automatically under the GNU Public License, which is a copyleft license. This license places a large emphasis on **freedom** (free as in speech) and power to the the user. It entails that all source code must be made somewhat available to the user, so that the user may modify however they decide to. Apart from these requirements, there aren't really any issues that I need to consider. 
> 
> The audience, as in the spirit of GNU/Linux, is anyone who wishes to empower themselves and use *free* software.

- How will I get feedback?

> I can get surface level feedback by asking people around me to try the system. However to get deeper feedback, I'd have to mostly rely on my own experience and other people who may decide to go throw the hassle of installing a new operating system. It'd be relatively easy to get feedback for the programming language since it should be easy to install.


### What do I already know?

I recently wrote an emulator, replicating the computer system of the Intel 8080, to interface instructions for the 8080 with my operating system. During this process, I gained a better understanding of how the kernel interfaces various computer components together to create a system capable of executing code on the fly. I've used many operating systems via manual installation or through virtualization and have learned what aspects I enjoy in an operating system.I know how to program using low-level languages as well as create scripts. I know how to use a Unix shell. This will be helpful in creating an operating system since that requires effective configuration and specialised scripts.

I know about programming paradigmns such as object-oriented, functional and imperative programming. I'm know how to program in several programming languages including C, C++, MIT Scheme, Javascript and Swift. I know about compilers and interpreters and I have a shallow understanding about how code is compiled/interpreted and executed. This will be will be helpful to my project because it means I don't have to start from scratch and learn how to do basic programming, before learning to efficiently program for more complex problems.

# Plannning - 6 Feb 2018

## Criteria

Scientific and Technical Innovation:

My goal is to provide the programming community with tools to improve development through a custom environment comprised of customised hardware, a customised operating system and a custom programming language

### PC Building

Criteria | Not achieved | Achieved to some extent | Achieved to a large extent | Completely achieved | Explanations/comments
| --- | --- | --- | --- | --- | --- |
**Cost** | The price of my PC Parts is not within the budgetary range. The purchases are poorly/not documented. | The price of my PC parts is within the desired budgetary range and the purchases are sufficiently documented | The price of my PC parts is within the desired budgetary range. The purchases are carefully  documented and market fluctuations are taken into account for part-purchasing. | The price of my PC parts is within the desired budgetary range. The purchases are diligently documented and market fluctuations are taken into account for part-purchasing. | ...
**Aesthetics** | The parts are illogically and erratically placed. It is not possible to view inside the computer. The computer is too ostentatious. LED lighting is not used or overused. The wiring is messy and disorganized. | The placement of the installed parts is logical and organised. The computer is not ostentatious. LED lighting is utilized to an extent. Wiring is hidden from view. | The parts are optimally placed. The computer is not ostentatious and LED lighting of different colours is used. Wiring is hidden from view. | The parts are optimally placed. LED Lighting effects and animations are utilized. Wiring is hidden from view and carefully organised. | ... 
**Function** | The computer is unable to run an operating system. The GPU cannot render images on a monitor. There is no sound output and the cooling system is dysfunctional. It doesn't accept or process input. | The computer is able to run a lightweight operating system. It is able to render images to a monitor. The computer has sound output and doesn't overheat. The computer accepts and process keyboard input. | The computer is able to run more demanding operating systems. It renders HD images to a monitor. The cooling system is quiet and functional. The computer can receive sound input and output sound. The computer accepts and process keyboard, mouse and controller input. It can connect to USB devices and is capable of connecting to the internet. | The computer is able to run more demanding operating systems and a large variety of programs. It renders HD images to multiple monitors. The cooling system is quiet and efficient. The computer can process a large variety of inputs and devices. It is capable of connecting to the internet through ethernet and WiFi. | ...


### GNU / Linux distro

Criteria | Not achieved | Achieved to some extent | Achieved to a large extent | Completely achieved | Explanations/comments
| --- | --- | --- | --- | --- | --- |
**Graphics** | The operating system has no aesthetic theme or the themes and colours do not match. It has no GUI or it has a poor GUI. The GUI does not support tiling or separate workspaces. The operating system does not support HD rendering.  The GUI is not customizable or configurable. | The GUI has a coherent aesthetic theme. It supports tiling or separate workspaces. It supports HD rendering and other display options. It supports icon and theme customization and general configuration. | The GUI has a coherent aesthetic theme. It supports tiling and seprate workspaces. It has moving screen-savers and efficient window management. The GUI can be customized and supports advanced configuration via the terminal. | The GUI has several coherent themes. It supports tiling, separate workspaces and window management. It has moving screen-savers, cover flow and widgets such as weather and world time. It can be customized and configured in a shareable text format. | ...
**Function** | The operating system does not have a GUI or sound. It runs poorly or doesn't run at all. It manages programs and handles memory inefficiently. It has a poor filesystem. It has little or no user permission system. It isn't POSIX compliant and does not have a shell interface. It does not have a package manager. The system cannot be configured or personalized. The system does not increase ease of software development or deployment. | The operating system has a GUI and sound support. It runs on a x86 architecture and efficiently manages programs and memory. It has a satisfactory filesystem and a satisfactory permission system. It is fully POSIX-compliant and has a shell interface. It has a package-manager and allows for customization and personalization. Overall, the system makes it easier to develop software. | The operating system has a capable GUI and sound system. It runs on a x86 architecture and efficiently manages a wide range of programs and memory. It has a capable file-system and a well-designed permission system. It is fully POSIX-compliant and has a comfortable shell interface. It has a capable package-manager and allows for customization and personalization through files, scripts and other methods. Overall, the system makes it easier and more comfortable to develop software. | The operating system has a efficient and extendable GUI and sound system. It runs on a x86 architecture and is capable of emulating other architectures. It efficiently manages a wide range of programs and memory. It has a capable and efficient filesystem and a well-designed, secure permission system. It is fully POSIX-compliant and has compatibility layers to interface with non-POSIX programs. It has a comfortable shell interface and efficient text editors. It has an efficient package manager, capable of handling dependencies and different software versions. It allows for deep customization and personalization through files, scripts and other methods. Overall. the system makes it easier, more comfortable and efficient to develop software.

### Programming Language 

Criteria | Not achieved | Achieved to some extent | Achieved to a large extent | Completely achieved | Explanations/comments
| --- | --- | --- | --- | --- | --- |
**Features**|
**Function**| The programming language is not extensible. It cannot be used to create libraries or prackages nor can it be import libraries or packages. It can only be used on one operating system. The programming language is not Turing-complete and cannot be described in a text-format. The programming language does not have a compiler or interpreter. | The programming language is extensible. It cannot be used to create libraries or packages but it can import external libraries. It can be used on multiple operating system. The programming language is Turing-complete and can be described using the ASCII text format. The programming language has a compiler/interpreter. | The programming language is extensible. It supports and can be used to create libraries/packages. It can be used on a wide range of environments. The programming language is Turing-complete and can be described using the ASCII text format. The programming language has a compiler/interpreter. | The programming language is very extensible. It can be used to create libraries/packages and can import libraries from other programming languages. It can be used on a wide range of environments, including an online REPL.The programming language is Turing-complete and can be described using the Unicode text-format. The programming language has both a compiler and interpreter.

## Timeline

Date: Task | Resources required | Summer Holidays | Wk1 29/1 - 3/2 | Wk2 5/2 - 9/2 | Wk3 12/2 - 16/2 | Wk4 19/2 - 23/2 | Wk5 26/2 - 2/3 | Wk6 5/3 - 9/3 | Wk7 12/3 - 16/3 | Wk8 19/3 - 23/3


### General Timeline:
    * Meet with supervisor at least once each term
    * Complete building and researching PC by the end of March
    * Start the report at the beginning of term 3
    * Start researching and prototyping programming language in April
    * Start operating system during Term 2-3 holidays.

Supervisor: 
* Tuesday, Feb 13, Term 1
* Friday, June 22, Term 2
* Week 1, Term 3

PC:
* Finalize PC part list and budget - 3 Jan
* Receive parts and assemble PC - 30 March

Report:
* Start report on the 24th of July
* Finish report on the 17th of August

Programming language:
* Start - 6 April
* Finish stable prototype by 17 August
* Finish, test and write libraries by personal project presentation

Operating System: 
* Start researching operating system - 24 Jan
* Start operating system - 5 July


# Collaboration with Supervisor - 6 Feb 2018

### First Meeting - Tuesday, Feb 13, 2018

Discussed: 
* Topic, Goal, Context 
* Managebac, 
* Process Journal 
* Short and Long term goals (Planning) 
* Research 
* Recording

TODO: 
* Start researching 
* Timeline 
* Criteria 
* Answer questions

Next Meeting: 
Week 6 of Term 1

### Second Meeting - Friday, June 22, 2018

Discussed: 
* Timeline 
* Criteria 
* Research

Todo: 
* Timeline 
* Criteria 
* Research 
* Start first draft of report

Next Meeting: Beginning of Week 1, Term 3


# Process

## Building The Computer

### Final PC Part List - 3 Jan 2018
The final part list for the computer.


[PCPartPicker part list](https://au.pcpartpicker.com/list/LhqWM8) / [Price breakdown by merchant](https://au.pcpartpicker.com/list/LhqWM8/by_merchant/)

Type|Item|Price
:----|:----|:----
**CPU** | [Intel - Core i7-8700 3.2GHz 6-Core Processor](https://au.pcpartpicker.com/product/C9hj4D/intel-core-i7-8700-32ghz-6-core-processor-bx80684i78700) | $485.00 @ Umart 
**CPU Cooler** | [Deepcool - GAMMAXX 400 74.3 CFM CPU Cooler](https://au.pcpartpicker.com/product/hJFPxr/deepcool-cpu-cooler-gammaxx400) | $35.00 @ Umart 
**Motherboard** | [Asus - Prime Z370-P ATX LGA1151 Motherboard](https://au.pcpartpicker.com/product/mKCrxr/asus-prime-z370-p-atx-lga1151-motherboard-prime-z370-p) | $219.00 @ Umart 
**Memory** | [G.Skill - Ripjaws V Series 16GB (2 x 8GB) DDR4-3000 Memory](https://au.pcpartpicker.com/product/LhgPxr/gskill-memory-f43000c15d16gvrb) | $278.00 @ Umart 
**Storage** | [Crucial - MX300 1.1TB 2.5" Solid State Drive](https://au.pcpartpicker.com/product/bh38TW/crucial-mx300-11tb-25-solid-state-drive-ct1050mx300ssd1) | $339.00 @ Umart 
**Case** | [NZXT - S340 Elite (Black) ATX Mid Tower Case](https://au.pcpartpicker.com/product/3TYWGX/nzxt-ca-s340w-b3-atx-mid-tower-case-ca-s340w-b3) | $149.00 @ Umart 
**Other** | [NZXT HUE+ & Aer RGB120 Fans Bundle Pack RGB 2x 120mm Aer Fans Included](https://au.pcpartpicker.com/product/vvmxFT/nzxt-hue-aer-rgb120-fans-bundle-pack-rgb-2x-120mm-aer-fans-included) | $109.00 @ Umart 
**Other**| Power Supply| $99.00 
**Other**| Video card| $609.00 
 | *Prices include shipping, taxes, rebates, and discounts* |
 | **Total** | **$2322.00**
 | Generated by [PCPartPicker](http://pcpartpicker.com) 2018-01-03 16:25 AEDT+1100 |
 
 The video card is an ASUS Geforce 1070. 
 The power supply is a Corsair 550W 80+.

### Justification (Why these parts were chosen)

These parts were chosen using the website au.pcpartpicker.com.

### Why I'm Using Arch Linux As My Base - 27 Jan 2018

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

### Constructing The Computer - 30 March 2018

![PC Parts]({{site.url}}{{site.baseurl}}/assets/pcbuilding1.jpg)

Computer construction involves the connection and linkage of several electrical parts in order to form a functional Turing machine. This build was made up of various parts designed to maximise performance and compatibility while decreasing cost: 
* Central Processing Unit - Intel Core i7-8700
* CPU Coolers - Deepcool GAMMAXX 400, Intel Stock Cooler, Hyper 212 Evo
* Motherboard - Asus Prime Z370
* RAM - 2 x Ripjaws V 8gb
* Storage - Crucial MX300 1TB SSD
* Case - NZXT S340 Elite
* Fans - Aer RGB 120mm, 140mm
* Graphics Card - Asus Geforce 1070
* Power Supply - Corsair TX550M
* Other Accessories - NZXT Hue+ and Deepcool Fanhub

Equipment used:

* Non-static workbench
* A Phillips screwdriver
* Pliers (I can't remember if I used this but anyways)


### Connecting Basic System

The first step in building the computer is assembling the core components on the motherboard. This allows us to check whether our parts are faulty or incompatible. It will allow us to boot up the initial system and to check that everything posts.

| Installing the CPU | Installing RAM |
| --- | --- |
| ![PC Parts]({{site.url}}{{site.baseurl}}/assets/pcbuilding2.jpg) | ![PC Parts]({{site.url}}{{site.baseurl}}/assets/pcbuilding3.jpg) |

To install these: First remove the motherbox from its protective casing and lay it on a non-static workbench. The makeshift workbench used in the picture is simply the motherboard box. Check the motherboard for any obvious defects such as bent socket pins before installing the components. To install the CPU: Open up the CPU cover and remove the CPU from its box, avoiding touching sensitive areas. Align the CPU so that it is correctly oriented with the CPU socket, using the bottom-left triangle for reference. Gently place the CPU into the socket and close it.
Next, open the latches for the RAM slots and push in the RAM sticks according to the optimal layout in the motherboard manual. Press down firmly until the latches snap back up.

After this, we must install the CPU cooler. Squirt a small dollop of thermal paste on the centre of the CPU. This will spread out in an uniform fashion, allowing for efficient heat-transfer between the cooler and CPU. Based on what CPU and motherboard you have, use the appropriate pins to install the cooler. Finish by plugging the cooler into the CPU_FAN socket.

The last component to be installed is the GPU. This will only be temporarily installed as it has to be reinstalled separately in the case. Similarly to the RAM, pop open the PCLE slot, push in the GPU and connect it to a monitor.
Before booting up we need to connect the electronics to a power supply **TODO TOMORROW**

Finally, we can start up the system by shorting the PWR pins with a metal object. If everything was done correctly and all parts are functional, then the BIOS should successfully boot.

### Installing System In Case

Now that we have confirmed the parts are functional and compatible, they need to be permanently fixed in their chassis.



###  Issues and Notes

There were several unexpected issues in the construction of this computer. The first was dama



## Designing The Operating System

### Version Controlled Customization Files - 21 April 2018

https://github.com/Blaze349/config

Purpose:

* Syncing of configuration files
* Testing configuration files
* Version-control history for said files




## Creating The Programming Language

# Taking Action - 6 Feb 2018

# Reflecting - 6 Feb 2018
