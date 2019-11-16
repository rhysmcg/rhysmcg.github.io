---
layout: post
title:  "Visualise your location history as a heatmap in Google Maps API!"
author: rhys
categories: [ mapping ]
image: "https://raw.githubusercontent.com/rhysmcg/heatmaphistory/master/google%20Maps%20Test.png"
---
Upon checking my old blogs, I realised that Google Fusion Tables is going to be decommissioned in December of 2019. A difficult thing about using web services is that they aren't very permanent! As  a result, I thought I’d relook at an old project about displaying your Location History as a heat map but this time convert it to use the Google Maps API instead.

During my holiday to Korea and Japan I enabled "Google Location History" which is now called [“Google Timeline”](https://www.google.com/maps/timeline) so that I could visually see where I was going during my trip. When I returned home, I downloaded the data and using a python script I made to analyse and try to remove duplicates (locations less than 5 kms to each other) and format it to a CSV file. I was able to import it to Google Fusion Tables and get a heatmap automatically. 

I think the most interesting part is seeing the really strong splotch from Tachikawa to Yotsuya in Tokyo, (my daily commute) and that little splotch at the North Korean border when I took the tour to Panmunjom!

Although it’s a little intrusive for privacy, I think visualising trips this way is fascinating! You may download KML files of your own timeline and try to format it to the Google Maps API yourself!

<iframe src="https://rhysmcg.github.io/heatmaphistory/" width="100%" height="480"></iframe>

Download: <a href="https://github.com/rhysmcg/heatmaphistory">https://github.com/rhysmcg/heatmaphistory</a>