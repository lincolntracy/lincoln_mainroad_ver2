---
title: "My First Useless AFL Stat"
date: 2021-08-22
#sidebar: false
categories:
 - "Blog"
tags:
 - "R"
 - "AFL" 
 - "Stats"
 - "Sports"
---

<!--more-->

In my day job as a Research Fellow in the School of Public Health and Preventive Medicine at Monash University I work with data from the [Burns Registry of Australia and New Zealand](https://www.monash.edu/medicine/sphpm/branz), or the BRANZ for short. The BRANZ is a clinical quality registry that captures data about patients with burn injuries admitted to hospitals with specialist burn services in Australia and New Zealand. If you're interested, you can read more about my research [here](https://www.lincolntracy.com/research/). 

One of the things I really enjoy about my job is that I get to use BRANZ data --- upwards of 30,000 admissions over an 11-year period --- to investigate injury trends and answer interesting research questions. The BRANZ releases an annual report that reflects on admissions data from the last year. These reports can be downloaded for free via [reports page of the BRANZ website](https://www.monash.edu/medicine/sphpm/branz/publications-and-reports#tabs__1410728-02). 

Outside of my work for Monash, I'm a big fan of Australian Rules Football (AFL). AFL fans might be aware of [Useless AFL Stats](https://www.facebook.com/uselessaflstats) and Twitter's favourite sports statistician, [Swamp](https://twitter.com/sirswampthing). I was keen to find a way to be like Aaron, Liam, Rohan, and Bill --- the team behind Useless AFL Stats --- and Swamp and get to combine my interest in sports with my skills in handling large data sets. 

Recently that I found out how I could [build my own Useless AFL Stats](http://www.uselessaflstats.com.au/build-your-own/). I've had a lot of fun over the last few weeks getting into the swing of things. Now, without further ado, I'm ready to share my first foray into the world of useless AFL stats. 

## Which team playing away on a Friday night in Round 20 won their game with the most accurate scoreline?

Round 20 of the 2021 AFL Premiership season kicked off with Carlton playing St Kilda under the roof at Marvel Stadium. After a tight first quarter where young Saints forward Max King kicked three goals, Carlton eventually ran out 31 point winners. All the official highlights can be seen [here](https://www.afl.com.au/video/655647/highlights-st-kilda-v-carlton?videoId=655647&modal=true&type=video&publishFrom=1627649954001). Carlton finished the night with 18 goals and four behinds. That's pretty good for Carlton, given the season we'd had until that point. To make it more impressive, 18.4 has only been kicked six times, including that game, at the time of writing. 

It got me thinking about how accurate teams had been in certain games. Disappointing losses the week before --- North Melbourne, 39 points --- and in the weeks after the St Kilda game --- Gold Coast (19 points), Port Adelaide (95 points), and Greater Western Sydney (14 points) --- also got me thinking about if I could find a stat that I would be able to look back on fondly over the long off season. So, I went searching until I found a useless stat that fit the bill.

The table below displays the 12 games where the team playing away on a Friday night in Round 20 won the match, sorted by how accurate each team was in terms of their goalkicking. If you hadn't figured out where this was going yet, **Carlton's performance from earlier this year** tops the list.

<center>

| Year | Team           | Opponent        | Venue            | Goals | Behinds | Accuracy |
| :--: | :------------- | :-------------- | :--------------- |:----: | :-----: | :------: |
| 2021 | Carlton        | St Kilda        | Marvel Stadium   | 18    | 4       | 81.8%    |
| 2001 | Adelaide       | North Melbourne | Colonial Stadium | 25    | 12      | 67.6%    |
| 2008 | Collingwood    | Port Adelaide   | Football Park    | 16    | 10      | 61.5%    |
| 2017 | Sydney         | Geelong         | Simonds Stadium  | 16    | 11      | 59.3%    |
| 1993 | Fitzroy        | Sydney          | SCG              | 17    | 12      | 58.6%    |
| 2010 | Collingwood    | Essendon        | MCG              | 24    | 18      | 57.1%    |
| 2000 | Essendon       | Carlton         | MCG              | 16    | 13      | 55.2%    |
| 1988 | Brisbane Bears | Richmond        | MCG              | 14    | 16      | 46.7%    | 
| 2009 | Adelaide       | Hawthorn        | MCG              | 13    | 16      | 44.8%    |
| 1999 | Essendon       | Collingwood     | MCG              | 12    | 15      | 44.4%    |
| 2013 | Hawthorn       | St Kilda        | Etihad Stadium   | 14    | 18      | 43.8%    |
| 2006 | Collingwood    | Port Adelaide   | Football Park    | 12    | 17      | 41.1%    |  

</center>

*Note: Marvel Stadium, Colonial Stadium, and Etihad Stadium all refer to the Docklands Stadium in Melbourne. Simonds Stadium refers to Kardinia Park in Geelong. Naming rights sponsors to these grounds have changed over time.*

If graphs are more your thing, then the same data can be viusalised below in a bar chart.

![Graphical representation of First Useless AFL Stat](/img/content/posts/first-useless-afl-stat/round20_labelled.png)

*Some other interesting observations:*

- Two of the now defunct AFL teams (Fiztory and the Brisbane Bears) appear on this list.
- Collingwood don't mind playing away on a Friday night, appearing three times as winners.
- Five teams --- Carlton, Collingwood, Sydney, Essendon, and Hawthorn --- appear as both winning and losing teams.
- The team playing away on Friday night in Round 20 has won three years in a row on two separate occasions --- 1999, 2000, and 2001 & 2009, 2009, & 2010. 
- Five of the 12 occurances involve two Victorian teams playing in Melbourne, so if you really wanted to you could probably debate the extent to how "away" these games really are.

Keep an eye out for more stats!

---

*This post would not have been made possible without the team from Useless AFL Stats, particularly their head data guy Liam Crowhurst ([@crow_data_sci](https://twitter.com/crow_data_sci) on Twitter). Without the fantastic introductory posts (check out parts [one](https://www.crowdatascience.com/introduction-afl-analytics-data-r/) and [two](https://www.crowdatascience.com/afl-analytics-data-r-part-2/)) on his website I never would have learned how to easily access [AFL Tables](https://afltables.com/afl/afl_index.html) data via the `fitzRoy` package in R.*

*If you want to gain some experience in coding using relevant, real-world data, I definitely recommend checking out Liam's introductory posts and trying to make your own stats, useless or otherwise.* 

---