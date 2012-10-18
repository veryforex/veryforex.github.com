---
layout: default
title: Frequently asked questions
name: faq
category: cot
---

FAQ
=================================

Q. How to install the indicator?
----------------------------------
A. Copy all the ex4 file to "your MetaTraderPath\experts\indicators", your MetaTraderPath is where your broker platform is installed., e.g. "C:\Program Files\MetaTrader 4\experts\indicators"
   
> copy the data file to "your MetaTraderPath\experts\files", e.g. "C:\Program Files\MetaTrader 4\experts\files"
   
> see the installation and user guide for details.


Q. When will I get the data?
----------------------------------
A. CFTC publishes the Commitments of Traders Report each week. the report is usually released on Friday afternoon, Federal holidays may delay release by one day, ForexCake.com will deliver the updated data to you shortly afterwards.

The following link is a tentative schedule of releases through 2012: [release schedule](/cot/schedule.html).


Q. How to use the data receive from VeryForex.com?
----------------------------------
A. save the attached file called COT_NEW.dat from the email, copy it to the folder of "your MetaTraderPath\experts\files", your MetaTraderPath is where your broker platform is installed. e.g, "C:\Program Files\MetaTrader 4\experts\files"

If you are prompted to replace the file, then select YES to replace the existing file.

Make sure you have install our indicators, then restart your MetaTrader 4.


Q. What's the meaning of VeryForex COT indiators?
----------------------------------
A. There are 5 COT indiators:

- COT positions and open interest:
	- *Open position of this Tuesday, correspones with CFTC original position data*
- COT position changes: 
	- *Open position changes from last Tuesday*
- COT net positions: 
	- *The net value of open position (long position - short position)*
- COT net positions index: 
	- *Show net position as index, index value of 100 to the maximum net position, 0 to the minimum net position*
- COT long-short ratio:
	- *Show whether traders are longing or shorting, the ratio of long position relative to all positions*


Q. What futures the COT indicator support?
----------------------------------
A. Current version support most major currencies and commodities: AUD, CAD, CHF, EUR, GBP, JPN, MXN, NZD, USD, XAG, XAU.


Q. Does the indicators work with demo accounts?
----------------------------------
A. Yes. It will work with all accounts - demo and live - and with all Metatrader4 brokers.


<h4>Q. Where can I download the COT data indicators for MetaTrader 4?</h4>
A. Visit our <a href='../cot/download.htm'>downloads page here</a>, you will also find instructions on how to install it.
<br/><br/>

Q. How to distinguish the different traders?
----------------------------------
A. We use different color to represent different traders' data, by default:
> The **Red** line represents the non-Commercial traders - (or large speculators, most valuable!)  
> The **Green** line represents the Commercial Traders (or hedgers).  
> The **Blue** line represents the Non-reportable (or small traders)  
> The **Black** line represents the total Open Interest.    
you can change them as your favor.

put mouse on the data line, the MetaTrader 4 platform would also show which kind of trader this line belongs to.


Q. I get an alert error. How to deal with it?
----------------------------------
A. That is when we can not open the COT_HIST.dat or COT_NEW.dat file. Make sure that you have placed COT_HIST.dat and COT_NEW.dat file in the right directory "your MetaTraderPath\experts\files" and you do not have another program opens with the file - e.g. any editor.


Q. MT4 always crash when launch the COT indicator.
----------------------------------
A. It may happen when the MetaTrader4 build version older than our COT indicator version, your Metatrader4 version must newer than  V4.220, please liveupdate your MetaTrader4.


Q. What's the best timeframe that the chart would use?
----------------------------------
A. The Indicators will work on charts with any periods - even the 1 minute chart! The best timeframe to use these data is weekly chart(also daily chart), as the data is updated weekly.<br>
Note: all the data is weekly data, e.g. when you show 1 minute or 1 week chart, our COT data just show the COT data of this week or the first week of this month.


Q. How to unsubscribe?
----------------------------------
A. We hope that you have no reason to unsubscribe. If you are unsatisfied with our service, please contact us so that we can do our best to prive our sevice better.

Unsubcription is very simple: log into your PayPal and click the unsubscribe link according paypal prompt message. 

Note: your subscription will end as soon as we receive notice from PayPal that you have ended your subscription.


Q. Why my MetaTrader crashed?
----------------------------------
A. The most possible reason is verion compatiblity, please check your MT4 Build version by clicking "Help" -> "About", the pop-up dialog would show your MT4 version, make sure you have downloaded same version indicators with MT4 build version, sometimes using previous version indicators may work, however we don't guarantee that, we suggest always updating your MetaTrader4 and COT indictors to latest version.

