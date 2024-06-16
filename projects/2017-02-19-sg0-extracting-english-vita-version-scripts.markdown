---
title: "STEINS;GATE 0: Extracting English Vita version scripts"
layout: page
permalink: "/projects/sg0-extracting-english-vita-version-scripts.html"
active_tab: projects
date: 2017-02-19 01:36:36 +0100
excerpt: <p>Guide for extracting the scripts from an English copy of STEINS;GATE 0 for Vita using a firmware 3.60 Vita (or PlayStation TV)</p>
---

[← Back to project page]({{ "/projects/sg0.html" | relative_url }})

This tutorial also applies to the PlayStation TV, but we will use "Vita" from now on for brevity. You may be able to skip some of these steps if you already have homebrew set up on your device.

##### Required software

- [FileZilla FTP client](https://filezilla-project.org/download.php?show_all=1)
- [VitaShell](https://github.com/TheOfficialFloW/VitaShell/releases)
- [MaiDumpTool](https://github.com/LioMajor/MaiDumpToolEN/releases)

We have also uploaded [a video tutorial](https://www.youtube.com/watch?v=8llmqBAt3PI) to complement this guide.

##### Instructions

1. Confirm your Vita's System Software version is **3.60** by opening the Settings app and navigating to System, then System Information. If your version is _below_ 3.60, you must update to 3.60 - and no further! - using [this procedure](http://wololo.net/2016/08/09/manually-update-ps-vita-firmware-3-60/). If your version is _above_ 3.60, there's unfortunately nothing you can do.
2. Make sure your Vita can connect to the Internet and is on the same local network as your PC.
3. Open your web browser and open `go.henkaku.xyz`.
4. Run _molecularShell_ and press the _Start_ button.
5. Set "Enable unsafe homebrew" to On and confirm with _Cross_.
6. Fully close _molecularShell_ (tear away the page), reopen it and press _Select_.
7. **On your computer,** download, install and run the _FileZilla FTP client_.
8. Type in the address you see displayed on your Vita (like `ftp://192.168.1.249:1337`) into the _Host:_ field and hit _Quickconnect_.
9. Copy the _MaiDumpTool_ and _VitaShell_ .vpk's to `ux0:/data`.
10. **On your Vita,** in _molecularShell_, install _VitaShell_ and launch it.
11. Using _VitaShell_, install _MaiDumpTool_.
12. Plug in your _STEINS;GATE 0_ game cartridge if you haven't already.

- You can also use a digital copy if you install it on your 3.60 Vita using either a PS3 or a latest firmware Vita. See [this guide](https://github.com/xy2iii/vita-handbook/blob/9669610f1bf5f0d868f59fb8ab8ec80dcde1fffb/Vita%20Handbook.txt#L262) for details. Note that in case you rebooted during this process, you will have to run _HENkaku_ again (connect to the Internet and open `go.henkaku.xyz` in your browser).

13. Run _MaiDumpTool_.
14. Select "Extract/Decrypt content", the \*STEINS;GATE 0 option, and "Extract gamedata only (without decrypting eboot, the game won't boot)".
15. Wait for _MaiDumpTool_ to do its thing.
16. Open _VitaShell_ and press _Select_.
17. **On your computer,** in FileZilla, navigate to `ux0:/mai/[SG0ID]/USRDIR`, where `[SG0ID]` is `PCSE00949` for American copies of _STEINS;GATE 0_ and `PCSB01012` for European copies.
18. Copy the `script` folder to your computer. You'll have to type this folder's path into the patch installer later.

[← Back to project page]({{ "/projects/sg0.html" | relative_url }})
