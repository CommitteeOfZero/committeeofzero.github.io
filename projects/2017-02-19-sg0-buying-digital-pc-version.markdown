---
title: "STEINS;GATE 0: Buying digital PC version"
layout: page
permalink: "/projects/sg0-buying-digital-pc-version.html"
active_tab: projects
date: 2017-02-19 01:13:49 +0100
excerpt: <p>Guide for buying and downloading the digital PC version of STEINS;GATE 0 without living in Japan</p>
---

[← Back to project page]({{ "/projects/sg0.html" | relative_url }})

Assuming you don't live in Japan, you will need to use a Japanese proxy/VPN to buy a digital copy of _STEINS;GATE 0_ for PC. If you don't have access to such, you can use _Tor_:

##### Setting up Tor

1. Download and install _[Tor Browser](https://www.torproject.org/projects/torbrowser.html.en#downloads)_.
2. Run the program once, then close it again.
3. Find the directory you installed _Tor Browser_ in.
4. Go to `Browser\TorBrowser\Data\Tor` and open `torrc` in your text editor (e.g. _Notepad_).
5. Add the following two lines:

   ```
   ExitNodes {jp}
   StrictNodes 1
   ```

6. Start _Tor Browser_ again.
7. Open the menu, go to _Options_, select _Privacy_.
8. Uncheck "Restrict third party cookies and other tracking data".
9. Uncheck "Always use private browsing mode". _Tor Browser_ will ask to be restarted. Allow it.

##### Buying the game

In the following guide, do everything labeled "with proxy" while connecting through your proxy/VPN (or in _Tor Browser_), and everything labeled "without proxy" with your proxy/VPN turned off (or in your regular web browser).

1. With proxy: [Register](https://www.dmm.com/my/-/register/) on DMM.com.
2. Without proxy: Login on DMM.com, then [add your credit card](https://www.dmm.com/en/my/-/payment/) or [top up DMM points](https://www.dmm.com/en/my/-/point/balance/). One Point = One Yen, so top up as many as _[STEINS;GATE 0](http://dlsoft.dmm.com/detail/ihobe_0031/)_ currently costs.
3. With proxy: Buy _[STEINS;GATE 0](http://dlsoft.dmm.com/detail/ihobe_0031/)_.
4. With proxy: Go to [your game library](http://dlsoft.dmm.com/mylibrary/), click _STEINS;GATE 0_. Right click buttons 1, 2 and 3 as well as the button with the download icon above, click "Save Link As..." for each, and save the files to the same folder, not changing the file names.

[← Back to project page]({{ "/projects/sg0.html" | relative_url }})
