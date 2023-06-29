---
title: The 🅱ump
author: B Cochrane
date: '2023-04-27'
slug: the-bump
categories:
  - R
tags:
  - Foopy
  - R
  - Analysis
---




Bans for tackles and bumps are the talk of the town, causing outrage from fantasy football coaches and old bogans alike.

I have created a Dataset of AFL Bans **(DAB)** for use in analysis.

From Round 1 to Round 6 we have seen 18 players banned for offences ranging from bumps, strikes to tackles.


<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-2-1.png" width="672" />


The majority of bans coming from tackles and bumps, with a minority from strikes


<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-3-1.png" width="672" />



Clustering of midfielders, looking like strong correlation between number of tackles and potential to be banned for tackling.
Forwards, and defenders seem to be dominating the bump category, interestingly a combination of small and big men too.
The people who get banned for tackling seem to be generally experienced enough players (i.e. it's not someone who doesn't know what they're doing, instead maybe do it a bit exuberantly)
Making this a ratio of # of tackles to length of ban looks like this:


<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-4-1.png" width="672" />


Will Day plummets down the ranks after his 2 week ban

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-5-1.png" width="672" />

Strong growth in tackle bans in the recent rounds - maybe players switching from the bump to tackle given the early bans given to bumpers in Rounds 1:3.

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-6-1.png" width="672" />



Nice and simple one here, less average ban duration if you choose to tackle and it goes wrong, vs. if you choose to bump and it goes wrong.
Also, just don't strike people maybe?
Of the 536 players who have played at least 1 game in 2023, 17 of them have yet to lay a tackle, will be interesting to see how this dataset looks at the end of the season.

Enjoy,

Ben
