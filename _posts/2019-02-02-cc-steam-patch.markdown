---
title: "CHAOS;CHILD Improvement Patch"
layout: post
permalink: "/projects/chaoschild-steam.html"
active_tab: projects
date: 2019-02-02 00:00:00 +0100
excerpt: <p>No, this isn't a delusion. Our CHAOS;CHILD Improvement Patch, full of fixes and improvements, is out now!</p>
---

Oh hey, we released something on time for once.

This patch brings the fixes and improvements from our previous patch to the Steam version and adds a few more. See [below](#features) for a full list of features.

**UPDATE:** See that "few" above? Miiight be a bit of an understatement.

Much like what we talked about for our STEINS;GATE Steam Patch version 2.0, we gained experience over the years, our team got bigger, and our ambitions higher. So here it is, finally—the major update to our CHAOS;CHILD Improvement Patch. With all the places our CHAOS;HEAD NOAH translation has gone, we were bound to revise CHAOS;CHILD at some point; the two games are very tightly connected, after all. As our work on NOAH progressed, we found more and more parallels, more evident thematic progression, and just... more in general. It wouldn’t be an exaggeration to say this patch has an amount of work and thought put into it comparable to our ROBOTICS;NOTES ELITE Steam Patch, but with far less crunch this time, we promise.

So, without further ado, we welcome you back to Chaos World.

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

##### Version 2.1.0 _(Sep 14, 2024)_

- Minor text and consistency fixes.
- GOG compatibility.
- Custom Steam assets added.

##### Version 2.0.1 _(Sep 29, 2022)_

- Minor text and consistency fixes.
- The title menu's logo is now properly translated.

##### Version 2.0 _(Apr 29, 2022)_

- A full proofreading pass of the game has been completed, fixing large amounts of incorrect terminology, inaccuracies, inconsistencies, as well as improving general readability. Some moderate translation checking was done as well.
- The TIPS have received a full translation check and editing pass.
- Terminology has been made consistent with our CHAOS;HEAD NOAH translation and all our other patches.
- Restored Japanese honorifics.

##### Version 1.12 _(May 21, 2019)_

- Fixed compatibility with May 20, 2019 Steam update.
- Adjusted edited keyboard help for Steam version.
- Fixed launcher issue with moving save files from a system with a controller installed to a system without one (**"There is an error importing setup files"**).
- Controller input can now be disabled to work around phantom inputs.
- Replaced update checker technology as the old one was causing launcher crashes for a small number of users.
- Fixed launcher not starting with **"Entry Point Not Found"** error for a small number of users.
- Fixed replaced videos failing to play for some Linux users.
- More typo fixes etc.

##### Version 1.11 _(Feb 03, 2019)_

- Fixed an issue where the installer would crash on pre-AVX CPUs.

##### Version 1.1 _(Feb 02, 2019)_

Initial release for Steam version.

- **Steam compatibility.**
  - Lots of internal updates.
  - Removed memory fragmentation workaround as the Steam version now has its own.
  - Steam Play (Linux) support.
- Some new translation fixes.
- Includes new prompt explaining the delusion trigger controls.
  - Because Z and C are certainly not the most obvious choice.
- Fixed patch installer not working on certain Windows installations lacking multimedia components.
- Fixed game engine bug involving _My Documents_ paths containing special characters on _OneDrive_.
  - We haven't checked if the Steam version still has this issue, but both _STEINS;GATE 0_ and the Japanese version of _CHAOS;CHILD_ did.
- Worked around game engine bug where, when pausing right before a voiced line, line would fail to play and game would crash on the next voiced line.
- Fixed the goddamn title music.
  - In 1.0, our HQ audio option had a bug preventing the title screen BGM from playing if the intro video isn't skipped. Sorry about that.
- Installer now ships as a ZIP archive instead of a self-extracting executable.

##### Version 1.0 _(Jun 30, 2018)_

Initial release for Japanese PC version.

# <a name="features"></a>Features

Many of these can be turned on and off individually.

##### Game bug fixes

The original game release has several technical issues, such as broken lipsync and crashes when pausing right before voiced lines. We've fixed all we could track down.

##### Script fixes

Corrects major mistranslations, continuity errors, and other translation flaws.

These range from simple punctuation mistakes, to huge errors that could impact one’s understanding of the game. Examples could include inaccurate descriptions, improper names, inconsistent terminology, etc.

The CHAOS;CHILD localization suffers from a peculiar translation issue. The way the game was written in Japanese takes a lot of inspiration from other mystery novels—especially with the prose. Unfortunately, in quite a lot of instances, descriptions and internal thoughts lacked a lot of the punch they should've had, or even worse, were cut out entirely in the localization. This could have been for any number of reasons, be it time crunch, lack of awareness, or perhaps not having the opportunity to read the other games in the series. Regardless, we've made it a point to restore these passages to match the original Japanese text.

As part of our pass, we revised some pretty large things that we wouldn't normally change, the biggest of which old fans of the series will pick up on pretty quick. We hope you enjoy discovering them as much as we enjoyed coming up with them.

##### Restored Japanese honorifics

Much like we did for the STEINS;GATE 0 Steam Patch version 2.0, we fully reimplemented honorifics. The official localizations of all other games use Japanese honorifics, and so does our CHAOS;HEAD NOAH translation, so it's only natural that CHAOS;CHILD receives the same treatment.

##### Consistency fixes

There were a number of terms in CHAOS;CHILD—such as the names of people, objects, events, and products—which were translated differently in previous localizations and official media. In most instances, consistency issues were most likely caused by a lack of a CHAOS;HEAD NOAH localization, as well as other untranslated games. Fortunately, because of our familiarity and work with this series, we’ve been able to create a proper CHAOS; terminology list, and the CHAOS;CHILD Improvement Patch version 2.0 will be your first look at it.

In short, on top of making CHAOS;CHILD consistent with every other patched game, it has also been made consistent with our CHAOS;HEAD NOAH translation. This’ll allow each and every one of our readers to have the best experience possible—one that maintains everything that connects these wonderful games together.

##### Typography improvements

Text box and backlog text is displayed in a nicer font, and issues such as text hanging off the edge of the text box have been fixed.

##### Subtitles

Adds text to various voice-only lines and cutscenes, including several important lines which previously had no translation. Additionally, there are optional karaoke subs added to openings and endings.

##### Translated CGs

Includes translated versions of most CGs with text. The original title had some untranslated CGs (including an untranslated map that made it impossible to finish the game without a guide), as well as parts of some CGs which were even machine-translated, and we translated and re-edited these images from scratch in 1080p (as opposed to upscaling from 540p Vita CGs or keeping the Steam versions). Over 200 images were modified in some way.

##### High-quality FMV audio

Many video files in the game (openings, endings, and several cutscenes) have very low-quality audio due to poor compression. This patch replaces low-quality tracks with higher-quality versions.

##### UI improvements

Much of the system/menu text has been re-translated for comprehensibility. Backlog highlights have been adjusted to suit multi-line text.

# <a name="guides"></a>Guides

- [100% Spoiler-free Walkthrough]({{ "/projects/cc-walkthrough.html" | relative_url }})
- [Installing on Linux and Steam Deck]({{ "/projects/coz-linux-deck.html" | relative_url }})

# Installation instructions

1. **[↓ Download the installer](https://github.com/CommitteeOfZero/cc-patch/releases).** You want `CCPatch-v<version>-Setup.zip`, not the source code.
2. Extract the archive somewhere on your hard drive, not in your game directory.
3. Go to the newly created `CCPatch-v<version>-Setup` folder and run `CCPatch-Installer.exe`. **Warning:** Has sound.

- If the installer quits with an error about `MSVCP140_1.dll`, install [Visual C++ Redistributable](https://aka.ms/vs/16/release/vc_redist.x86.exe) (32-bit version, vc_redist.x86.exe - regardless of your system) and try again.

4. After you click _Finish_ and the installer closes, you can delete the `CCPatch-v<version>-Setup` folder.

# Troubleshooting

If you're having a problem not covered here, please [ask us on Discord](https://discord.gg/rq4GGCh) about it.

**Note:** The game requires the latest **DirectX 9.0c redistributable** (having a higher version of DirectX installed is not sufficient). If the game fails to run for you, [install DirectX 9](https://www.microsoft.com/en-us/download/details.aspx?id=35). (Steam should take care of this for you, but we're leaving it here just in case.)

### Game/launcher fails to start from Steam

You can try starting the launcher from the desktop/start menu shortcut (if you created one during the installation) or by directly running `LauncherC0.exe` from the game directory (right click _CHAOS;CHILD_ in your Steam library, _Properties_ → _Local Files_ → _Browse Local Files..._). Make sure you're logged into Steam, though.

### Phantom inputs make the game impossible to control (menu selections automatically go up)

On some systems, the game detects false controller inputs (mostly on Linux, but we've heard this from Windows users as well).

In the launcher, click _More Settings_ if you haven't already, go to the _Controller_ tab, select a different controller if you get multiple options, or just disable controller input altogether by unchecking _Enable_.

### Game shows an error about `mgs::Audio::CPlayer::InitializeXaudio()`

![XAudio2 error]({{ "/uploads/error_xaudio.png" | absolute_url }})

Install [DirectX 9.0c](https://www.microsoft.com/en-us/download/details.aspx?id=35) and try again.

### Installer shows an error about `MSVCP140.dll`

![MSVCP140.dll error]({{ "/uploads/error_vcruntime.png" | absolute_url }})

Install [Visual C++ Redistributable](https://aka.ms/vs/16/release/vc_redist.x86.exe) (32-bit version, vc_redist.x86.exe - regardless of your system) and try again.

### Installer shows an error about `api-ms-win-crt-runtime-l1-1-0.dll`

![UCRT error]({{ "/uploads/error_ucrt.png" | absolute_url }})

Update Windows. You may need to install the Visual C++ 2015 Redistributable Update 3 again afterwards (file above) - use "Repair" when prompted.

# Credits

- **Translation**: Rain, ItsRigs, MrComputerRevo, Ice, Enorovan, ChrisGLink
- **Editing**: Kumin, Discontinuous Qualia, Spider
- **Image editing**: Cypert, dusk, rimi, MrComputerRevo, Kumin, Raykable, Zips, Enorovan, Rile_Zugo
- **Hacking**: SomeAnon, daxxy, MrComputerRevo, JoseJL, Enorovan
- **Subtitles**: zahj
- **QC**: Spider
- **Chief Masochism Officer**: MrComputerRevo, Enorovan (abdication)
- **Masochism Deputies**: Raniel, Gel Banana

Special thanks to our vetted laboratory assistants for playtesting and proofreading!

This project includes a number of third-party components. See [this page]({{ "/projects/cc-thirdparty.html" | relative_url }}) for attribution.

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
- [STEINS;GATE: Linear Bounded Phenogram Improvement Patch]({{ "/projects/sglbp-patch.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
- [STEINS;GATE 0 Steam Patch]({{ "/projects/sg0-steam.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
- [ROBOTICS;NOTES DaSH Steam Patch]({{ "/projects/rnd-steam.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
- [ANONYMOUS;CODE Improvement Patch]({{ "/projects/ac-patch.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
