---
title: "STEINS;GATE 0 Steam Patch"
layout: post
permalink: "/projects/sg0-steam.html"
active_tab: projects
date: 2020-08-21 17:56:06 +0100
excerpt: <p>It’s about time, huh?</p>
---

It’s about time, huh?

We figure we owe you an explanation as to why this one took so long.
You might recall that last time we released a patch for STEINS;GATE 0, we tried sending it into the past in order to
release on time.

Well, this time, we tried sending the patch into the future! Unfortunately, we were all so caught up in whether or not
we *could* that we didn't consider if we *should*. 

Because as a result of this misguided strategy, we were unable to release the patch until it arrived in our inbox much,
much later.

Okay, okay, jokes aside, we’re very sorry at the time it took to deliver on this project. We hope that the enhanced
STEINS;GATE 0 experience will have been worth the wait!

This patch features a number of added changes and fixes to improve the English release of STEINS;GATE 0 on Steam,
including typo fixes, changes for consistency with the original STEINS;GATE, and even the option to restore Japanese
honorifics back into the game! See [below](#features) for a full list of features.

<div style="border: 1px solid #fff; padding: 8px;">
Download link and instructions are <a href="#guides">↓ below</a>.
</div>

If you want a spoiler-free guide on how to obtain every ending, you can find one [here]({{ "/projects/sg0-walkthrough.html" | relative_url }}).

[Join us on Discord](https://discord.gg/rq4GGCh) for fun, ~~shitposting~~ and support.

# Screenshots

{% include thumb.html fullsize="/uploads/sg0_steam_typography.png" thumb="/uploads/sg0_steam_typography_thumb.png" caption="Typography" %}
{% include thumb.html fullsize="/uploads/sg0_steam_consistency.png" thumb="/uploads/sg0_steam_consistency_thumb.png" caption="Consistency / Honorifics" %}
{% include thumb.html fullsize="/uploads/sg0_steam_videos.png" thumb="/uploads/sg0_steam_videos_thumb.png" caption="Translated Videos" %}
{% include thumb.html fullsize="/uploads/sg0_steam_extracgs.png" thumb="/uploads/sg0_steam_extracgs_thumb.png" caption="Translated CGs" %}


# Changelog

##### Version 2.1 *(Jul 28, 2021)*

* A full translation check and editing pass of the TIPS has been completed, fixing large amounts of incorrect terminology, inaccuracies, inconsistencies, as well as improving general readability.
* Text and translation fixes, with a heavy focus on maintaining consistency with the original STEINS;GATE. 

##### UPDATED *(Oct 24, 2020)*

* The problem with some anti-virus software detecting the patch as a false positive should be fixed (except McAfee, but if you use McAfee, we recommend you get a better antivirus.)
* If you downloaded the patch before this update, please download [SG0Patch-v2.02-Update.zip](https://github.com/CommitteeOfZero/zero-patch/releases/download/2.02/SG0Patch-v2.02-Update.zip) and extract it to your game installation folder.

##### Version 2.02 *(Oct 6, 2020)*

* Even more typo fixes.
* Improved the typesetting of certain CGs.
* _Fully_ fixed an issue where “Failed to allocate memory” errors sometimes occur.

##### Version 2.01 *(Aug 23, 2020)*

* Even more typo fixes.
* Improved the translations of certain CGs.
* Fixed an issue where "Failed to allocate memory" errors sometimes occur (please tell us if you're still experiencing this problem).

##### Version 2.0 *(Aug 21, 2020)*

Initial release for Steam version.

* **Steam compatibility.**
  * Lots of internal updates. (special thanks to grechnik for contributing!)
  * Steam Play (Linux) support.
* Option to include Japanese honorifics in text added.
* Even more translation and consistency fixes.
* More CGs edited.
* Improved song translations.
* Improved menu translations.
* Translated chapter title cards.
* Installer and launcher updated.
  * .NET Framework is no longer required.

##### Version 1.0 *(Feb 19, 2017)*

Initial release for Japanese PC version.

# <a name="features"></a>Features

Many of these can be turned on and off individually.

##### Script fixes

Corrects *over 3000* mistranslations, continuity errors and other translation flaws.
These range from simple punctuation mistakes to huge errors that could impact one’s understanding of the game, such as
a reference to the wrong character.

Additionally, certain terms are translated differently between the original STEINS;GATE localization and the
STEINS;GATE 0 localization, and we’ve corrected as many of those as we could as well. This includes changing the name
order to Japanese-style (e.g. “Kyoma Hououin” → “Hououin Kyouma”).

##### Retranslated TIPS

Every single TIP has been modified in some way. Some of them required minor edits for flow and style, others needed to be rewritten to account for stiff or confusing writing, and many of them needed to be partially or completely retranslated due to missing or incorrect information.

##### Restored Japanese honorifics

One of the more notable changes in the v2.0 patch. 

The localizations of the original STEINS;GATE, as well as Linear Bounded Phenogram, My Darling’s Embrace,
and even the upcoming ROBOTICS;NOTES ELITE and ROBOTICS;NOTES DaSH all use Japanese honorifics, so why shouldn’t STEINS;GATE 0?

Thanks to the help of the incredible Enorovan, who carefully combed through all the text in the game,
we’ve created an option to add Japanese honorifics back into the game, alongside a new glossary definition explaining them
(just like in the original STEINS;GATE localization)!

##### Typography improvements

Displays text and RINE messages in a nicer font with better text formatting.
This includes toggleable options such as improved outlines and different display styles for usernames on RINE.

##### Translated Videos

A number of videos have been translated or had their translations improved.
This included chapter title cards, which now feature added translations for the Japanese chapter titles. 
(This is not to be confused with the English titles: every chapter actually features two titles, one in English and one
in Japanese, and they’re often quite different.)

##### Subtitles

Improved translation on certain cutscenes.
Additionally, there are optional karaoke subtitles for openings and endings. Now with the option to select between
Japanese + English song subtitles, Japanese only, or English only.

##### Translated CGs

Contains new translated versions of most CGs and several backgrounds. Some CGs which were translated in the original
Steam version have been replaced with variations that are visually improved or better-translated. This includes many of
the stickers used on RINE.

##### High quality FMV audio

For openings, endings and some other videos, we’ve included the option to play high-quality audio instead of the
low-quality audio tracks normally included in the Steam version.

##### Hide auto/skip buttons

Includes an option to hide the auto/skip buttons even when using mouse control (keyboard / gamepad shortcuts for these will still work).

##### Save game compatibility

Can be installed over the Steam version of the game without breaking existing saves.

# <a name="guides"></a>Guides

* [100% Spoiler-free Walkthrough]({{ "/projects/sg0-walkthrough.html" | relative_url }})
* [Installing on Linux]({{ "/projects/sg0-linux.html" | relative_url }})

# Installation instructions

1. **[↓ Download the installer](https://github.com/CommitteeOfZero/zero-patch/releases).** You want `SG0Patch-v<version>-Setup.zip`, not the source code.
2. Extract the archive somewhere on your hard drive, not in your game directory.
3. Go to the newly created `SG0Patch-v<version>-Setup` folder and run `SG0Patch-Installer.exe`. **Warning:** Has sound.
  * If the installer quits with an error about `MSVCP140_1.dll`, install [Visual C++ Redistributable](https://aka.ms/vs/16/release/vc_redist.x86.exe) (32-bit version, vc_redist.x86.exe - regardless of your system) and try again.
4. After you click *Finish* and the installer closes, you can delete the `SG0Patch-v<version>-Setup` folder.

# Troubleshooting

If you're having a problem not covered here, please [ask us on Discord](https://discord.gg/rq4GGCh) about it.

**Note:** The game requires the latest **DirectX 9.0c redistributable** (having a higher version of DirectX installed is not sufficient). If the game fails to run for you, [install DirectX 9](https://www.microsoft.com/en-us/download/details.aspx?id=35). (Steam should take care of this for you, but we're leaving it here just in case.)

### Game/launcher fails to start from Steam

You can try starting the launcher from the desktop/start menu shortcut (if you created one during the installation) or by directly running `LauncherC0.exe` from the game directory (right click *STEINS;GATE 0* in your Steam library, *Properties* → *Local Files* → *Browse Local Files...*). Make sure you're logged into Steam, though.

### Phantom inputs make the game impossible to control (menu selections automatically go up)

On some systems the game detects false controller inputs (mostly on Linux, but we've heard this from Windows users as well).

In the launcher, click *More Settings* if you haven't already, go to the *Controller* tab, select a different controller if you get multiple options or just disable controller input altogether by unchecking *Enable*.

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

* **Image editing**: Cypert, Kumin
* **Hacking**: SomeAnon, daxxy, MrComputerRevo, grechnik
* **Editing**: Enorovan, Kumin, Discontinuous Qualia
* **Translation**: ChrisGLink, ItsRigs, Rain
* **Subtitles**: zahj, SnowedEarth
* **Video editing**: Enorovan, LkProd
* **Trailer**: Rain, Enorovan, Kumin, Ice

Special thanks to our vetted laboratory assistants for playtesting and proofreading!

This project includes a number of third-party components. See [this page]({{ "/projects/sg0-thirdparty.html" | relative_url }}) for attribution.
