---
title: "CHAOS;CHILD: Extracting English Vita version scripts"
layout: page
permalink: "/projects/cc-extracting-english-vita-version-scripts.html"
active_tab: projects
date: 2018-06-30 22:30:00 +0100
excerpt: <p>Guide for extracting the scripts from an English copy of CHAOS;CHILD for Vita using a firmware 3.60 Vita (or PlayStation TV)</p>
---

[← Back to project page]({{ "/projects/chaoschild.html" | relative_url }})

This tutorial also applies to the PlayStation TV, but we will use "Vita" from now on for brevity. You may be able to skip some of these steps if you already have homebrew set up on your device.

##### Required software

- [FileZilla FTP client](https://filezilla-project.org/download.php?show_all=1)
- [VitaShell](https://github.com/TheOfficialFloW/VitaShell/releases)

We have also uploaded [a video tutorial](https://www.youtube.com/watch?v=SKNn0gxeUCI) to complement this guide.

##### Instructions

1. Confirm your Vita’s System Software version is **3.60** by opening the Settings app and navigating to System, then System Information. If your version is *below* 3.60, you must update to 3.60 using [this procedure](http://wololo.net/2016/08/09/manually-update-ps-vita-firmware-3-60/). If your version is *above* 3.60, please check back after July 1st for an updated tutorial using the new h-encore homebrew enabler. For instructions on using HENkaku on System Software version 3.60, follow the steps below.
2. Make sure your Vita can connect to the Internet and is on the same local network as your PC.
3. Open your web browser and open `go.henkaku.xyz`.
4. Run *molecularShell* and press the *Start* button.
5. Set "Enable unsafe homebrew" to On and confirm with *Cross*.
6. Fully close *molecularShell* (tear away the page), reopen it and press *Select*.
7. **On your computer,** download, install and run the *FileZilla FTP client*.
8. Type in the address you see displayed on your Vita (like `ftp://192.168.1.249:1337`) into the *Host:* field and hit *Quickconnect*.
9. Copy the *VitaShell* .vpk to `ux0:/data`.
10. **On your Vita,** in *molecularShell*, install *VitaShell*.
11. Plug in your *CHAOS;CHILD* game cartridge if you haven’t already.
  - You can also use a digital copy if you install it on your 3.60 Vita using a latest firmware Vita. *(Using a PS3 no longer works.)* See [this guide](https://github.com/xy2iii/vita-handbook/blob/9669610f1bf5f0d868f59fb8ab8ec80dcde1fffb/Vita%20Handbook.txt#L262) for details. Note that in case you rebooted during this process, you will have to run *HENkaku* again (connect to the Internet and open `go.henkaku.xyz` in your browser).
12. Open the *CHAOS;CHILD* LiveArea page and download the `v1.01` update by pressing the *Update* button.
13. Install the update normally and ignore the `C1-6703-6` error.
14. Run *VitaShell*.
15. Navigate to `gro0:/app` (or `ux0:/app` for the digital version).
16. Press the *Triangle* button on the `[GameID]` folder, where `[GameID]` is `PCSE01022` for American copies of *CHAOS;CHILD* and `PCSB01075` for European copies.
17. Scroll down to the “More” menu entry and select *Open decrypted* option.
18. Press *Select* to enable FTP access.
19. **On your computer,** in FileZilla, navigate to `ux0:/patch/[GameID]/USRDIR`.
20. Copy the `script` folder to your computer. You’ll have to type this folder’s path into the patch installer later.

[← Back to project page]({{ "/projects/chaoschild.html" | relative_url }})