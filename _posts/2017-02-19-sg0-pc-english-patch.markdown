---
title: "STEINS;GATE 0 PC English Patch"
layout: post
permalink: "/projects/sg0.html"
active_tab: projects
date: 2017-02-19 02:04:01 +0100
excerpt: <p>Turns out compressing an entire patch down to 36 bytes isn't as easy as Chiyomaru makes it seem. We had planned to send it back to the past to release it on time, but then CERN came and told us we can't use their LHC and gave us a slap on the wrist. So, we had to go the long way around.</p>
---

# Outdated

<div style="border: 1px solid #fff; padding: 8px;">
<p>This page is for the old version of the <i>STEINS;GATE 0 PC English Patch</i> that combined the Vita English scripts with the Japanese PC version.</p>

<p>The current version of our patch works with the official English Steam release and doesn't require any other versions of the game.</p>

<p><a href='{{ "/projects/sg0-steam.html" | relative_url }}'>You can find the page about the Steam patch here.</a></p>
</div>

# Previous contents

Turns out compressing an entire patch down to 36 bytes isn't as easy as Chiyomaru makes it seem. We had planned to send it back to the past to release it on time, but then CERN came and told us we can't use their LHC and gave us a slap on the wrist. So, we had to go the long way around.

This patch inserts the official English translation of STEINS;GATE 0 into the Japanese PC version while addressing various shortcomings and making a number of improvements to both the translation and the base game. See [below](#features) for a full list of features.

<div style="border: 1px solid #fff; padding: 8px;">
Download link and instructions are <a href="#guides">↓ below</a>.

<p>You are required to <b>own the PC version of the game as well as the decrypted, unmodified scripts of the English Vita version</b>. These can be extracted using a <b>Vita or PSTV on firmware 3.60</b> (lower versions can be upgraded to that, but downgrades are not possible). Modified scripts from pirate copies able to run the game on firmware 3.60 are not compatible.</p>

Both the physical and digital English Vita versions can be used, but getting the digital version <i>onto</i> your 3.60 device currently requires a PS3 or a second, latest firmware Vita.
</div>

You can find guides for buying the Japanese PC version and extracting the necessary data from the English Vita version [below](#guides).

[Join us on Discord](https://discord.gg/rq4GGCh) for fun, ~~shitposting~~ and support.

# Screenshots

{% include thumb.html fullsize="/uploads/sg0_typography_rine.png" thumb="/uploads/sg0_typography_rine_thumb.png" caption="Typography/RINE" %}
{% include thumb.html fullsize="/uploads/sg0_consistency.png" thumb="/uploads/sg0_consistency_thumb.png" caption="Consistency" %}
{% include thumb.html fullsize="/uploads/sg0_subtitles.png" thumb="/uploads/sg0_subtitles_thumb.png" caption="Subtitles" %}
{% include thumb.html fullsize="/uploads/sg0_extracgs.png" thumb="/uploads/sg0_extracgs_thumb.png" caption="Translated CGs" %}

# <a name="features"></a>Features

Many of these can be turned on and off individually.

##### Script fixes

Corrects several hundred typos, mistranslations, continuity errors and other translation flaws. These range from simple punctuation mistakes to errors great enough to impact one's understanding of the game, such as a reference to the wrong character.

##### Consistency fixes

Adds an option that changes terminology (such as names, objects, or products) to be more consistent with the previous *STEINS;GATE* VN translation and switches name order to Japanese (e.g. "Kyoma Hououin" => "Hououin Kyouma").

##### Better typography

Displays text in a nicer font and adds/corrects wordwrapping in *RINE* and dialogue. Outline improvement can be toggled and *RINE* name display can be [switched between white-with-black-shadow and pure black]({{ "/uploads/sg0_rine_comparison.png" | relative_url }}).

##### Subtitles

Translates some cutscenes and optionally adds styled karaoke subtitles to openings and endings.

##### Translated CGs

Contains translated versions of most CGs. CGs that were already translated in the official Vita localisation were reedited instead of being upscaled from 540p to 1080p.

##### More translations

Also translates stickers used in *RINE* conversations, system/menu text and the launcher.

##### High quality FMV audio

For openings, endings and some other videos, plays high-quality versions instead of the included low-quality audio tracks.

##### Hide auto/skip buttons

Includes an option to hide auto/skip buttons even when using mouse control (keyboard / gamepad shortcuts for these will still work).

##### Save game compatibility

Can be installed over the Japanese version or other patches without breaking existing saved games.

# <a name="guides"></a>Guides

* [How to buy the digital PC version]({{ "/projects/sg0-buying-digital-pc-version.html" | relative_url }})
* [How to extract the English Vita version scripts]({{ "/projects/sg0-extracting-english-vita-version-scripts.html" | relative_url }})

# Installation instructions

1. **[↓ Download the installer](https://github.com/CommitteeOfZero/zero-patch/releases).**
2. Run the installer. **Warning:** Has sound. If the installer doesn't run, install [.NET Framework 4](https://www.microsoft.com/en-us/download/details.aspx?id=17851) and try again.
3. Point *"Game directory:"* to the PC version's installation directory (containing files such as `Game.exe` and the `USRDIR` folder).
4. Point *"English Vita scripts:"* to the unencrypted, unmodified `USRDIR\script` directory copied from your English Vita version (containing files ending in `.scx`).
5. *"Create desktop shortcuts"* will create one shortcut for the game launcher and one shortcut to the patch configuration tool.
6. *"Run configuration tool after installation"* will run said configuration tool when installation finishes. Note you can also run it by starting `LBConfig.exe` inside the game directory after patch installation.

##### Known issues

If, after installing the patch and starting the game, you get stuck on a loading screen saying *"Checking trophies. Please do not turn off the power."*, download and run [CheckingTrophiesFix.exe](https://github.com/CommitteeOfZero/zero-patch/releases/download/1.00/CheckingTrophiesFix.exe), go to the game's installation directory, then `languagebarrier`, select `enscript.mpk` and click Open.

# Credits

* **Cypert:** Image editing
* **SomeAnon, daxxy:** Reverse engineering, hacking, installer
* **zahj, SnowedEarth:** Subtitles
* **Kumin, Discontinuous Qualia:** Script/subs editing
* **MrComputerRevo:** Script dumping tutorial

Special thanks to our vetted laboratory assistants for playtesting and proofreading!

This project includes a number of third-party components. See [this page]({{ "/projects/sg0-thirdparty.html" | relative_url }}) for attribution.
