---
title: "CHAOS;CHILD PC English patch"
layout: post
permalink: "/projects/chaoschild.html"
active_tab: projects
date: 2018-06-30 22:30:00 +0100
---

As one game ends, another begins.

...Sorry, by the way, that this patch ended up taking so long. We'd make some cheeky excuse involving real booting or whatever, but this really isn't the time for that.

This patch inserts the official English translation of CHAOS;CHILD into the Japanese PC version while addressing various shortcomings and making a number of improvements to both the translation and the base game. See [below](#features) for a full list of features.

<div style="border: 1px solid #fff; padding: 8px;">
Download link and instructions are <a href="#guides">↓ below</a>.

<p>You are required to <b>own the PC version of the game as well as the decrypted, unmodified scripts of the English Vita version 1.01</b>. These can be extracted using a <b>Vita or PSTV on firmware 3.60</b> (a hack for firmwares 3.65 to 3.68 has been announced for the near future). Both the physical and digital English Vita versions can be used.</p>

Both the physical and digital English Vita versions can be used, but getting the digital version <i>onto</i> your 3.60 device currently requires a second, latest firmware Vita. <i>(Using a PS3 no longer works.)</i>
</div>

You can find guides for buying the Japanese PC version and extracting the necessary data from the English Vita version [below](#guides).

If you want a spoiler-free guide on how to obtain every ending, you can find one [here]({{ "/projects/cc-walkthrough.html" | relative_url }}).

[Join us on Discord](https://discord.gg/rq4GGCh) for fun, ~~shitposting~~ and support.

# Screenshots

{% include thumb.html fullsize="/uploads/cc_typography.png" thumb="/uploads/cc_typography_thumb.png" caption="Typography" %}
{% include thumb.html fullsize="/uploads/cc_consistency.png" thumb="/uploads/cc_consistency_thumb.png" caption="Consistency" %}
{% include thumb.html fullsize="/uploads/cc_subtitles.png" thumb="/uploads/cc_subtitles_thumb.png" caption="Subtitles" %}
{% include thumb.html fullsize="/uploads/cc_extracgs.png" thumb="/uploads/cc_extracgs_thumb.png" caption="Translated CGs" %}

# <a name="features"></a>Features

Many of these can be turned on and off individually.

##### Script fixes

From typos to mistranslations, we've fixed mistakes ranging from large to small—for a total of over 1,600 lines changed. Some of them were tiny enough that most people would probably skim past without realizing, while others were grossly obvious or confusing and were serious impediments to an immersive reading experience.

##### Consistency fixes

Like with STEINS;GATE 0, there were a number of terms in CHAOS;CHILD, such as names of people, objects, and products, which were translated differently in previous localizations and official media. This patch **optionally** replaces all inconsistent terminology with the translations used in previous titles (primarily STEINS;GATE’s localization), as well as swapping the name order to Japanese (e.g. "Takumi Nishijo" → "Nishijou Takumi").

##### Typography improvements

Text box and backlog text is displayed in a nicer font, and issues such as text hanging off the edge of the text box have been fixed.

##### Subtitles

Adds text to various voice-only lines and cutscenes, including several important lines which previously had no translation. Additionally, there are optional karaoke subs added to openings and endings.

##### Translated CGs

Includes translated versions of most CGs with text. The original title had some untranslated CGs (including an untranslated map that made it impossible to finish the game without a guide), as well as parts of some CGs which were even machine-translated, and we translated and re-edited these images from scratch in 1080p (as opposed to upscaling from 540p Vita CGs). Over 200 images were modified in some way.

##### High quality FMV audio

Many video files in the game (openings, endings, and several cutscenes) have very low-quality audio due to poor compression. This patch replaces low-quality tracks with higher-quality versions.

##### UI improvements

Much of the system/menu text has been re-translated for comprehensibility. Backlog highlights have been adjusted to suit multi-line text.

##### Stability

Like STEINS;GATE 0, the PC version of CHAOS;CHILD occasionally crashes for some players. We implemented a defense against this for STEINS;GATE 0, which unfortunately didn't work on some systems. With this patch, we've added an additional workaround that applies in those cases as well.

# <a name="guides"></a>Guides

* [How to buy the digital PC version]({{ "/projects/cc-buying-digital-pc-version.html" | relative_url }})
* [How to extract the English Vita version scripts]({{ "/projects/cc-extracting-english-vita-version-scripts.html" | relative_url }})
* [100% Spoiler-free Walkthrough]({{ "/projects/cc-walkthrough.html" | relative_url }})

# Installation instructions

1. **[↓ Download the installer](https://github.com/CommitteeOfZero/cc-patch/releases).**
2. Run the installer. **Warning:** Has sound.
  * If the installer quits with an error about `MSVCP140.dll`, install [Visual C++ 2015 Redistributable Update 3](https://www.microsoft.com/en-us/download/details.aspx?id=53587) (32-bit version, `vc_redist.x86.exe` - regardless of your system) and try again.
3. When asked, fill in the directory where you installed the PC version (containing a `USRDIR` directory and files such as `Game.exe`).
4. When asked, fill in your path to the unencrypted, unmodified `USRDIR\script` directory copied from update 1.01 for the English Vita version (containing files ending in `.scx`).

Mac and Linux installers coming soon™ (for real this time).

# Troubleshooting

If you're having a problem not covered here, please [ask us on Discord](https://discord.gg/rq4GGCh) about it.

**Note:** The game requires the latest **DirectX 9.0c redistributable** (having a higher version of DirectX installed is not sufficient). If the game fails to run for you, [install DirectX 9](https://www.microsoft.com/en-us/download/details.aspx?id=35).

### Game shows a Japanese/gibberish message box titled `Error`

!["Error" error (Japanese)]({{ "/uploads/error_config.jpg" | absolute_url }})
!["Error" error (Mojibake)]({{ "/uploads/error_config_mojibake.png" | absolute_url }})

This happens when the game cannot open its configuration / save data directory.

Make sure your locale is set to the appropriate locale for your Windows user name (in particular, *do not* run the game in Japanese locale).

If your *Documents* folder is on *OneDrive*, currently the only way to run the game is to move it out (using the appropriate Windows functionality, not simply dragging the folder).

This is a bug in the PC version of the engine we will address in an update soon.

### Game shows an `SdWrap` error

![SdWrap error]({{ "/uploads/error_sdwrap.png" | absolute_url }})

The *title* is important here - in Japanese locale, the message would display correctly, however that's not related to the issue at hand (and using Japanese locale is not required to run the game and can actually cause problems itself).

This happens when the patch installer fails to modify your game executable (most likely because something else on your system was reading `Game.exe` at the time or because you're using antivirus).

1. Browse to the game folder (the *Troubleshooting* tab under *More Settings* in the launcher has a button for this).
2. Close the launcher.
3. Close/disable antivirus or anything else that might be preventing `Game.exe` from being modified (rebooting may help).
4. Delete/move `Game.exe.bak` and `Game.exe.tmp` to prevent the installer from believing `Game.exe` has been successfully patched.
5. Reinstall the patch (you don't need to uninstall it first).

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

* **Image editing**: Cypert, dusk, rimi, MrComputerRevo, Kumin, Raykable
* **Hacking**: SomeAnon, daxxy, MrComputerRevo
* **Editing**: Kumin, Discontinuous Qualia
* **Translation**: Rain, ItsRigs, MrComputerRevo, Ice
* **Subtitles**: zahj
* **Chief Masochism Officer**: MrComputerRevo
* **Masochism Deputies**: Raniel, Gel Banana

Special thanks to our vetted laboratory assistants for playtesting and proofreading!

This project includes a number of third-party components. See [this page]({{ "/projects/cc-thirdparty.html" | relative_url }}) for attribution.
