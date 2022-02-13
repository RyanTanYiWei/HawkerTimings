# Hawker Centres: Morning Markets or Dinner Spots?

![Visual](https://github.com/RyanTanYiWei/HawkerTimings/blob/main/Hawker%20Centres.JPG)

[Blogpost](https://ryantanyiwei.wixsite.com/blog/hawker-centres-time)

<b>Description</b>

Months back, a student of mine asked me an earnest question - "What do you think makes certain hawker centres work like a morning market or a supper spot?" I gave a fair response then, along the lines of how hawker centres tend to function for the neighbourhood/district it is situated in. This particular topic has been on my mind for quite a while and I always wanted to know if there are more complex factors that determine this time-sensitive function - like the relative proximity of hawker centres are to each other. Perhaps residents in this neighbourhood find more affinity in this market for morning shopping/ breakfasts because the other adjacent hawker centres tend to cater more for the office workers during the afternoon crowd? Even after I've drafted this visualization, I guess the answer still isn't as obvious, but it certainly does help me think deeper about it.

<b>What the Code does</b>

1) Inputs NEA's KML data on Locations of Hawker Centres
2) Scrapes Popular Times on Google Maps using JosiahParry/populartimes package
3) Identify which Hawker Centre queries do not have Popular Times
4) Find the Mode of the top Popular Times in the week to find the "Peak Timing"
5) Export the information of "Peak Timing" onto a Voronoi Map (created beforehand on QGIS)

++QGIS project file to visualize it
