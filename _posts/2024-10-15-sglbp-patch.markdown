---
title: "STEINS;GATE: Linear Bounded Phenogram Improvement Patch"
layout: post
permalink: "/projects/sglbp-patch.html"
active_tab: projects
date: 2024-10-15 00:00:01 +0100
excerpt: <p>After opening the Gate of Steiner and the Gate of Zero, the Gate of Phenogram is finally unlocked!</p>
---

After opening the Gate of Steiner and the Gate of Zero, the Gate of Phenogram is finally unlocked!

At last, we've come to the world line where all may experience this anthology in the manner it was intended.

As Phenogram runs on a very similar build to the original STEINS;GATE, many of the technical features this patch provides are shared with it. On the language side, meanwhile, we addressed a whole heaping helping of typos and grammatical issues, and we took special attention to ensure references, callbacks, and inter-series continuity were maintained.

Now, without further ado, a Tutturu and El Psy Kongroo to you♪

<div style="border: 1px solid #fff; padding: 8px;">
Download link and instructions are <a href="#installation">↓ below</a>.
</div>
 
[Join us on Discord](https://discord.gg/rq4GGCh) for fun, ~~shitposting~~ and support.

# Screenshots

{% include thumb.html fullsize="/uploads/sglbp_text_before.png" thumb="/uploads/sglbp_text_before_thumb.png" caption="Typography - before" %}
{% include thumb.html fullsize="/uploads/sglbp_text_after.png" thumb="/uploads/sglbp_text_after_thumb.png" caption="Typography - after" %}
{% include thumb.html fullsize="/uploads/sglbp_subtitles.png" thumb="/uploads/sglbp_subtitles_thumb.png" caption="Subtitles" %}
{% include thumb.html fullsize="/uploads/sglbp_extracgs.png" thumb="/uploads/sglbp_extracgs_thumb.png" caption="Translated CGs" %}

# Features

Here's the full list of improvements. Each can be turned on and off individually, if you like.

##### Script fixes

A full translation check of the game has been completed, fixing grammatical issues, minor typos and wording issues, as well as an extensive amount of inconsistencies with text formatting and a handful of translation fixes.

##### Better typography

Adds word-wrapping to the phone and displays text in a nicer font.

##### High-quality FMV music

For openings and endings, plays high-quality BGM tracks instead of the included low-quality audio tracks.

##### Karaoke subtitles

Adds styled karaoke subtitles to openings and endings.

# <a name="guides"></a>Guides

- [Installing on Linux and Steam Deck]({{ "/projects/coz-linux-deck.html" | relative_url }})

# <a name="installation"></a>Installation instructions

1. **[↓ Download the installer](https://github.com/CommitteeOfZero/sghd-patch/releases).** You want `SGLBPPatch-v<version>-Setup.zip`, not the source code.
2. Extract the archive somewhere on your hard drive, not in your game directory.
3. Go to the newly created `SGLBPPatch-v<version>-Setup` folder and run `SGLBPPatch-Installer.exe`. **Warning:** Has sound.

- If the installer quits with an error about `MSVCP140_1.dll`, install [Visual C++ Redistributable](https://aka.ms/vs/16/release/vc_redist.x86.exe) (32-bit version, vc_redist.x86.exe - regardless of your system) and try again.

4. After you click _Finish_ and the installer closes, you can delete the `SGLBPPatch-v<version>-Setup` folder.

# Troubleshooting

If you're having a problem not covered here, please [ask us on Discord](https://discord.gg/rq4GGCh) about it.

**Note:** The game requires the latest **DirectX 9.0c redistributable** (having a higher version of DirectX installed is not sufficient). If the game fails to run for you, [install DirectX 9](https://www.microsoft.com/en-us/download/details.aspx?id=35). (Steam should take care of this for you, but we're leaving it here just in case.)

### Game/launcher fails to start from Steam

You can try starting the launcher from the desktop/start menu shortcut (if you created one during the installation) or by directly running `LauncherC0.exe` from the game directory (right click _STEINS;GATE: Linear Bounded Phenogram_ in your Steam library, _Properties_ → _Local Files_ → _Browse Local Files..._). Make sure you're logged into Steam, though.

### Phantom inputs make the game impossible to control (menu selections automatically go up)

On some systems the game detects false controller inputs (mostly on Linux, but we've heard this from Windows users as well).

In the launcher, click _More Settings_ if you haven't already, go to the _Controller_ tab, select a different controller if you get multiple options or just disable controller input altogether by unchecking _Enable_.

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

- **Image editing**: Choccy, Bloody, Enorovan, Rile_Zugo, LkProd
- **Hacking**: JoseJL, Dextinfire, Enorovan, SomeAnon, daxxy, MrComputerRevo
- **QC**: Dextinfire, Llednar
- **Translation**: Enorovan, fl4t_is_justice
- **Subtitles**: zahj, Enorovan
- **Subtitles editing**: Kumin
- **Video editing**: Rile_Zugo

Special thanks to grechnik for contributing to our open source repository!

This project includes a number of third-party components. See [this page]({{ "/projects/sglbp-thirdparty.html" | relative_url }}) for attribution.

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
- [ROBOTICS;NOTES ELITE Steam Patch]({{ "/projects/rne-steam.html" | relative_url }})
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
