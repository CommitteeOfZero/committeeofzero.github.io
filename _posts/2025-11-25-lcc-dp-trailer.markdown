---
title: "Love Chu☆Chu!!! Double Pack Translation Patch - Announcement Trailer"
layout: post
permalink: "/projects/lcc-dp-trailer.html"
active_tab: projects
date: 2025-11-25 00:00:00 +0000
excerpt: <br/><div class="youtube-wrapper"><iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/K5DUMwSiZso" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
---
## Love Chu☆Chu!!! Double Pack Translation Patch - Announcement Trailer

<div class="youtube-wrapper"><iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/K5DUMwSiZso" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>

## Latest Progress Report

You can find it [here]({{ "/2025/07/28/committee-of-zero-progress-update-12.html" | relative_url }}).

# Current Progress

## Porting (Impacto)

You can find the link to the repository [here](https://github.com/CommitteeOfZero/impacto).

Note that the number of issues isn't final, and that issues themselves vary in size.

<div id="milestones"></div>
<script>
fetch('https://api.github.com/repos/CommitteeOfZero/impacto/milestones')
  .then(res => res.json())
  .then(data => {
    const container = document.getElementById('milestones');
    data.sort((a, b) =>
      b.title.localeCompare(a.title, undefined, { sensitivity: 'base' })
    );
    container.innerHTML = data.map(milestone =>
      `<div style="border: 1px solid #fff; padding: 8px;">
         <h3><a href="${milestone.html_url}" target="_blank" rel="noopener noreferrer">${milestone.title}</a></h3>
         <ul>
          <li><u>Open Issues:</u> ${milestone.open_issues}</li>
          <li><u>Closed Issues:</u> ${milestone.closed_issues}</li>
          <li><b><u>Total Completion:</u> ${((milestone.closed_issues/(milestone.open_issues + milestone.closed_issues))*100).toFixed(2)}%</b></li>
         </ul>
       </div>`
    ).join('');
  });
</script>

\* These values are fetched automatically.

## Translation

Quality Assurance is in progress.

### CHAOS;HEAD Love Chu☆Chu! Overall Totals — November 25th, 2025

|                  | **Translation** | **TLC**     | **Editing** |
| ---------------- | --------------- | ----------- | ----------- |
| Common route     | 100.00%         | 100.00%     | 100.00%     |
| Nanami route     | 100.00%         | 100.00%     | 100.00%     |
| Yua route        | 100.00%         | 100.00%     | 100.00%     |
| Sena route       | 100.00%         | 100.00%     | 100.00%     |
| Kozue route      | 100.00%         | 100.00%     | 100.00%     |
| Ayase route      | 100.00%         | 100.00%     | 100.00%     |
| Rimi route       | 100.00%         | 100.00%     | 100.00%     |
| TIPs             | 100.00%         | 100.00%     | 100.00%     |
| **<u>Total</u>** | 100.00%         | 100.00%     | 100.00%     |

{: class="totals"}

### CHAOS;CHILD Love Chu☆Chu!! Overall Totals — November 25th, 2025

|                  | **Translation** | **TLC**     | **Editing** |
| ---------------- | --------------- | ----------- | ----------- |
| Common route     | 100.00%         | 100.00%     | 100.00%     |
| Hinae route      | 100.00%         | 100.00%     | 100.00%     |
| Hana route       | 100.00%         | 100.00%     | 100.00%     |
| Nono route       | 100.00%         | 100.00%     | 100.00%     |
| Serika route     | 100.00%         | 100.00%     | 100.00%     |
| Yui & Yuto route | 100.00%         | 100.00%     | 100.00%     |
| Itou route       | 100.00%         | 100.00%     | 100.00%     |
| Intermissions    | 100.00%         | 100.00%     | 100.00%     |
| TIPs             | 100.00%         | 100.00%     | 100.00%     |
| **<u>Total</u>** | 100.00%         | 100.00%     | 100.00%     |

{: class="totals"}

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
- [STEINS;GATE: My Darling's Embrace Improvement Patch]({{ "/projects/sgmde-patch.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
- [ROBOTICS;NOTES ELITE Steam Patch]({{ "/projects/rne-steam.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
- [STEINS;GATE: Linear Bounded Phenogram Improvement Patch]({{ "/projects/sglbp-patch.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
- [CHAOS;CHILD Improvement Patch]({{ "/projects/chaoschild-steam.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-gog.svg" | relative_url }}">
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-switch.svg" | relative_url }}">
- [STEINS;GATE 0 Steam Patch]({{ "/projects/sg0-steam.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
- [ROBOTICS;NOTES DaSH Steam Patch]({{ "/projects/rnd-steam.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
- [ANONYMOUS;CODE Improvement Patch]({{ "/projects/ac-patch.html" | relative_url }})
  <img style="width: 16px; height: 16px; margin: auto;" src="{{ "/assets/plat-icon-steam.svg" | relative_url }}">
