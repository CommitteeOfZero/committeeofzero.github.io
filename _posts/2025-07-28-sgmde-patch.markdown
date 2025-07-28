---
title: "STEINS;GATE: My Darling’s Embrace Improvement Patch"
layout: post
permalink: "/projects/sgmde-patch.html"
active_tab: projects
date: 2025-07-28 00:00:01 +0000
excerpt: <p>This is a lab mem story that could have been.</p>
---

This is a lab mem story that could have been.

Welcome to the Delta Attractor Field! Here you’ll get to enjoy some good time with the STEINS;GATE cast, and explore many possibilities.

Just like Phenogram, My Darling’s Embrace is a very similar game to the original STEINS;GATE, and so it also shares features with it. On the language side, it had a better base than Phenogram, but still needed a full on check, especially on terminology.

Now go ahead, and adjust the divergence to any value *you*’d like.

<div style="border: 1px solid #fff; padding: 8px;">
Download link and instructions are <a href="#installation">↓ below</a>.
</div>
 
[Join us on Discord](https://discord.gg/rq4GGCh) for fun, ~~shitposting~~ and support.

# Screenshots

{% include thumb.html fullsize="/uploads/sgmde_text_before.png" thumb="/uploads/sgmde_text_before_thumb.png" caption="Typography - before" %}
{% include thumb.html fullsize="/uploads/sgmde_text_after.png" thumb="/uploads/sgmde_text_after_thumb.png" caption="Typography - after" %}
{% include thumb.html fullsize="/uploads/sgmde_subtitles.png" thumb="/uploads/sgmde_subtitles_thumb.png" caption="Subtitles" %}
{% include thumb.html fullsize="/uploads/sgmde_extracgs.png" thumb="/uploads/sgmde_extracgs_thumb.png" caption="Translated CGs" %}

# Features

##### Script fixes

A full translation check of the game has been completed, fixing mistranslations, terminology, grammatical issues, typos, and wording issues.

##### Bug fixes

Fixed two bugs related to the phone, one where an interactive email's hitbox was going for too long, and another where the phone would pop in and pop out every few lines during a video call.

##### Translated CGs

Translated a number of CGs and BGs, as well as fixed some terminology and typesetting errors present in other images.

##### Better typography

Adds word wrapping to phone text and displays story text in a nicer font.

##### Karaoke subtitles

Adds styled karaoke subtitles to openings and endings.


# <a name="guides"></a>Guides

- [Installing on Linux and Steam Deck]({{ "/projects/coz-linux-deck.html" | relative_url }})

# <a name="installation"></a>Installation instructions

1. **[↓ Download the installer](https://github.com/CommitteeOfZero/sgmde-patch/releases).** You want `SGMDEPatch-v<version>-Setup.zip`, not the source code.
2. Extract the archive somewhere on your hard drive, not in your game directory.
3. Go to the newly created `SGMDEPatch-v<version>-Setup` folder and run `SGMDEPatch-Installer.exe`. **Warning:** Has sound.

- If the installer quits with an error about `MSVCP140_1.dll`, install [Visual C++ Redistributable](https://aka.ms/vs/16/release/vc_redist.x86.exe) (32-bit version, vc_redist.x86.exe - regardless of your system) and try again.

4. After you click _Finish_ and the installer closes, you can delete the `SGMDEPatch-v<version>-Setup` folder.

# Troubleshooting

If you're having a problem not covered here, please [ask us on Discord](https://discord.gg/rq4GGCh) about it.

**Note:** The game requires the latest **DirectX 9.0c redistributable** (having a higher version of DirectX installed is not sufficient). If the game fails to run for you, [install DirectX 9](https://www.microsoft.com/en-us/download/details.aspx?id=35). (Steam should take care of this for you, but we're leaving it here just in case.)

### Game/launcher fails to start from Steam

You can try starting the launcher from the desktop/start menu shortcut (if you created one during the installation) or by directly running `LauncherC0.exe` from the game directory (right click _STEINS;GATE: My Darling's Embrace_ in your Steam library, _Properties_ → _Local Files_ → _Browse Local Files..._). Make sure you're logged into Steam, though.

### Phantom inputs make the game impossible to control (menu selections automatically go up)

On some systems, the game detects false controller inputs (mostly on Linux, but we've heard this from Windows users as well).

In the launcher, click _More Settings_ if you haven't already, go to the _Controller_ tab, select a different controller if you get multiple options, or just disable controller input altogether by unchecking _Enable_.

### Game shows an error about `mgs::Audio::CPlayer::InitializeXaudio()`

![XAudio2 error]({{ "/uploads/error_xaudio.png" | absolute_url }})

Install [DirectX 9.0c](https://www.microsoft.com/en-us/download/details.aspx?id=35) and try again.

### Installer shows an error about `MSVCP140_1.dll`

![MSVCP140.dll error]({{ "/uploads/error_vcruntime_sg0_steam.png" | absolute_url }})

Install [Visual C++ Redistributable](https://aka.ms/vs/16/release/vc_redist.x86.exe) (32-bit version, vc_redist.x86.exe - regardless of your system) and try again.

### Installer shows an error about `api-ms-win-crt-runtime-l1-1-0.dll`

![UCRT error]({{ "/uploads/error_ucrt.png" | absolute_url }})

Update Windows. You may need to install the Visual C++ Redistributable again afterwards (file above) - use “Repair” when prompted.

# Credits

- **Image editing**: Enorovan, Bloody, Choccy
- **Hacking**: JoseJL, Enorovan, Dextinfire, PringlesGang, SomeAnon, daxxy, MrComputerRevo
- **QC**: PringlesGang, ItsRigs
- **Translation Check**: Enorovan, ItsRigs
- **Subtitles**: zahj
- **Video editing**: Enorovan
- **Additional Assets**: Kumin
- **Special Thanks**: fl4t_is_justice, Jake

Special thanks to grechnik for contributing to our open-source repository!

This project includes a number of third-party components. See [this page]({{ "/projects/sgmde-thirdparty.html" | relative_url }}) for attribution.

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
- [STEINS;GATE: Variant Space Octet Translation Patch]({{ "/projects/sgvso-patch.html" | relative_url }})
- [ROBOTICS;NOTES ELITE Steam Patch]({{ "/projects/rne-steam.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
- [STEINS;GATE: Linear Bounded Phenogram Improvement Patch]({{ "/projects/sglbp-patch.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
- [CHAOS;CHILD Improvement Patch]({{ "/projects/chaoschild-steam.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-gog.svg" | relative_url }}">
- [STEINS;GATE 0 Steam Patch]({{ "/projects/sg0-steam.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
- [ROBOTICS;NOTES DaSH Steam Patch]({{ "/projects/rnd-steam.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
- [ANONYMOUS;CODE Improvement Patch]({{ "/projects/ac-patch.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
