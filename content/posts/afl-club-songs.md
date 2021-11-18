---
title: "AFL Club Songs"
date: 2021-11-19T09:32:03+11:00
categories:
 - "Blog"
tags:
 - "R"
 - "AFL" 
 - "Stats"
 - "Sports"
---

<!--more-->

Every club in the AFL has a team song that is played when the team runs out on the field before the game and after the game, if the team wins. Wikipedia has a nice [summary of all the team songs](https://en.wikipedia.org/wiki/List_of_Australian_Football_League_team_songs), including notes about their history. 

Some club songs are good, like the Russian folk song inspired *There’s a Big Big Sound* of the Greater Western Sydney Giants. Written by Harry Angus of The Cat Empire, parodies (or memes) featuring the song were everywhere in September 2019 when the Giants made their first Grand Final. Here’s [10 of the best GWS song memes](https://www.afl.com.au/news/124630/theres-a-big-big-sound-the-top-10-gws-song-memes), according to the official AFL website. 

Other club songs are not as good. Birds of Tokyo added versus to, but took a some shine off, *We’re Flying High* (club song of the West Coast Eagles) when the club recorded a new version in February 2020. Listen to the [old](https://www.youtube.com/watch?v=rGBxLtHgNfw) and [new](https://www.youtube.com/watch?v=ioenqyOgbGo) versions and judge for yourself. 

*We Are the Suns of the Gold Coast Sky* is another example of a less-than ideal club song. In fact, the best thing about Gold Coast team song is when a staff member had to hold up the words to said song after the Suns first win (against Port Adelaide in Round 5, 2011).

![Gold Coast](/img/content/posts/afl-club-songs/gold_coast_song.jpg)

*Source: https://www.aflplayers.com.au/news-feed/stories/connection-community-and-continuity-the-growth-of-gold-coast*

But possibly the most “unique” performance of AFL club songs was given by Mike Brady & The Music Men (including Rex Hunt, Jim Stynes, Tony Liberatore, Sam Newman, and Lou Richards) at the AFL Centenary Ball back in 1996. The full video is available on [YouTube](https://www.youtube.com/watch?v=EicgMbM9OqY). I highly recommend setting aside 10 minutes to watch the full clip---just when you think it can’t get any more strange, awkward, or just plain nuts, it does.

One thing I was curious about this week was how good each song is at identifying who the respective team is, what colours they wear, and where they are from. The Gold Coast song does this surprisingly well on this regard:

> “We are the **Suns** of the **Gold Coast** sky, we are one in the **red, gold, and blue**”

Just **four of the 18 teams mention all three aspects of the club identity in their song**. Carlton admittedly gets a leg up here, as the mascot/moniker is the same as the club colours---but I’ll allow it. Ten teams mention two of the three aspects, while the remaining four clubs only mention one aspect each. 

Here’s the complete Venn diagram for the three aspects of club identity mentioned in their respective songs---I find it interesting that no club mentions their colours and location, but not the mascot. Perhaps the Tasmanian team will fill this gap if they are ever awarded a licence?

![Venn diagram](/img/content/posts/afl-club-songs/song_venn.png)

I was also curious to look at the most common words across AFL club songs. To do this, I transcribed the lyrics for all the club songs into a text file, imported them into the R statistical environment, and started [making word clouds](http://www.sthda.com/english/wiki/text-mining-and-word-cloud-fundamentals-in-r-5-simple-steps-you-should-know).

Based on the raw data, “the” is the most common word---appearing a total of 218 times. 

![Word cloud 1](/img/content/posts/afl-club-songs/wordcloud_01_cropped.png)

But this isn’t very interesting, as ‘stopwords’ like “the” or “we” are so common we can’t extract any useful information from them. Let’s remove these stopwords and try again.

Things look much better after removing stopwords---“old” now tops the list with 24 mentions, followed by “team” (18), “mighty” (17), “will” (17), and “win” (17).

![Word cloud 2](/img/content/posts/afl-club-songs/wordcloud_02_cropped.png)

Eight clubs have “old” in their song lyrics, but the Carlton fans sing “old” more than any other supporter base.

| Club            | Number of times "old" appears in song |
| :-------------- | :-----------------------------------: |
| Brisbane Lions  | 2                                     |
| Carlton         | 6                                     |
| Collingwood     | 4                                     |
| Essendon        | 2                                     |
| Fremantle       | 4                                     |
| Melbourne       | 2                                     |
| North Melbourne | 2                                     |
| Richmond        | 2                                     |

However, the data I have used inflates the number of times certain words appear. For most club songs (14 by my count), the same refrain is repeated twice---usually before and after an instrumental solo. Take the St Kilda club song, for example:

> “Oh when the Saints… go marching in… Oh when the Saints go marching in… Oh how I want to be with St Kilda… when the Saints go marching in”

The short refrain is sung, some horns play, and then the short refrain is repeated. Therefore, technically Saints is used six times throughout the song.

The clubs that differ are Adelaide, Fremantle, Port Adelaide, and West Coast. These clubs don’t go completely off on their own path (like *[Dare to Beat the Bear](https://www.youtube.com/watch?v=0LTDRCOuOwI)*), but do feature at least one verse before heading back to the main refrain. 

My personal favourite would have to be the middle section of the Fremantle song:

> “We’re the rollers, we’re the rockers. We’re the mighty Freo dockers. We’re gonna roll them and we’ll rock em. We’re going to send them to the bottom. And if they get up, we’ll do it again the dockers stop at nothing, nothing.”

What’s your most/least favourite club song? Or what lyric does your head in? I’m keen to hear your thoughts. 

--- 

*As always, I apologise to anyone who has already looked at these stats.*