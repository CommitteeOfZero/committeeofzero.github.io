---
title: "CHAOS;CHILD: Buying digital PC version"
layout: page
permalink: "/projects/cc-buying-digital-pc-version.html"
active_tab: projects
date: 2018-06-30 22:30:00 +0100
excerpt: <p>Guide for buying and downloading the digital PC version of CHAOS;CHILD without living in Japan</p>
---

[← Back to project page]({{ "/projects/chaoschild.html" | relative_url }})

# Outdated

<div style="border: 1px solid #fff; padding: 8px;">
<p>This page is for the old version of the <i>CHAOS;CHILD PC English Patch</i> that combined the Vita English scripts with the Japanese PC version.</p>

<p>The current version of our patch works with the official English Steam release and doesn't require any other versions of the game.</p>

<p><a href='{{ "/projects/chaoschild-steam.html" | relative_url }}'>You can find the page about the Steam patch here.</a></p>
</div>

# Previous contents

Assuming you don't live in Japan, you will need to use a Japanese proxy/VPN to buy a digital copy of *CHAOS;CHILD* for PC. If you don't have access to such, you can use *Tor*:

##### Setting up Tor

1. Download and install *[Tor Browser](https://www.torproject.org/projects/torbrowser.html.en#downloads)*.
2. Run the program once, then close it again.
3. Find the directory you installed *Tor Browser* in.
4. Go to `Browser\TorBrowser\Data\Tor` and open `torrc` in your text editor (e.g. *Notepad*).
5. Add the following two lines:

   ~~~
   ExitNodes {jp}
   StrictNodes 1
   ~~~
6. Start *Tor Browser* again.
7. Open the menu, go to *Options*, select *Privacy*.
8. Uncheck "Restrict third party cookies and other tracking data".
9. Uncheck "Always use private browsing mode". *Tor Browser* will ask to be restarted. Allow it.

##### Buying the game

In the following guide, do everything labeled "with proxy" while connecting through your proxy/VPN (or in *Tor Browser*), and everything labeled "without proxy" with your proxy/VPN turned off (or in your regular web browser).

1. With proxy: [Register](https://www.dmm.com/my/-/register/) on DMM.com.
2. Without proxy: Login on DMM.com, then [top up DMM points](https://www.dmm.com/en/my/-/point/balance/). One Point = One Yen, so top up as many as *[CHAOS;CHILD](http://dlsoft.dmm.com/detail/ihobe_0029/)* currently costs.
  * DMM no longer accepts Western credit cards for direct game purchases. Buying DMM points with your credit card and using them to buy games may work. However, we have only tested this with PayPal.
3. With proxy: Buy *[CHAOS;CHILD](http://dlsoft.dmm.com/detail/ihobe_0029/)*.
4. With proxy: Go to [your game library](http://dlsoft.dmm.com/mylibrary/), click *CHAOS;CHILD*. Right click buttons 1, 2, 3, 4, 5 as well as the button with the download icon above, click "Save Link As..." for each, and save the files to the same folder, not changing the file names.

[← Back to project page]({{ "/projects/chaoschild.html" | relative_url }})