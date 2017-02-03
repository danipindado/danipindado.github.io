---
layout: inner
title: Pool Swim app v4.2 released
date: 'Thu Jan 26 2017 01:00:00 GMT+0100 (Central Europe Standard Time)'
categories: apps
tags: apps garmin connectiq
comments: true
ads: true
lead_text: New UI for FR630
published: true
---
Since version 2.0 I have been supporting FR630. 

Even though supporting it in ConnectIQ is pretty straightforward, I was a little bit reluctant to support it, because of the touch screen. 
I had [read](https://www.dcrainmaker.com/2015/12/garmin-forerunner-630-depth-review.html#backlight-touchscreen-display), that the touch screen does not deal very well with water. I don't own a FR630 so I wouldn't be able to test the app on it. 
Finally I decided to support it, and wait for users to report. 

Within ConnectIQ developers cannot figure out how many people with a certain watch are using their apps. I assumed that not many people with a FR630 were using the app, because for the first months nobody came back to me. 

A couple of weeks ago a spanish user contacted me. As expected, the behavior of the watch under water was not ideal. Dealing with the screen was driving him nuts. 
He has helped me to figure out what the most convenient key combination is. The FR630 has just 4 buttons (vs FR230/FR235, which have 5). To make things worst, the function of the buttons is slightly different. In FR23x lap and back functions are mapped to just one button, while in the FR630 garmin decided to split them in two different buttons.

We have come up with this solution. I hope [FR630](http://a-fwd.com/es=danpinblo01-21&it=danpinblo03-21&fr=blodedanpin0d-21&de=blodedanpi0d0-21&uk=danpinblo-21&com=danpinblo-21&e=RR3Mjl7n30G6nQDUx3AT7&asin-com=B016VC1PTU) users will find it convenient:

![swimming-pool-image](/images/FR630.png){:class="img-responsive"}


+ button 1(backlight) has the typical behaviour
+ button 2(back) leaves the app if the activity is stopped. But also toggles between data screens 1 and 2 during an activity.
+ button 3(select) starts/stops the activity
+ button 4(lap) trigers an interval within an actity. But also enables main menu if activity is paused.
+ Touch screen is usually locked. It will only get enabled to handle menus (main menu or save/discard menu). Here you will use the swipe & tap gestures to deal with the different options. This is something you will not typically do in the water.

The [user guide](https://danipindado.github.io/downloads/pool_swim_user_guide.pdf) has been updated.

[This](https://danipindado.github.io/Garmin-ConnectIQ-pool-swim-app.html) is the original post where you can find more information on the app.

Other than that, not many new changes in this version. There are a couple of changes to improve how pace charts are displayed in [Sport Tracks](www.sporttracks.mobi). Thanks to Sport Tracks guys for their support.

I have been collecting accelerometer data. So I will begin to work in autopause detection.  

Feel free to use the comment section below to ask any questions. 
Remember that you don't need to create a Disqus account in order to comment: just write your comment, click on the "Name" field below, and the option "I'd rather post as a guest" will pop up.

Last, but not least, I offer ads and affiliate links on the site. These links help me get more gadgets that I can show you here :) . And remember that you will still pay the same price for the product. 

Cheerio!
