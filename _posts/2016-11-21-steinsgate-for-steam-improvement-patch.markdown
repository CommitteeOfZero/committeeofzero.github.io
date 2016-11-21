---
title: "STEINS;GATE for Steam improvement patch"
layout: post
permalink: "/projects/sghd.html"
active_tab: projects
date: 2016-11-21 01:04:37 +0100
---

Greetings and salutations, lab mems and gigalomaniacs. We're guessing since you're here, you must have heard of the recent(ish) release of [STEINS;GATE on Steam](http://store.steampowered.com/app/412830/). We also assume you know it has several significant flaws which made playing it uncomfortable. We set out to fix those flaws, improve upon the release and make this the best version of STEINS;GATE out there.

You can [download the patch here](https://github.com/CommitteeOfZero/sghd-patch/releases). Installation instructions are [below](#installation).

This was just a side project of a side project. Stay tuned, you'll be hearing again from us soon.

**We're currently looking for a translator!** Please take a look at [our recruitment post]({% post_url 2016-11-21-chaoshead-noah-looking-for-translators %}) if you think you can help.

# Features
Here's the full list of improvements. Each can be turned on and off individually, if you like.

##### Better typography
Adds word-wrapping to the phone and displays text in a nicer font.

[![Typography - before]({{ "/uploads/sghd_text_before_thumb.png" | relative_url }}){:height="274px" :width="274px"}]({{ "/uploads/sghd_text_before.png" | relative_url }}){:style="margin-right: 8px"}
[![Typography - after]({{ "/uploads/sghd_text_after_thumb.png" | relative_url }}){:height="274px" :width="274px"}]({{ "/uploads/sghd_text_after.png" | relative_url }})

##### Proper English
Fixes various typos/mistranslations in menu text.

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
Adds subtitles to some translated videos, allowing you to use the high-quality Japanese originals. Requires manual setup, [see below](#jpvideo).

# <a name="installation"></a>Installation instructions
This patch is for the English Steam version of STEINS;GATE. The JAST release, Steam version set to Japanese and pirated copies are not supported.

1. **Download [the patch](https://github.com/CommitteeOfZero/sghd-patch/releases).**
2. Go to your STEINS;GATE installation folder. By default this is `C:\Program Files (x86)\Steam\SteamApps\common\STEINS;GATE`.
   * In case you installed the game to a different Steam library folder and need help finding it: Right click *STEINS;GATE* in your Steam library, go to *Properties*, *Local Files*, *Browse Local Files...*
3. Open the patch archive you just downloaded.
4. Copy its contents to the STEINS;GATE installation folder.
5. (Optional) Run LBConfig.exe to disable or enable features.

##### <a name="jpvideo"></a>Higher-quality video instructions
These are the (optional) steps for using softsubbed original videos in place of the hard-translated English ones. This feature is disabled by default because it involves manually redownloading gigabytes of game data twice for minor quality gains for a small amount of content. If you still wish to use it, follow these instructions:

1. In your Steam library, right click *STEINS;GATE*, go to *Properties*, *Language* and switch to Japanese. Close the properties window.
2. Wait for the game data to finish downloading.
3. Browse to the game folder.
4. Copy the `USRDIR\movie` folder somewhere else.
5. Switch the game language back to English.
6. Wait for the game data to finish downloading again.
7. Copy the previously backed up `USRDIR\movie` folder back in.
8. After installing the patch, run LBConfig.exe and turn on this option.

# Credits
* **Cypert:** Image editing, subs
* **SomeAnon, DrDaxxy:** Reverse engineering, hacking
* **zahj, SnowedEarth:** Karaoke subtitles

Translated lyrics for 'Skyclad Observer', 'Farfalla of Fate' and 'A.R.' taken from the previous JAST USA release of STEINS;GATE.

This project includes a number of third-party components. See [this page](https://github.com/CommitteeOfZero/LanguageBarrier/blob/master/LanguageBarrier/THIRDPARTY) for attribution and licenses.