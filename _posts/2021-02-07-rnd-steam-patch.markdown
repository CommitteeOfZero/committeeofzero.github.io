---
title: "ROBOTICS;NOTES DaSH Steam Patch"
layout: post
permalink: "/projects/rnd-steam.html"
active_tab: projects
date: 2021-02-07 22:00:00 +0100
excerpt: <p>It's time for robots, <i>again</i>.</p>
---

It’s time for robots, <i>again</i>.

Hacking our way through to deliver this patch to you all has been tough—we weren’t competing against just any Super Hacker, after all—but we finally made it. Embrace the winds coming from the northeast, for this really is a festival to attend!

This patch features a significant number of changes and fixes to improve the English release of ROBOTICS;NOTES DaSH on Steam, including typo fixes, changes for consistency with the rest of the Science Adventure Series, and even the implementation of mouse support into the game! See [below](#features) for a full list of features.

<div style="border: 1px solid #fff; padding: 8px;">
Download link and instructions are <a href="#guides">↓ below</a>.
</div>

If you want a spoiler-free guide on how to obtain every ending, you can find one [here]({{ "/projects/rnd-walkthrough.html" | relative_url }}).

[Join us on Discord](https://discord.gg/rq4GGCh) for fun, ~~shitposting~~ and support.

# Screenshots

{% include thumb.html fullsize="/uploads/rnd_consistency_typography.png" thumb="/uploads/rnd_consistency_typography_thumb.png" caption="Consistency / Typography" %}
{% include thumb.html fullsize="/uploads/rnd_tips.png" thumb="/uploads/rnd_tips_thumb.png" caption="Retranslated TIPs" %}
{% include thumb.html fullsize="/uploads/rnd_videos_cgs.png" thumb="/uploads/rnd_videos_cgs_thumb.png" caption="Translated Videos/CGs" %}
{% include thumb.html fullsize="https://www.youtube.com/watch?v=yCyV22P1IMA" fullsize_ext=true thumb="/uploads/rnd_mouse_thumb.png" caption="Mouse Support" %}

# Changelog

##### Version 1.1.0 _(Jun 16, 2024)_

- More translation, consistency, and typo fixes.
- DXVK common fix implemented.

##### Version 1.0.4 _(Sep 7, 2022)_

- Translation, consistency, and typo fixes.
- A consistent crash on Twipo has been fixed.

##### Version 1.0.3 _(Apr 1, 2022)_

- The translation check/proofreading pass of the game has advanced, fixing incorrect terminology, inaccuracies, and inconsistencies.
- The Swimsuit Patch bonus feature has been implemented.

##### Version 1.0.2 _(Aug 24, 2021)_

- A light translation check/proofreading pass of half the game has been completed, fixing incorrect terminology, inaccuracies, and inconsistencies.
- TIPS section has been adjusted for readability.

##### Version 1.0.1 _(Feb 13, 2021)_

- Translation, consistency, and typo fixes.
- Fixed some text-wrapping issues.
- Fixed an issue regarding long names in the backlog.

##### Version 1.0 _(Feb 07, 2021)_

Initial release.

# <a name="features"></a>Features

##### Script fixes

Corrects major mistranslations, continuity errors, and other translation flaws.

These range from simple punctuation mistakes to huge errors that could impact one’s understanding of the game, such as inaccurate characterization, wrong names, or inconsistent terminology.

Additionally, certain terms were translated differently between ROBOTICS;NOTES DaSH and the other Science Adventure localizations—we’ve corrected as many of those inconsistencies as we could. This includes changing the name order to Japanese-style (e.g. “Itaru Hashida” → “Hashida Itaru”).

##### Retranslated TIPs

Every single TIP has been modified in some way. Some of them required minor edits for flow and style, others needed to be rewritten to account for stiff or confusing writing, and many of them needed to be partially or completely retranslated due to missing or incorrect information.

##### Typography improvements

Displays tweeps, geotags, the backlog, and basically any and all text in a nicer font with better formatting.

##### Subtitles

There are optional karaoke subtitles for openings and endings available—you have the option to choose between Japanese + English song subtitles, Japanese only, or English only.

##### Translated CGs

Contains new translated versions of most CGs. This includes a number of CGs that were translated in the original Steam version, which have been replaced with variations that are improved both visually and translation-wise. In addition, the phase title cards now feature added translations for the Japanese titles. (This is not to be confused with the English titles: every phase features two titles, one in English and one in Japanese, and they’re always totally different.)

##### Mouse support

We've fully implemented mouse support in ROBOTICS;NOTES DaSH, just like we did for the ROBOTICS;NOTES ELITE patch.
Since all the features in ROBOTICS;NOTES DaSH were already included in our ROBOTICS;NOTES ELITE patch, we replicated the control scheme we used for all features in that game.

Likewise, the HELP screen has been updated to reflect the added mouse controls.

##### Added auto/skip buttons

As part of the mouse support implementation, we've designed and added auto/skip buttons, just like we did for the ROBOTICS;NOTES ELITE patch. (Keyboard and gamepad shortcuts for these functions will still work.)

##### Save game compatibility

Can be installed over the Steam version of the game without breaking existing saves.

# <a name="guides"></a>Guides

- [100% Spoiler-free Walkthrough]({{ "/projects/rnd-walkthrough.html" | relative_url }})
- [Installing on Linux and Steam Deck]({{ "/projects/coz-linux-deck.html" | relative_url }})

# Installation instructions

1. **[↓ Download the installer](https://github.com/CommitteeOfZero/rnd-patch/releases).** You want `RNDPatch-v<version>-Setup.zip`, not the source code.
2. Extract the archive somewhere on your hard drive, not in your game directory.
3. Go to the newly created `RNDPatch-v<version>-Setup` folder and run `RNDPatch-Installer.exe`. **Warning:** Has sound.

- If the installer quits with an error about `MSVCP140_1.dll`, install [Visual C++ Redistributable](https://aka.ms/vs/16/release/vc_redist.x86.exe) (32-bit version, vc_redist.x86.exe - regardless of your system) and try again.

4. After you click _Finish_ and the installer closes, you can delete the `RNDPatch-v<version>-Setup` folder.

# Troubleshooting

If you're having a problem not covered here, please [ask us on Discord](https://discord.gg/rq4GGCh) about it.

**Note:** The game uses components from the latest **DirectX End-User Runtimes** (you may not have these even if you have the right DirectX version). If the game fails to run for you, [install DirectX End-User Runtimes](https://www.microsoft.com/en-us/download/details.aspx?id=35). (Steam should take care of this for you, but we're leaving it here just in case.)

### Game/launcher fails to start from Steam

You can try starting the launcher from the desktop/start menu shortcut (if you created one during the installation) or by directly running `LauncherC0.exe` from the game directory (right click _ROBOTICS;NOTES DaSH_ in your Steam library, _Properties_ → _Local Files_ → _Browse Local Files..._). Make sure you're logged into Steam, though.

### Game shows an error about `mgs::Audio::CPlayer::InitializeXaudio()`

![XAudio2 error]({{ "/uploads/error_xaudio.png" | absolute_url }})

Install [DirectX End-User Runtimes](https://www.microsoft.com/en-us/download/details.aspx?id=35) and try again.

### Installer shows an error about `MSVCP140_1.dll`

![MSVCP140.dll error]({{ "/uploads/error_vcruntime_sg0_steam.png" | absolute_url }})

Install [Visual C++ Redistributable](https://aka.ms/vs/16/release/vc_redist.x86.exe) (32-bit version, vc_redist.x86.exe - regardless of your system) and try again.

### Installer shows an error about `api-ms-win-crt-runtime-l1-1-0.dll`

![UCRT error]({{ "/uploads/error_ucrt.png" | absolute_url }})

Update Windows. You may need to install the Visual C++ Redistributable again afterward (file above) - use “Repair” when prompted.

# Credits

- **Hacking**: MrComputerRevo, JoseJL, daxxy, SomeAnon
- **Translation**: Enorovan, ChrisGLink, Rain, ItsRigs
- **Editing**: Kumin
- **Image editing**: LkProd, TehVict, Kumin
- **Subtitles**: zahj

Special thanks to [grechnik](https://github.com/grechnik) for contributing to our open-source repository!

This project includes a number of third-party components. See [this page]({{ "/projects/rnd-thirdparty.html" | relative_url }}) for attribution.

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
- [CHAOS;CHILD Improvement Patch]({{ "/projects/chaoschild-steam.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-gog.svg" | relative_url }}">
- [STEINS;GATE 0 Steam Patch]({{ "/projects/sg0-steam.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
- [ANONYMOUS;CODE Improvement Patch]({{ "/projects/ac-patch.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
