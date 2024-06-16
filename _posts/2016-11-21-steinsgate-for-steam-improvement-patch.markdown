---
title: "STEINS;GATE Steam Patch"
layout: post
permalink: "/projects/sghd.html"
active_tab: projects
date: 2016-11-21 01:04:37 +0100
excerpt: <p>Greetings and salutations, lab mems and Gigalomaniacs.</p>
---

Greetings and salutations, lab mems and gigalomaniacs. We’re guessing since you’re here, you must have heard of the recent(ish) release of STEINS;GATE on Steam. We also assume you know it has several significant flaws which made playing it uncomfortable. We set out to fix those flaws, improve upon the release and make this the best version of STEINS;GATE out there.

**UPDATE:** That was nearly five years ago now. Can you believe it? Well, a promise is a promise, and we've finally gotten around to releasing this major update for the STEINS;GATE Steam patch! Throughout the years, we've gained more and more experience working with this series, so it was only natural that someday we'd return to the project that started it all! Even though STEINS;GATE still remains as a top-of-the-line localization, there's always a _few_ things to fix, aren't there? Now then, without further ado, let the 19790th development council commence!

<div style="border: 1px solid #fff; padding: 8px;">
Download link and instructions are <a href="#installation">↓ below</a>.
</div>
 
[Join us on Discord](https://discord.gg/rq4GGCh) for fun, ~~shitposting~~ and support.

# Screenshots

{% include thumb.html fullsize="/uploads/sghd_text_before.png" thumb="/uploads/sghd_text_before_thumb.png" caption="Typography - before" %}
{% include thumb.html fullsize="/uploads/sghd_text_after.png" thumb="/uploads/sghd_text_after_thumb.png" caption="Typography - after" %}
{% include thumb.html fullsize="/uploads/sghd_subtitles.png" thumb="/uploads/sghd_subtitles_thumb.png" caption="Subtitles" %}
{% include thumb.html fullsize="/uploads/sghd_cosplay.png" thumb="/uploads/sghd_cosplay_thumb.png" caption="Cosplay Patch" %}

# Changelog

##### Version 2.2.0 _(Jun 16, 2024)_

- Minor text and consistency fixes.
- A few more edited CGs added.
- DXVK common fix implemented.

##### Version 2.1 _(Oct 23, 2022)_

- The Cosplay Patch has been upscaled and implemented!
- A few more edited CGs added.
- Minor text and consistency fixes.

##### Version 2.0.1 _(Aug 27, 2021)_

- Minor text and consistency fixes.
- Fixed issues with word wrapping.
- Fixed an issue where some HQ videos were not properly replaced.

##### Version 2.0 _(Jul 28, 2021)_

- Lots of internal updates.
- Installer and launcher updated.
- Steam Play (Linux) support.
- .NET Framework is no longer required.
- A full proofreading pass of the game has been completed, fixing slight grammatical issues, minor typos and wording issues, as well as an extensive amount of inconsistencies with text formatting.
- A full translation check of the TIPS has been completed, fixing minor terminology issues, light inaccuracies, as well as improving general readability.
- A small handful of text and translation fixes.
- More edited CGs added.
- Improved song translations.

##### Version 1.1 _(Aug 29, 2020)_

- Fixed the text font to remove certain display errors.
- A few more edited CGs added.
- Some edited images have been redone with improved visuals or translations.
- More script edits to fix Engrish and various other major mistakes.

##### Version 1.03 _(Sep 11, 2017)_

- Compatibility update for 09/11/2017 game patch.

##### Version 1.02 _(Feb 8, 2017)_

- Fixed an issue where saving to file 38 would corrupt the outline texture, causing black boxes to be drawn above hyphens.

##### Version 1.01 _(Nov 21, 2016)_

- Fixed crash relating to HQ Audio functionality.

##### Version 1.0 _(Nov 21, 2016)_

Initial release.

# Features

Here's the full list of improvements. Each can be turned on and off individually, if you like.

##### Script fixes

A full proofreading pass of the game has been completed, fixing slight grammatical issues, minor typos and wording issues, as well as an extensive amount of inconsistencies with text formatting and a handful of translation fixes. Also includes display fixes in Suzuha's route.

##### Checked TIPS

A full translation check of the TIPS has been completed, fixing minor terminology issues and light inaccuracies, as well as improving general readability.

##### Cosplay Patch

Reimplements the Cosplay Patch from the non-HD Japanese PC versions of STEINS;GATE using proper upscaling. You'll be able to (re)experience the game with the entirety of the characters wearing costumes/cosplay! Don't forget to thank Mayuri for this find!

If you're curious about who is cosplaying who, or just can't figure out how to get started, head over [here]({{ "/2022/10/23/steinsgate-cosplay-help.html" | relative_url }}).

##### Better typography

Adds word-wrapping to the phone and displays text in a nicer font.

##### High-quality CGs

Replaces low-quality (more heavily upscaled/compressed) translated images with edits of the high-quality Japanese originals.

##### High-quality FMV music

For openings and endings, plays high-quality BGM tracks instead of the included low-quality audio tracks.

##### Karaoke subtitles

Adds styled karaoke subtitles to openings and endings.

##### Forced texture filtering

Greatly improves visual quality during zoom-ins and at sub-1080p resolutions.

##### Black screen fix

Workaround for issue where game hangs at black screen when exiting while in fullscreen mode.

##### Higher-quality videos

Adds subtitles to some translated videos, allowing you to use the high-quality Japanese originals.

# <a name="guides"></a>Guides

- [Installing on Linux and Steam Deck]({{ "/projects/coz-linux-deck.html" | relative_url }})

# <a name="installation"></a>Installation instructions

This patch is for the English Steam version of STEINS;GATE. The JAST release, Steam version set to Japanese and pirated copies are not supported.

1. **[↓ Download the installer](https://github.com/CommitteeOfZero/sghd-patch/releases).** You want `SGPatch-v<version>-Setup.zip`, not the source code.
2. Extract the archive somewhere on your hard drive, not in your game directory.
3. Go to the newly created `SGPatch-v<version>-Setup` folder and run `SGPatch-Installer.exe`. **Warning:** Has sound.

- If the installer quits with an error about `MSVCP140_1.dll`, install [Visual C++ Redistributable](https://aka.ms/vs/16/release/vc_redist.x86.exe) (32-bit version, vc_redist.x86.exe - regardless of your system) and try again.

4. After you click _Finish_ and the installer closes, you can delete the `SGPatch-v<version>-Setup` folder.

# Troubleshooting

If you're having a problem not covered here, please [ask us on Discord](https://discord.gg/rq4GGCh) about it.

**Note:** The game requires the latest **DirectX 9.0c redistributable** (having a higher version of DirectX installed is not sufficient). If the game fails to run for you, [install DirectX 9](https://www.microsoft.com/en-us/download/details.aspx?id=35). (Steam should take care of this for you, but we're leaving it here just in case.)

### Game/launcher fails to start from Steam

You can try starting the launcher from the desktop/start menu shortcut (if you created one during the installation) or by directly running `LauncherC0.exe` from the game directory (right click _STEINS;GATE_ in your Steam library, _Properties_ → _Local Files_ → _Browse Local Files..._). Make sure you're logged into Steam, though.

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

- **Image editing**: Cypert, LkProd, Zips, Choccy, Spider
- **Hacking**: SomeAnon, daxxy, MrComputerRevo
- **Editing**: Kumin, ChrisGLink, Enorovan
- **Translation**: ChrisGLink
- **Subtitles**: zahj, SnowedEarth, Cypert
- **Video editing**: LkProd

Translated lyrics for 'Skyclad Observer', 'Farfalla of Fate' and 'A.R.' taken from the previous JAST USA release of STEINS;GATE.

Special thanks to grechnik for contributing to our open source repository!

This project includes a number of third-party components. See [this page](https://github.com/CommitteeOfZero/LanguageBarrier/blob/master/LanguageBarrier/THIRDPARTY) for attribution and licenses.
