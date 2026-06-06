---
title: "Committee of Zero - Progress Update #13"
layout: post
excerpt: <p>Welcome back, Science Adventurers! It’s been around ten months since we last gave you a general update.</p>
date: 2026-06-06 00:00:00 +0000
---

Welcome back, Science Adventurers! It’s been around ten months since we last gave you a general update; we’ve been releasing some smaller updates over on our Twitter and Discord, but in case you’ve missed those, here’s the latest on the LCC Double Pack Translation Patch, our other projects, our future plans, and more.

In this report, we won’t be addressing the games separately like we usually do, but we’ll still keep things categorized in individual sections. Now, let’s not waste any more time and dive right into it!

# Translations

For the past year, some of our trusted community members have been QA testing our scripts while utilizing our ports so they may report any mistake or typo that may have slipped through. A vast majority of our testers have completed their passes, a process which has greatly helped with ironing out the text, as well as some scripting manipulations going awry (such as adding tips for the localization).

The translation team as well as the Head Editor consider the script as close as it can be to finished, although we’re ideally expecting one last pass from our Head Translator, both for technical and perfectionist reasons.

# Assets

All necessary assets have been edited, including CGs, videos, and songs, with the sole exception being the credits, as they are still in progress.

There’s a small bonus we’re working on as well, but due to its complexity, we’re not sure it’ll make the cut just yet. All in due time...

# Ports: What’s Done

The most important area to follow on our path to release is the ports.

It is no exaggeration to say that the amount of (steady) work that has been done in the past year by our three main developers (Dextinfire, PringlesGang, and Gunoshozo), as well as a few select external contributors, has been monumental.

Last time we spoke, we mentioned that most of C;CLCC’s base UI had been implemented. But since then:

- The C;HLCC menus, which are *loaded* with complex animations, are 100% complete.
- The C;CLCC menus are 95% complete, with only the iconic “smoke” effect carried over from C;C remaining.
- We built our subtitles implementation directly into the engine, which also allowed us for the first time (outside of A;C which is a different engine) to render stylized subs on insert songs.
- We implemented all in-script VFXs, which with both games combined amounts to 20, some of them being used once or twice. We’re talking wave effects, transitions, masks, and more.
- We squashed a lot, and we mean a *lot,* of little bugs caused by very small code inaccuracies, the game being set to certain resolutions, or even the weirdest one so far: only on Steam Link.
- Naturally, the most important thing of all in CHAOS; games, the Delusion Triggers, are now fully implemented! And as a bonus, we also included one other surprise: mouse support!
- Script patches to bring the game closer to proper PC behavior (such as exit prompts).
- And more...

At this point in time, you have to know the game by heart to know what’s still wrong with the core gameplay. But we want everyone’s experience to be as close to perfect and as close to the original release as possible; to meet this end, there’s still a bit more to go.

To give you a better idea of what we’ve accomplished, here is a compilation of the sizzle reels our Project Manager has shared over the past year:

<div class="youtube-wrapper"><iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/LZO8pFDfnP4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>

Now, let’s get into what’s left.

# Ports: What’s Left

As you gathered with the section above, there isn’t a whole lot! However, we have yet to address something that’s pretty important: accessibility and ease of installation. Our goal has always been and always will be to support the official release; in order to utilize our patch, you will have to obtain the game files from the Japanese copy you bought. Once you’ve done that, though, we want it just to take a few clicks to get our patch up and running so you can enjoy the games at their fullest. So here’s what we’re doing to address that.

- We’re currently reviewing our patch framework implementation that just got done, which will allow us to override select assets we translated, drive configuration (Do you actually want mouse support? English or Japanese?), and so on, paired with an overlay that will allow such configuration, much like other re-implementations of VERY popular games have been doing.
- We’re currently working on the achievement system in order to emulate the original release; this includes the system itself, notifications, and the overlay as a whole.
- Preliminary work on the installer has just begun; we plan to allow direct install for PC Operating Systems, as well as a simple “drag-and-drop” for CFW Switch and Android.
- We’re optimizing the CFW Switch build; we have yet to wrap up the Android input system; and we also are working on getting Impacto to run as a proper app on macOS.

<hr>

We also have a few remaining tasks as far as polishing goes—we’re really getting close to release if so much of what’s left is just polishing!

- We’re redoing the separation between the different ways text is handled in those games (ADV, NVL, Tips, Backlog, Special) so that they all meet their expected behaviors without impacting one another (e.g: the backlog shouldn’t be displaying weird margins or colors shown in ADV or NVL), which will also fix the wordwrapping in Japanese, as well as implement our final in-script issue: displaying two lines at the same time. (All of this is what we want to test thoroughly with our last QA pass).
- The remaining 5% of C;CLCC UI/specific code is already getting worked on.
- Using the default fonts when playing in Japanese and polishing the fades when the characters appear.
- Ensure the Switch Double Pack assets are inserted properly.
- Remaining Script Patches for keyboard inputs.
- Multi-controller button guides.
- We’re considering a heavy change in our visual renderers; this will allow us to build for even more platforms, though we have yet to decide if this is part of the plan for 1.0.0.

And that’s it! As you may have gathered, there is still a lot to be done on the tech end, but there’s almost nothing major that hasn’t been at least investigated.

And of course, for what will likely be for the last time, a reminder that all of this is open-source. Anyone can contribute, especially when it comes to lending a hand on the smaller tasks; the more help we get, the closer the ports get to completion. You can find the repository [on GitHub](https://github.com/CommitteeOfZero/impacto).

You can also check the ports’ progress updated live over [here]({{ "/projects/lcc-dp-trailer.html" | relative_url }}).

# All of this to say...?

We are once again reaffirming that the LCC Double Pack Translation Patch will be released this year, in 2026. We are so close we can touch it, but there still is work to do; summer’s coming up soon, so we mean to get a lot of it done over the next few months.

Without giving a definitive date, but because a release window is somewhat overdue, we will put everything we have into releasing the LCC Translation Patches **<u>around the time the CHAOS; games usually take place</u>**. Of course, we’ll try to space it out so that everyone will get to enjoy STEINS;GATE RE:BOOT when that game comes out too (congratulations Steiner and Blick, by the way!), so keep an eye on our Twitter and Discord for updates!

We look forward to celebrating our most ambitious release yet with you! Till next time!
