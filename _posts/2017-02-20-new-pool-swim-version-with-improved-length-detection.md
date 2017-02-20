---
layout: inner
date: '2017-02-20 21:28 +0100'
ads: true
comments: true
published: true
title: New pool swim version with improved length detection
categories: apps
tags: garmin apps connectiq
lead_text: title
---
Today I have released v4.4 of Pool Swim app. There are no additional functions. This released is focused on applying a new filter to the heading signal coming from the compass, so that length detection should be more accurate. I have also done several improvements regarding memory management. Finally, I have temporarily removed the stroke counting feature. It will be back soon, with improved accuracy. 

Since a couple of versions, you can find a "debug" setting in the GC app in your smartphone. This setting enables recording of heading and acceleration data @10Hz. This setting will increase the size of the fit file about 10 times. But on the other hand, it can provide very useful data which I can use to fine tune the algorithms. 
Until that version, the only data source I had was the chart shown in Garmin Connect. While it provides a rough idea whether the algorithm is working fine, the granularity is just one second. 

Here you can see an example. This chart shows about 80 seconds of a swimming activity. The data series in orange color shows the heading with the filter I have been using until version 4.3. And the grey one, the new filter which is implemented in version 4.4. The new algorithm reduces better the oscillations.

<img src="{{site.baseurl}}/images/excel.png" width="50%">

I have introduced improvements in the memory management. And specially in the menu handling, both main menu and exit menu. Browsing the menus was consuming lot of memory. under circumstances, the app could run out of memory. I hope this won't be happening anymore. 

I have removed the stroke counting. It was not working very well. And it was consuming lot of memory because of some big arrays. Now that I can acquire data @10Hz, it should be much easier to fine tune the stroke counting algorithm. Until now I was just guesstimating. For this I need data! I would be very glad if some of you, especially those with better swimming skills, could provide a fit file (with the "debug" setting active).

Happy swimming!

Cheerio
