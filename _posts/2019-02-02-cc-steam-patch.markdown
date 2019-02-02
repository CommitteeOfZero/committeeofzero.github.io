---
title: "CHAOS;CHILD Steam patch"
layout: post
permalink: "/projects/chaoschild-steam.html"
active_tab: projects
date: 2019-02-02 00:00:00 +0100
---

Oh hey, we released something on time for once.

This patch brings the fixes and improvements from our previous patch to the Steam version and adds a few more. See [below](#features) for a full list of features.

<div style="border: 1px solid #fff; padding: 8px;">
Download link and instructions are <a href="#guides">↓ below</a>.
</div>

If you want a spoiler-free guide on how to obtain every ending, you can find one [here]({{ "/projects/cc-walkthrough.html" | relative_url }}).

[Join us on Discord](https://discord.gg/rq4GGCh) for fun, ~~shitposting~~ and support.

# Screenshots

{% include thumb.html fullsize="/uploads/cc_typography.png" thumb="/uploads/cc_typography_thumb.png" caption="Typography" %}
{% include thumb.html fullsize="/uploads/cc_consistency.png" thumb="/uploads/cc_consistency_thumb.png" caption="Consistency" %}
{% include thumb.html fullsize="/uploads/cc_subtitles.png" thumb="/uploads/cc_subtitles_thumb.png" caption="Subtitles" %}
{% include thumb.html fullsize="/uploads/cc_extracgs.png" thumb="/uploads/cc_extracgs_thumb.png" caption="Translated CGs" %}

# Changelog

##### Version 1.1 *(Feb 02, 2019)*

Initial release for Steam version.

* **Steam compatibility.**
  * Lots of internal updates.
  * Removed memory fragmentation workaround as the Steam version now has its own.
  * Steam Play (Linux) support.
* Some new translation fixes.
* Includes new prompt explaining the delusion trigger controls.
  * Because Z and C are certainly not the most obvious choice.
* Fixed patch installer not working on certain Windows installations lacking multimedia components.
* Fixed game engine bug involving *My Documents* paths containing special characters on *OneDrive*. 
  * We haven't checked if the Steam version still has this issue, but both *STEINS;GATE 0* and the Japanese version of *CHAOS;CHILD* did.
* Worked around game engine bug where, when pausing right before a voiced line, line would fail to play and game would crash on the next voiced line.
* Fixed the goddamn title music.
  * In 1.0, our HQ audio option had a bug preventing the title screen BGM from playing if the intro video isn't skipped. Sorry about that.
* Installer now ships as a ZIP archive instead of a self-extracting executable.

##### Version 1.0 *(Jun 30, 2018)*

Initial release for Japanese PC version.

# <a name="features"></a>Features

Many of these can be turned on and off individually.

##### Game bug fixes

The original game release has several technical issues, such as broken lipsync and crashes when pausing right before voiced lines. We've fixed all we could track down.

##### Script fixes

From typos to mistranslations, we've fixed mistakes ranging from large to small—for a total of over 1,600 lines changed. Some of them were tiny enough that most people would probably skim past without realizing, while others were grossly obvious or confusing and were serious impediments to an immersive reading experience.

##### Consistency fixes

Like with STEINS;GATE 0, there were a number of terms in CHAOS;CHILD, such as names of people, objects, and products, which were translated differently in previous localizations and official media. This patch **optionally** replaces all inconsistent terminology with the translations used in previous titles (primarily STEINS;GATE’s localization), as well as swapping the name order to Japanese (e.g. "Takumi Nishijo" → "Nishijou Takumi").

##### Typography improvements

Text box and backlog text is displayed in a nicer font, and issues such as text hanging off the edge of the text box have been fixed.

##### Subtitles

Adds text to various voice-only lines and cutscenes, including several important lines which previously had no translation. Additionally, there are optional karaoke subs added to openings and endings.

##### Translated CGs

Includes translated versions of most CGs with text. The original title had some untranslated CGs (including an untranslated map that made it impossible to finish the game without a guide), as well as parts of some CGs which were even machine-translated, and we translated and re-edited these images from scratch in 1080p (as opposed to upscaling from 540p Vita CGs or keeping the Steam versions). Over 200 images were modified in some way.

##### High quality FMV audio

Many video files in the game (openings, endings, and several cutscenes) have very low-quality audio due to poor compression. This patch replaces low-quality tracks with higher-quality versions.

##### UI improvements

Much of the system/menu text has been re-translated for comprehensibility. Backlog highlights have been adjusted to suit multi-line text.

# <a name="guides"></a>Guides

* [100% Spoiler-free Walkthrough]({{ "/projects/cc-walkthrough.html" | relative_url }})
* [Installing on Linux]({{ "/projects/cc-linux.html" | relative_url }})

# Installation instructions

1. **[↓ Download the installer](https://github.com/CommitteeOfZero/cc-patch/releases).** You want `CCPatch-v<version>-Setup.zip`, not the source code.
2. Extract the archive somewhere on your hard drive, not in your game directory.
3. Go to the newly created `CCPatch-v<version>-Setup` folder and run `CCPatch-Installer.exe`. **Warning:** Has sound.
  * If the installer quits with an error about `MSVCP140.dll`, install [Visual C++ 2015 Redistributable Update 3](https://www.microsoft.com/en-us/download/details.aspx?id=53587) (32-bit version, `vc_redist.x86.exe` - regardless of your system) and try again.
4. After you click *Finish* and the installer closes, you can delete the `CCPatch-v<version>-Setup` folder.

# Troubleshooting

If you're having a problem not covered here, please [ask us on Discord](https://discord.gg/rq4GGCh) about it.

**Note:** The game requires the latest **DirectX 9.0c redistributable** (having a higher version of DirectX installed is not sufficient). If the game fails to run for you, [install DirectX 9](https://www.microsoft.com/en-us/download/details.aspx?id=35). (Steam should take care of this for you, but we're leaving it here just in case.)

### Game/launcher fails to start from Steam

You can try starting the launcher from the desktop/start menu shortcut (if you created one during the installation) or by directly running `LauncherC0.exe` from the game directory (right click *CHAOS;CHILD* in your Steam library, *Properties* → *Local Files* → *Browse Local Files...*). Make sure you're logged into Steam, though.

### Game shows an error about `mgs::Audio::CPlayer::InitializeXaudio()`

![XAudio2 error]({{ "/uploads/error_xaudio.png" | absolute_url }})

Install [DirectX 9.0c](https://www.microsoft.com/en-us/download/details.aspx?id=35) and try again.

### Installer shows an error about `MSVCP140.dll`

![MSVCP140.dll error]({{ "/uploads/error_vcruntime.png" | absolute_url }})

Install [Visual C++ 2015 Redistributable Update 3](https://www.microsoft.com/en-us/download/details.aspx?id=53587) (32-bit version, `vc_redist.x86.exe` - regardless of your system) and try again.

### Installer shows an error about `api-ms-win-crt-runtime-l1-1-0.dll`

![UCRT error]({{ "/uploads/error_ucrt.png" | absolute_url }})

Update Windows. You may need to install the Visual C++ 2015 Redistributable Update 3 again afterwards (file above) - use "Repair" when prompted.

# Credits

* **Image editing**: Cypert, dusk, rimi, MrComputerRevo, Kumin, Raykable, Zips
* **Hacking**: SomeAnon, daxxy, MrComputerRevo, JoseJL
* **Editing**: Kumin, Discontinuous Qualia
* **Translation**: Rain, ItsRigs, MrComputerRevo, Ice
* **Subtitles**: zahj
* **Chief Masochism Officer**: MrComputerRevo
* **Masochism Deputies**: Raniel, Gel Banana

Special thanks to our vetted laboratory assistants for playtesting and proofreading!

This project includes a number of third-party components. See [this page]({{ "/projects/cc-thirdparty.html" | relative_url }}) for attribution.
