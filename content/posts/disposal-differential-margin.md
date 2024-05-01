---
title: "Disposal Differential and Margin"
date: 2024-05-02T06:59:05+10:00
categories:
 - "Blog"
tags:
 - "R"
 - "AFL" 
 - "Stats"
 - "Sports"
---

*Does winning more of the ball translate to winning on the scoreboard?*

<!--more-->

Last week I watched the ANZAC Eve game between Richmond and Melbourne while sitting in the Darwin airport, waiting for my flight home after visiting the Top End for a conference. 

It was early in the final quarter when a graphic came up on the screen and caught my attention: Melbourne, despite leading by 16 points, had the same number of disposals as Richmond.

This got me thinking about the relationship between disposals and the final margin in AFL games, and whether there are any interesting things we can learn.

To date there have been 9905 V/AFL games with both disposal and score data available. Here’s a scatter plot comparing the disposal differential (i.e., the difference in the number of disposals recorded by the two teams) with the final margin.

![Disposal diff and margin fig](/img/content/posts/afl-differential-disposal-margin.png)

Looking at the figure above, as well as the underlying data, reveals some interesting findings. 

### You can have the same score or the same number of disposals – but not both

Of the 9905 games mentioned above, there have been 87 draws (0.9%) and 78 (0.8%) games where teams finished with an equal number of disposals. But **there has never been a draw where teams had the same number of disposals**. 

There have been two draws where one team had one disposal more than their opponent: [Fitzroy versus Collingwood (Round 8, 1980; Collingwood had the extra disposal)](https://afltables.com/afl/stats/games/1980/040619800517.html) and [Brisbane Lions versus Port Adelaide (Round 12, 1998; the Lions had the extra disposal)](https://afltables.com/afl/stats/games/1998/131919980614.html).

There have also been four games have seen teams finish with the same number of disposals and been separated by a single point – most recently in Round 7, 2022 [(Port Adelaide versus St Kilda)](https://afltables.com/afl/stats/games/2022/131520220430.html).

### Getting more of the ball doesn’t guarantee a win, and winning big doesn’t mean you’ve had all the ball

In the 9827 games where teams had a different number of disposals, **the team with more disposals won 7250 (73.8%) of games**, lost 2490 (25.3%), and drew 87 (0.9%). This shows that while getting your hands on the ball goes a long way to winning,  [disposal](https://www.lincolntracy.com/posts/disposal-eff-wins/) and scoring efficiency also matter. 

The biggest win in V/AFL history – [Fitzroy’s 190-point thrashing of Melbourne back in 1979](https://afltables.com/afl/stats/games/1979/061119790728.html) – saw the Lions have 129 more disposals than the Demons. 

But this is over 100 disposals less than the biggest disposal differential since disposals were recorded – an unbelievable **236** – when [Geelong beat West Coast by 99 points](https://afltables.com/afl/stats/games/2008/091820080830.html) in the final round of the 2008 home and away season. 

Every Geelong player recorded between 12 and 34 disposals (Tom Lonergan and Cameron Ling, respectively), while **only nine Eagles cracked double figures**. Dean Cox and Quinten Lynch were the most prolific ball-getters with 21 disposals each. 

On the other side of things, the **Brisbane Lions** hold the record for having the biggest disposal differential but still losing the game, when they had **133 more disposals but lost to the Gold Coast** in [Round 19, 2015](https://afltables.com/afl/stats/games/2015/192020150808.html), while **Essendon** have the biggest loss despite racking up more disposals, courtesy of their **108-point** loss to Hawthorn in [Round 12, 2016](https://afltables.com/afl/stats/games/2016/051020160610.html) where they had 11 more disposals.

### Finals are a strange beast

The largest margin in a game where teams had an equal number of disposals is **89 points**, when Richmond defeated Greater Western Sydney in the [2019 Grand Final](https://afltables.com/afl/stats/games/2019/142120190928.html). 

The largest disposal differential in a drawn game (**129**) also happened in a final – the [1990 qualifying final between Collingwood and West Coast](https://afltables.com/afl/stats/games/1990/041819900908.html). Things went a bit smoother for the Pies in the [replay](https://afltables.com/afl/stats/games/1990/041819900915.html), where they had 45 more disposals and won by 59 points the following week. 

Collingwood has played in two drawn Grand Finals (1977 and 2010). They had fewer disposals in both drawn Grand Finals (255-305 in 1977 and 326-338 in 2010), then again had fewer disposals in the Grand Final replay they lost (227-310 in a 27-point loss) but more disposals in the replay they won (379-326 in a 56-point win). 

--- 

*The timeframe of this stat is limited based on what data are freely/easily available and/or accessible. Please don’t hesitate to contact me if you spot any errors in what I have presented.* 
