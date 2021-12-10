---
title: "Scoreless First Quarters"
date: 2021-12-10T10:56:08+11:00
categories:
 - "Blog"
tags:
 - "R"
 - "AFL" 
 - "Stats"
 - "Sports"
---

<!--more-->

I have an uncle who coaches junior football in Melbourne. He has provided several suggestions on topics for potential posts since I started putting these out earlier in the year.

One suggestion was exploring who had recorded the most disposals in a game after getting zero or one touches in the first quarter. He wanted something with a focus on resilience for background material when he talks with the juniors in the future.

This is an interesting question, but I have been able to track down an answer. If anyone knows, please let me know!

However, the stats available via the [fitzRoy package](https://cran.r-project.org/web/packages/fitzRoy/fitzRoy.pdf) has a quarter-by-quarter breakdown of team scores for every game since 1897. So, I’ll tweak the question slightly and look at how teams have performed after going scoreless in the first quarter. 

Three hundred and fourteen of the 15,983 AFL games played to date have had one team scoreless at quarter time. This equates to **just under 2% of all games**. 

It didn’t take long for a team to play an entire quarter without scoring. The first of the 314 games occurred in Round 1, 1897, when Geelong failed to trouble the scorers against Essendon. Geelong backed it up again the next week against Melbourne.

The most recent scoreless first quarter was Adelaide against St Kilda in Round 13, 2021. However, Adelaide got the last laugh with Riley Thilthorpe [kicking with winning goal over his own head](https://www.youtube.com/watch?v=ztvZBT2keG4) in the dying stages of the game.

From the graph below we can see that the number of games each year with scoreless first quarters has declined over time. The **1899 season had the most of these games with 17**, while there have been 20 seasons without a scoreless first quarter.

![Figure 1](/img/content/posts/scoreless-first-quarters/scoreless_graph1.png)

The COVID impacted 2020 season stands out somewhat compared to the past 40-odd years, with **seven games** with scoreless first quarters. These seven games were:
- **Carlton** v Melbourne, Round 2
- Gold Coast v **Adelaide**, Round 3
- Richmond v **North Melbourne**, Round 7
- **Fremantle** v Collingwood, Round 9
- West Coast v **Hawthorn**, Round 12
- Gold Coast v **Carlton**, Round 13
- North Melbourne v **West Coast**, Round 18
(The team listed in **bold** text had the scoreless first quarter)

Despite their poor start in the VFL, Geelong have faired better since and now sit more towards the middle of the pack in terms of games where they failed to score in the first quarter. The graph below shows the number of games each team went scoreless in the first quarter.

![Figure 2](/img/content/posts/scoreless-first-quarters/scoreless_graph2.png)

Every team in V/AFL history has had at least one scoreless quarter. **St Kilda (39)** and **Carlton (37)** have the unenviable record of having the most scoreless first quarters. I find it surprising that Gold Coast and Greater Western Sydney only have one scoreless first quarter each, given some of the losses they copped when they were first introduced to the competition. 

Teams with a scoreless first quarter have a W-L record of 58-256, meaning they only win 18.5% of the time. It’s therefore not surprising that almost all the teams have a lower winning percentage in these games (as displayed in the graph below).

Fremantle is the only exception, **having gone on to win two of three games in which they were scoreless at quarter time**. 

The Brisbane Bears, Brisbane Lions, Gold Coast, Greater Western Sydney, Hawthorn, and Port Adelaide are excluded from the graph below as these teams have never won a game after failing to score in the first quarter. 

![Figure 3](/img/content/posts/scoreless-first-quarters/scoreless_graph3.png)

In closing, I need to apologise to my uncle on this one---not the most encouraging results…

*If you’re wondering, no match in AFL history has had both teams fail to score in the first quarter. The closest a game has ever gotten was in Round 1, 1965, when Geelong (who were scoreless at quarter time) hosted Footscray (who registered a single behind).*

--- 

*As always, I apologise to anyone who has already looked at these stats.*