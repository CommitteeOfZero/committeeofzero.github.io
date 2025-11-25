---
title: "STEINS;GATE: Variant Space Octet Translation Patch"
layout: post
permalink: "/projects/sgvso-patch.html"
active_tab: projects
date: 2025-07-28 00:00:00 +0000
excerpt: <p>Experience this STEINS;GATE afterstory in 8-bit!</p>
---

Experience this STEINS;GATE afterstory in 8-bit!

Unexpected as it is, we patched this very niche entry, as it contains a lot of interesting setup for the series's overarching science, as well as a few references to the CHAOS;HEAD entries. We also tried to make it less annoying to set up.

Enjoy this short sequel in a known yet different world…

<div style="border: 1px solid #fff; padding: 8px;">
Download link and instructions are <a href="#installation">↓ below</a>.
</div>
 
[Join us on Discord](https://discord.gg/rq4GGCh) for fun, ~~shitposting~~ and support.

# Screenshots

{% include thumb.html fullsize="/uploads/sgvso_translation_pov.png" thumb="/uploads/sgvso_translation_pov_thumb.png" caption="Translation POV" %}
{% include thumb.html fullsize="/uploads/sgvso_extracgs.png" thumb="/uploads/sgvso_extracgs_thumb.png" caption="Translated CGs" %}

# Features

##### Script fixes

A full translation check of the game has been completed, fixing mistranslations, grammatical issues, minor typos, and wording issues, as well as an extensive number of inconsistencies with text formatting.

##### Translated CGs

Translated a number of CGs relevant to gameplay.

##### Point-of-view selection

You can choose to play in first person, like the game was written in, or in second person, the more traditional way for the genre in the West. Use the in-game configuration to select the mode.

##### Engine update

By upgrading the game from krkr2 to krkrz, we made it so that you don’t need to change your locale anymore. You can now enjoy the game with less headache. Also, we provided more resolution settings, available in the in-game configuration.

# <a name="installation"></a>Installation instructions

1. **[↓ Download the installer](https://github.com/CommitteeOfZero/sgvso-patch/releases).** You want `SGVSOPatch-v<version>-Setup.zip`, not the source code.
2. Extract the archive somewhere on your hard drive, not in your game directory.
3. Go to the newly created `SGVSOPatch-v<version>-Setup` folder and run `SGVSOPatch-Installer.exe`. **Warning:** Has sound.

- If the installer quits with an error about `MSVCP140_1.dll`, install [Visual C++ Redistributable](https://aka.ms/vs/16/release/vc_redist.x86.exe) (32-bit version, vc_redist.x86.exe - regardless of your system) and try again.

4. After you click _Finish_ and the installer closes, you can delete the `SGVSOPatch-v<version>-Setup` folder.
5. As there is no way for the installer to automatically obtain your install path, you will need to add the root of your game yourself.

# Troubleshooting

If you're having a problem not covered here, please [ask us on Discord](https://discord.gg/rq4GGCh) about it.

### Launcher fails to start

You can try starting the launcher from the desktop/start menu shortcut (if you created one during the installation) or by directly running `LauncherC0.exe` from the game directory.

### Installer shows an error about `MSVCP140_1.dll`

![MSVCP140.dll error]({{ "/uploads/error_vcruntime_sg0_steam.png" | absolute_url }})

Install [Visual C++ Redistributable](https://aka.ms/vs/16/release/vc_redist.x86.exe) (32-bit version, vc_redist.x86.exe - regardless of your system) and try again.

### Installer shows an error about `api-ms-win-crt-runtime-l1-1-0.dll`

![UCRT error]({{ "/uploads/error_ucrt.png" | absolute_url }})

Update Windows. You may need to install the Visual C++ Redistributable again afterwards (file above) - use “Repair” when prompted.

# Credits

- **Image editing**: TehVict
- **Hacking**: Dextinfire, PringlesGang, BoilingTeapot, ItsRigs, Enorovan
- **Translation Check**: ItsRigs, Enorovan
- **Additional Assets**: Kumin

Special thanks to Blick Winkel for the original translation and giving us authorization to use it as a basis for our work!

This project includes a number of third-party components. See [this page]({{ "/projects/sgvso-thirdparty.html" | relative_url }}) for attribution.

---

# See our other patches

- [CHAOS;HEAD NOAH Overhaul Patch]({{ "/projects/chn-patch.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-gog.svg" | relative_url }}">
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-switch.svg" | relative_url }}">
- [STEINS;GATE Steam Patch]({{ "/projects/sghd.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
- [STEINS;GATE ELITE Improvement Patch]({{ "/projects/sge-patch.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
- [STEINS;GATE: My Darling's Embrace Improvement Patch]({{ "/projects/sgmde-patch.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
- [ROBOTICS;NOTES ELITE Steam Patch]({{ "/projects/rne-steam.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
- [STEINS;GATE: Linear Bounded Phenogram Improvement Patch]({{ "/projects/sglbp-patch.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
- [CHAOS;CHILD Improvement Patch]({{ "/projects/chaoschild-steam.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-gog.svg" | relative_url }}">
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-switch.svg" | relative_url }}">
- [STEINS;GATE 0 Steam Patch]({{ "/projects/sg0-steam.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
- [ROBOTICS;NOTES DaSH Steam Patch]({{ "/projects/rnd-steam.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
- [ANONYMOUS;CODE Improvement Patch]({{ "/projects/ac-patch.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
