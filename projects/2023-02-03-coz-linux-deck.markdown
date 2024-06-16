---
title: "Installing Patches on Linux and Steam Deck"
layout: page
permalink: "/projects/coz-linux-deck.html"
active_tab: guides
date: 2023-02-03 00:00:00 +0100
excerpt: <p>Linux and Steam Deck installation instructions for all of our patches.</p>
---

## ANONYMOUS;CODE Video Fix

ANONYMOUS;CODE currently relies on a custom Proton GE build (ProtonGE-AC) for proper video playback, developed by community contributor [Hawkheart](https://github.com/Hawkheart).

The build can be found [**here**](https://github.com/CommitteeOfZero/ProtonGE-AC/releases/download/1.0.0/protonge-anonymouscode.tar.gz) and specific installation instructions [**here**](https://github.com/GloriousEggroll/proton-ge-custom#installation). Please make sure to install this custom build and run the game to generate a prefix based on it **_before_** any attempt at installing the ANONYMOUS;CODE Improvement Patch through _The Polyversal Linux Steam Patcher for the Committee of Zero's Science Adventure Steam Patches on Linux_.

ANONYMOUS;CODE has other issues on Proton regarding audio playback in dialogue and lockups in gameplay, but our ANONYMOUS;CODE Improvement Patch addresses these by including the xaudio 2.9 library in its 1.0.1 version. With the custom Proton GE build and our patch, the game should operate completely as intended.

For our leet hackers out there, you can find the GitHub commit for the video playback fix [here](https://github.com/GloriousEggroll/proton-ge-custom/compare/master...Hawkheart:proton:anonymouscode-fix), with its issue history documented [here](https://github.com/ValveSoftware/Proton/issues/7083).

<hr>

Head to the Polyversal CoZ Linux patcher repository by clicking on this [link](https://github.com/CommitteeOfZero/polyversal-coz-linux-patcher).
