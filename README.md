# Penguin

![Penguin · Logo](https://raw.githubusercontent.com/hxAri/hxAri/main/public/images/1701208743;6cxkEyg82i.png)

## Table of Contents
- [Penguin](#penguin)
  - [Table of Contents](#table-of-contents)
  - [Abouts](#abouts)
  - [Notes](#notes)
  - [Features](#features)
    - [Binary Execution](#binary-execution)
    - [Command Line Interface](#command-line-interface)
    - [Linux Distros](#linux-distros)
    - [Desktop Environment](#desktop-environment)
    - [Window manager](#window-manager)
  - [Dependency](#dependency)
  - [Environment](#environment)
      - [Warning](#warning)
  - [Installation](#installation)
  - [Usagement](#usagement)
  - [Sources](#sources)
  - [Support](#support)
  - [Licence](#licence)

## Abouts
**[Penguin](https://github.com/sudo-Penguin-Lalala/Penguin)** is a Command Line Tool to simplify the installation of Linux Distros to the Android Operating System using Termux as a Shell environment. **[Penguin](https://github.com/sudo-Penguin-Lalala/Penguin)** also supports more than 6 Linux Distros [see](#linux-distros), as well as several Desktop Environments [see](#desktop-environment) and also Window Manager [view](#window-manager).

This project is a fork of **[hxAri/Penguin](https://github.com/hxAri/Penguin)**, now maintained by **NNT**.

For problems with graphics rendering you need to know that Termux does not support it however, don't worry about that you can still achieve it with the help of VNC Viewer you can download it via Play Store for free.

## Notes
Maybe when you install a distro it will be fine until you successfully install it, but some distros may require some additional configuration to run well. But no need to worry about that, because you will still be able to use it.

## Features
The **[Penguin](https://github.com/sudo-Penguin-Lalala/Penguin)** features

### Binary Execution
Makes it easier for you to run your Linux Distro.

### Command Line Interface
The Command Line is very interesting and also easy to understand (this is just my opinion :D)

### Linux Distros
List of currently available or supported Linux Distros on **[Penguin](https://github.com/sudo-Penguin-Lalala/Penguin)**
* **Alpine**
* **Arch Linux**
* **Debian**
* **Fedora**
* **Kali Linux**
* **Kali Nethunter**
* **Manjaro**
* **Parrot Security OS**
* **Ubuntu**
* **Void**

### Desktop Environment
List of currently available or supported Desktop Environment on **[Penguin](https://github.com/sudo-Penguin-Lalala/Penguin)**
* LXDE
* LXQT
* MATE
* XFCE

### Window manager
List of currently available or supported Linux Window Manager **[Penguin](https://github.com/sudo-Penguin-Lalala/Penguin)**
* Awesome
* I3
* Openbox

## Dependency
Does **[Penguin](https://github.com/sudo-Penguin-Lalala/Penguin)** require additional dependencies? Yeah, but not much. All the required dependencies are all in a file called **dependencies**, you can read them with your favorite `cat` in the Terminal Emulator.

## Environment
If **[Penguin](https://github.com/sudo-Penguin-Lalala/Penguin)** uses the Shell as a programming language, does it require virtualization such as a Virtual Environment in the Python language? It can be yes or no, the environment here is intended to be a different situation because **[Penguin](https://github.com/sudo-Penguin-Lalala/Penguin)** is typed on a Laptop/PC so the **development** environment means that you will never install it, just create a system file folder like `{distro}-fs`

Meanwhile, the **production** environment is where you actually run it on your Termux and, you will actually install it. If you want to change the **[Penguin](https://github.com/sudo-Penguin-Lalala/Penguin)** environment you just need to change the contents of the **environment** file to the environment you want (**production** is set to default)

#### Warning
If you set it to development and run it in Termux it will probably cause permission errors

## Installation
How to install **[Penguin](https://github.com/sudo-Penguin-Lalala/Penguin)**? Just clone or download the source code from this repository.
```sh
git clone https://github.com/sudo-Penguin-Lalala/Penguin
```
Let's change give the penguin executable permission
```sh
chmod +x Penguin/penguin
```
Now you can run the **[Penguin](https://github.com/sudo-Penguin-Lalala/Penguin)** like this
```sh
bash Penguin/penguin
```
Or like this
```sh
. Penguin/penguin
```
Or this
```sh
Penguin/penguin
```
Next, please choose the distro you want to install yourself, and follow the instructions given, Have Nice Live!

## Usagement
When the Linux distro you installed has been successfully installed you can easily run it with just one line of code, see below for an example of running it in the Termux command line:
```sh
# (distro) (mode<cli|desktop<lxde|lxqt|mate|xfce>|window<awesome|openbox|i3>>)
```
Ubuntu distro cli mode:
```sh
ubuntu 22.04 cli
```
Ubuntu distro desktop environment mode:
```sh
ubuntu 22.04 desktop xfce
```
Ubuntu distro window manager mode:
```sh
ubuntu 22.04 window awesome
```

## Sources
To source the Root File System for the **[Penguin](https://github.com/sudo-Penguin-Lalala/Penguin)** Linux Distro, it uses sources from various GitHub repositories, including:
* **[Andronix](https://github.com/AndronixApp/AndronixOrigin)**

## Support
Give spirit to the developer, no matter how many donations given will still be accepted

## Licence
All **[Penguin](https://github.com/sudo-Penguin-Lalala/Penguin)** source code is licensed under the GNU General Public License v3. Please [see](https://www.gnu.org/licenses) the original document for more details.
## Credit: hxAri
