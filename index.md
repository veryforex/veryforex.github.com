---
layout: default
title: What's VeryForex indicators and COT data
name: index
category: category
---

What's VeryForex Indicators
=================================
VeryForex collect, reorganize, comment, optimize popular indicators, and also archive them, here, we can easy to achieve readable, optimized indicators.

What's up
=================================
<ul>
{% for post in site.posts limit:5 %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

What's COT data
=================================

Volume indicator is a very important indicator to confirm the trend, break, reverse, however the "Volume" indicator of MetaTrader 4 is not "real volume" indicator, it is just the tick volume of each interval (e.g. the number of ticks during the 30-minute period).

Commitments of Traders(COT) data from Commodity Futures Trading Commission (CFTC) can substitute the "Volume" indicator, as it provide the position and open interest information! It's very cool, though CFTC publishs the report once each week, and the data has a delay of three days. 


What's VeryForex COT Data Service
=================================

VeryForex.com provide a free COT indicator to show and anylyze the COT data on your MetaTrader 4 platform, [download](/cot/download.html) COT indicators and history COT data right now!
For the subscription user, we bring you weekly updated COT dat via Email according to the CFTC [release schedule](/cot/schedule.html).


