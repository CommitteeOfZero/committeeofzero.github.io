---
title: "ROBOTICS;NOTES ELITE Steam Patch"
layout: post
permalink: "/projects/rne-steam.html"
active_tab: projects
date: 2020-11-15 22:00:00 +0100
excerpt: <p>It's time for robots.</p>
---

It’s time for robots.

Yes, it's here—our most ambitious patch yet. As “that person” says, “we couldn't stand idly by and ignore allies in trouble.” See, robots represent a kind of bond to us; they are a form of hope. And we couldn't just let that bond or that hope die.

This patch features a significant number of changes and fixes to improve the English release of ROBOTICS;NOTES ELITE on Steam, including typo fixes, a thorough check of every line of the translation, changes for consistency with the rest of the Science Adventure Series, and even the implementation of mouse support into the game! See [below](#features) for a full list of features.


<div style="border: 1px solid #fff; padding: 8px;">
Download link and instructions are <a href="#guides">↓ below</a>.
</div>

If you want a spoiler-free guide on how to obtain every ending, you can find one [here]({{ "/projects/rne-walkthrough.html" | relative_url }}).

[Join us on Discord](https://discord.gg/rq4GGCh) for fun, ~~shitposting~~ and support.

# Screenshots

{% include thumb.html fullsize="/uploads/rne_consistency_typography.png" thumb="/uploads/rne_consistency_typography_thumb.png" caption="Consistency / Typography" %}
{% include thumb.html fullsize="/uploads/rne_extracgs.png" thumb="/uploads/rne_extracgs_thumb.png" caption="Translated CGs" %}
{% include thumb.html fullsize="/uploads/rne_videos.png" thumb="/uploads/rne_videos_thumb.png" caption="Translated Videos" %}
{% include thumb.html fullsize="https://www.youtube.com/watch?v=CxHhW5Um6MI" fullsize_ext=true thumb="/uploads/rne_mouse_thumb.png" caption="Mouse Support" %}

# Changelog

##### Version 1.0.9 *(Oct 10, 2022)*

* More translation, consistency, and typo fixes.

##### Version 1.0.8 *(Apr 1, 2022)*

* More translation, consistency, and typo fixes.

##### Version 1.0.7 *(Aug 24, 2021)*

* Minor text fixes, as well as improved consistency with STEINS;GATE.
* TIPS section has been adjusted for readability.

##### Version 1.0.6 *(Apr 02, 2021)*

* Translated remaining untranslated CGs.
* More translation, consistency, and typo fixes.

##### Version 1.0.5 *(Feb 07, 2021)*

* More translation, consistency, and typo fixes.
* Added the original ROBOTICS;NOTES opening to the movie library.

##### Version 1.0.4 *(Dec 28, 2020)*

* More translation, consistency, and typo fixes.

##### Version 1.0.3a *(Dec 7, 2020)*

* Compatibility update for 12/06/2020 game patch.

##### Version 1.0.3 *(Dec 6, 2020)*

* More translation, consistency, and typo fixes.
* Fixed clipping in some character animations.
* Fixed an instance where an incorrect character model was used.
* Fixed a background that was being displayed with the wrong color.
* Fixed an issue where tips would line break improperly.
* Fixed an issue where the launcher would crash for some users when pressing the "More Settings" button.
* Re-encoded videos for better quality.

##### Version 1.0.2 *(Dec 3, 2020)*

* More translation, consistency, and typo fixes.
* Fixed mouse controls being inaccurate for ultrawide monitors.
* Fixed some text-wrapping issues.

##### Version 1.0.1 *(Nov 19, 2020)*

* Translation, consistency, and typo fixes.
* Fixed text-wrapping issues with em dashes, quotes, brackets, and parentheses.
* Fixed issues with text margins.
* Fixed an issue with misplaced voice lines.
* Fixed improperly displayed names. 

##### Version 1.0 *(Nov 15, 2020)*

Initial release.

# <a name="features"></a>Features

##### Script fixes

Corrects *countless* mistranslations, continuity errors and other translation flaws. (Note: not actually countless, but so many we didn’t have time to count. We at least know this: around one-third of the lines in the game have been changed.)

These range from simple punctuation mistakes to huge errors that could impact one’s understanding of the game, such as inaccurate characterization, wrong names, or inconsistent terminology.

Additionally, certain terms are translated differently between ROBOTICS;NOTES ELITE and the other Science Adventure localizations, and we’ve corrected as many of those as we could as well. This includes changing the name order to Japanese-style (e.g. “Kaito Yashio” → “Yashio Kaito”).

##### Typography improvements

Displays documents, tweeps, geotags, the backlog, and basically any and all text in a nicer font with better formatting.

##### Translated videos

Pretty much every video containing text in the game has been translated—or had its original translation improved. Additionally, there are optional karaoke subtitles for openings and endings—with the option to select between Japanese + English song subtitles, Japanese only, or English only.

##### Translated CGs

Contains new translated versions of most CGs. This includes a number of CGs that were translated in the original Steam version, which have been replaced with variations that are both visually improved and better-translated. In addition, the phase title cards now feature added translations for the Japanese titles. (This is not to be confused with the English titles: every phase actually features two titles, one in English and one in Japanese, and they’re always totally different.)

##### Mouse support

We've fully implemented mouse support in ROBOTICS;NOTES ELITE. Next to our full check of the translation, this is probably the most impressive feat of any of our patches so far.
For all features in ROBOTICS;NOTES ELITE included in other PC Science Adventure games, we've done our best to replicate the controls as closely as possible, and for new features like 'IRUO.', we've implemented brand-new control schemes.
Naturally, the HELP screen has been updated to reflect the new controls.

##### Added auto/skip buttons

As part of the mouse support implementation, we've designed and added auto/skip buttons, just like the other Science Adventure PC games. (Keyboard and gamepad shortcuts for these will still work.)

##### Fixed skip function

We've fixed a bug with the implementation of the "skip" function. In the newer ports of ROBOTICS;NOTES ELITE, the skip function was totally broken. Even when set to "Read text only," it would skip lines at random, regardless of whether or not they've been read before. That should all be dealt with now.

##### Save game compatibility

Can be installed over the Steam version of the game without breaking existing saves.

# <a name="guides"></a>Guides

* [100% Spoiler-free Walkthrough]({{ "/projects/rne-walkthrough.html" | relative_url }})

# Installation instructions

1. **[↓ Download the installer](https://github.com/CommitteeOfZero/rne-patch/releases).** You want `RNEPatch-v<version>-Setup.zip`, not the source code.
2. Extract the archive somewhere on your hard drive, not in your game directory.
3. Go to the newly created `RNEPatch-v<version>-Setup` folder and run `RNEPatch-Installer.exe`. **Warning:** Has sound.
  * If the installer quits with an error about `MSVCP140_1.dll`, install [Visual C++ Redistributable](https://aka.ms/vs/16/release/vc_redist.x86.exe) (32-bit version, vc_redist.x86.exe - regardless of your system) and try again.
4. After you click *Finish* and the installer closes, you can delete the `RNEPatch-v<version>-Setup` folder.

# Troubleshooting

If you're having a problem not covered here, please [ask us on Discord](https://discord.gg/rq4GGCh) about it.

**Note:** The game uses components from the latest **DirectX End-User Runtimes** (you may not have these even if you have the right DirectX version). If the game fails to run for you, [install DirectX End-User Runtimes](https://www.microsoft.com/en-us/download/details.aspx?id=35). (Steam should take care of this for you, but we're leaving it here just in case.)

### Game/launcher fails to start from Steam

You can try starting the launcher from the desktop/start menu shortcut (if you created one during the installation) or by directly running `LauncherC0.exe` from the game directory (right click *ROBOTICS;NOTES ELITE* in your Steam library, *Properties* → *Local Files* → *Browse Local Files...*). Make sure you're logged into Steam, though.

### Game shows an error about `mgs::Audio::CPlayer::InitializeXaudio()`

![XAudio2 error]({{ "/uploads/error_xaudio.png" | absolute_url }})

Install [DirectX End-User Runtimes](https://www.microsoft.com/en-us/download/details.aspx?id=35) and try again.

### Installer shows an error about `MSVCP140_1.dll`

![MSVCP140.dll error]({{ "/uploads/error_vcruntime_sg0_steam.png" | absolute_url }})

Install [Visual C++ Redistributable](https://aka.ms/vs/16/release/vc_redist.x86.exe) (32-bit version, vc_redist.x86.exe - regardless of your system) and try again.

### Installer shows an error about `api-ms-win-crt-runtime-l1-1-0.dll`

![UCRT error]({{ "/uploads/error_ucrt.png" | absolute_url }})

Update Windows. You may need to install the Visual C++ Redistributable again afterwards (file above) - use “Repair” when prompted.

# Credits

* **Hacking**: MrComputerRevo, JoseJL, SomeAnon, daxxy
* **Translation**: ChrisGLink (and his baby nephew), Enorovan, Jake, Barrafas, WitchEvelyn, Rain, ItsRigs
* **Editing**: Discontinuous Qualia, Fasty, Kumin
* **Image editing**: LkProd, TehVict, Enorovan, WizardNoah, Kumin, MrComputerRevo
* **Subtitles**: zahj
* **Video editing**: LkProd

Special thanks to [grechnik](https://github.com/grechnik) for contributing to our open source repository!

This project includes a number of third-party components. See [this page]({{ "/projects/rne-thirdparty.html" | relative_url }}) for attribution.
