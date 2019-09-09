---
layout: post
title: 1000 Songs to listen before you Die!!!!
subtitle: Exploring 1000 Songs
tags: [songs,music,data visualisation]
---

I came across this [dataset](https://opendata.socrata.com/Fun/Top-1-000-Songs-To-Hear-Before-You-Die/ed74-c6ni) mentioned in the topic. I was interested to find out more about this dataset.
First things first. Even though the title is 1000 songs, it contains only a list of 994 songs. There goes the title in ashes.(pooof)
The songs are categorised by Artist, Year, Title and also spotify url(222 songs don’t have this url)

>The oldest song it has is from the year 1916 by title **“Jerusalem”** by artist “William Blake, Charles Hubert and Hastings Parry”.

The latest song is from the year 2008. Infact they are 19 songs from this year.

This led me to thinking how many songs are they are from each year.

![Songs by year](/img/songsbyyear.png)

**1968 has the maximum number of songs : 39**

Next, I wanted to see how the die to songs are segregated by Themes.
![song themes](/img/themes.png)

Almost all the seven themes are equally distributed but the “Party Songs” nudge ahead by a short margin.

Next stop, artists. There are 670 different artists for 994 songs. Let’s see which artist is has maximum songs in the listen before die list.
![Top artist](/img/topartist.png)

Bob Dylan is the top artist, followed not so close by “The Beatles”. Youngsters are no match for an oldie.

Interestingly, most of the artists have equal number of songs, why are the number of songs by an artist not random
Is Bob Dylan popular because of a specific theme ? Why is he so popular. Let’s see his songs by the themes.

![Bob Dylan song themes](/img/bobdylan.png)

Hmm.. My respect for Bob Dylan just touched a new peak. He is versatile, no wonder so many of his songs are in the die list. No surprises that “Heartbreaks” songs are his specialty.
I wanted to see if the type of songs to listen to have changed by decades. Are the 60’s top songs any different from 90’s. I thought 60’s were for discos and 90’s were for party songs.

Nope, 60’s was for love songs and but 90’s was for party and sex songs.

I cannot think of any more interesting things to do with this data. If you can think of any, let me know.

If interested, you can look at the workings on this from [here](https://github.com/yvishyst/songstolisten/blob/master/songstolisten.ipynb).
