---
title: "Calendar Scores"
date: 2021-10-22T09:18:34+11:00
categories:
 - "Blog"
tags:
 - "R"
 - "AFL" 
 - "Stats"
 - "Sports"
---

<!--more-->

When we talk about dates in Australia, we most commonly use the *day-month-year* format. For example, if we wrote today’s date out in full it would be 22 October 2021. If we were only using numeric values, it would be 22/10/2021. Dates can sometimes be written in a slightly different format---2021-10-22--- but this simply reverses the *day-month-year* format to *year-month-day*. The main point is that the month is in the middle of dates in Australia (unlike the format used by the United States, which have the month first e.g., 9/11 for September 11).

Scores in AFL games are also reported in a specific format or notation: *goals-behinds-total score*. This week I was curious to see **how many times a team kicked a score (in terms of *goals-behinds*) that matched the date (*day-month*) the game was played on**. There’s no real reason behind this curiosity---I think I just liked the symmetry of it all. 

This first question led to a series of other questions about these games. I’ve tried to present these questions (and my findings) in a somewhat logical order in the remainder of the post.

### How many times has this occurred?

There have been **41 games in V/AFL history where a team kicked a score that matched the date**. The full list of these matches can be seen [here](/files/content/posts/calendar-scores/Calendar-Score-List.pdf).

### When was the first time this occurred?

The first of these 41 games occurred on **June 3, 1899**, when Geelong (3.10.28) defeated Essendon (3.6.24) in Round 5. 

### When was the most recent time this occurred?

The most recent occasion where a team score matched the date happened **earlier this year** (i.e., 2021), with Melbourne (12.14.86) defeating Port Adelaide (8.7.55) on July 8 (Round 17). 

### In how many seasons have games like this occurred?

**Thirty-five seasons** have had at least one game where a team kicks a score that matches the calendar date.

### Which season has the most games like this?

In addition to having the first game where a team score matches the calendar date, the 1899 season also holds the record for the **most times this occurs in a year, with three**. On the same day Geelong defeated Essendon, Melbourne (4.11.35) defeated Fitzroy (3.6.24). Then eight weeks later in Round 13, Essendon (5.8.38) defeated Melbourne (3.7.28) on August 5. 

Only four seasons have had two games where a team score matches the calendar date---1908, 1925, 1976, and 2020. Thirty other seasons have had one game where a team score matches the calendar date.

### What’s the most common date that these games have been played on?

**August 7** takes the cake here, with **four games featuring a team that kicks 7.8** (1943, two in 1976, and one in 1982). August 12th is next on the list (12.8; three games), while May 8 (8.5), May 9 (9.5), June 2 (2.6), June 3 (3.6), June 6 (6.6), June 11 (11.6), June 12 (12.6), July 4 (4.7), July 11 (11.7), and August 8 (8.8) have all occurred twice. The remaining 14 games have occurred on unique dates. 

### How many teams have played in a game where a score matches the calendar date?

**Twenty** of the 21 teams in V/AFL history have featured in a game where a team score matched the calendar date. The only team not to play in a game where a team score matched the calendar date is **Greater Western Sydney**. Even University, who played from 1908 to 1914, managed to appear in one game ([versus Essendon, in 1913](https://afltables.com/afl/stats/games/1913/051719130809.html))!

### Which team has played in the most games where a score matches the calendar date?

**St Kilda** have played in the greatest number of these games, with **nine** appearances. The Saints are followed closely by **Carlton** and **Geelong**, who have each played in **eight** such games. 

### Which team has the best win percentage in games where a score matches the calendar date?

The table below displays the number of calendar score games each team has played and the number of wins that have come from these appearances.

<center>

| Team             | Played | Wins | Win % |
| :--------------- | :----: | :--: | :---: |
| Adelaide         | 4      | 3    | 75    |
| Brisbane Bears   | 1      | 0    | 0     |
| Brisbane Lions   | 1      | 1    | 100   |
| Carlton          | 8      | 4    | 50    |
| Collingwood      | 4      | 2    | 50    |
| Essendon         | 6      | 4    | 75    |
| Fitzroy          | 4      | 1    | 25    |
| Fremantle        | 5      | 1    | 20    |
| Geelong          | 8      | 7    | 87.5  |
| Gold Coast       | 1      | 0    | 0     |
| Hawthorn         | 2      | 2    | 100   |
| Melbourne        | 7      | 4    | 57.1  |
| North Melbourne  | 5      | 3    | 60    |
| Port Adelaide    | 1      | 0    | 0     |
| Richmond         | 4      | 3    | 75    |
| St Kilda         | 9      | 3    | 33.3  |
| Sydney           | 5      | 1    | 20    |
| University       | 1      | 0    | 0     |
| West Coast       | 2      | 1    | 50    |
| Western Bulldogs | 4      | 1    | 25    |

</center>

From this table, we can see that the Lions and the Hawks have a perfect record in these games. However, their win percentages are somewhat inflated as they have only played in one and two of these games respectively. Realistically, **Geelong** has the best record in these games, winning **seven of their eight games** for an 87.5% win rate.

### How many teams have kicked a score that matches the calendar date?

**Sixteen** different teams have kicked a score that matches the calendar date across the 41 games where this has occurred. 

The teams not on have kicked a score that matches the calendar date are the Brisbane Bears, Geelong, Greater Western Sydney (by virtue of not playing in a game where either team has not kicked a score that matches the calendar date), Hawthorn, and University. I find it interesting that Geelong has played in eight games where their opponent has kicked a score that matches the calendar date! 

### How many teams have kicked a score that matches the calendar date and won the game?

Only **eight** of the 41 games I’ve been looking at today have been won by the team that kicks the calendar date score. Only two of these games have occurred in the last century. These eight games are:
- Essendon (5.8.38) defeated Melbourne (3.7.25): Round 13, 5/08/1899
- Melbourne (8.8.56) defeated Carlton (5.11.41): Round 14, 8/08/1903
- South Melbourne (12.5.77) defeated Collingwood (8.9.57): Round 2, 12/05/1906
- St Kilda (6.6.42) defeated Geelong (5.9.36): Round 6, 6/06/1908
- Essendon (9.8.62) defeated University (8.12.60): Round 16, 9/08/1913
- Richmond (14.8.92) defeated South Melbourne (9.7.61): Round 15, 14/08/1920
- Fremantle (17.8.110) defeated Hawthorn (13.13.91): Round 21, 17/08/2014
- Carlton (8.9.57) defeated Sydney (8.4.52): Round 16, 8/09/2020

Be on the lookout for more scores that match the calendar date next season!

---

*As always, apologies to anyone who has already presented these stats.*