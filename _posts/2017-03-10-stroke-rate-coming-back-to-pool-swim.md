---
layout: inner
date: '2017-03-10 21:33 +0100'
ads: true
comments: true
lead_text: title
published: false
title: Stroke rate coming back to Pool Swim
---
Today I am releasing v4.5 of Pool Swim. 

The biggest change is stroke rate. Maybe you remember I removed it from v4.4. Or actually, I stopped calculating it because it was not very accurate. 

Thanks to the support of one user who sent me fit file with debug information activated, I have come up with a band pass filter for the acceleration which should hopefully provide much more accurate values. 

Here you can see a chart showing the data read by the accelerometer (red) and the same signal after applying the digital filter. Most of the noise is gone and it attenuates the effect of gravity. the result is a quite smooth curve oscilating around 0. 

<img src="{{site.baseurl}}/images/2017-03-10_21h43_42.png" width="100%">

Of course behaviour might change from swimmer to swimmer. The algorithm has been fine tuned with just that one sample, plus some testing that I have performed in my living room :)

It is optimized for crawl (mainly because this is the swimming style the user swam...). If you usually swim in a different style and stroke rate is not working accurately, maybe you can create a FIT file with debug info and share it with me. 

Other than that, I have fixed a bug which in certain circumstances might trigger two wrong lengths at the beginning of the activity. 

And I have done a very minor change to the length detection algorithm, to make it even more robust. 


