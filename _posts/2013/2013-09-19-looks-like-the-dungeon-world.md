---
title: Looks like the Dungeon World
categories: Discussion
tags: ['crawler', 'agent', 'every', 'looks']
author: Sage LaTorra
link: https://plus.google.com/+SageLaTorra/posts/1LQ9hLqenwr
published: 2013-09-19T18:14:55.018Z
updated: 2013-09-19T18:14:55.018Z
imagelink: []
thumblinks: []
---

Looks like the Dungeon World Codex is down. We got DoS-ed by what appears to be some kind of weird crawler. A Mozilla/Windows user agent hit every link it could find at roughly half-second intervals viewing every single monster page.<br /><br />We don&#39;t have crawling blocked and haven&#39;t had a problem in the past, so I&#39;m thinking this is just some rogue agent. It&#39;s funny to imagine someone caring enough to DoS us on purpose, but I doubt that&#39;s the case.<br /><br />I&#39;m going to keep it down for a bit until either our quota resets or I can figure out what&#39;s up with this crawler.
<div id='comment z13oslqymwinzpzs122ndtna1lqncdyx404'>
  <h4><img src='{{site.baseurl}}//images/avatars/114058978089705547111_photo.jpg'> Matt Smith</h4>
      <p><cite>2013-09-19 19:14:18 (edited: 2013-09-19 19:14:18)</cite></p>
        <p>When it gets back up I&#39;ll be sure to post a new monster: &quot;The Crawler&quot; with the moves:<br />-Ruin everybody&#39;s fun<br />-Hint towards malicious intent<br />- Do the bidding of some Jag-weed with no life.</p>
</div>
        

<div id='comment z13oslqymwinzpzs122ndtna1lqncdyx404'>
  <h4><img src='{{site.baseurl}}//images/avatars/117415966179711277938_photo.jpg'> Sage LaTorra</h4>
      <p><cite>2013-09-19 19:18:53 (edited: 2013-09-19 19:18:53)</cite></p>
        <p>Just to be clear here: the issue is not that the system went down, but that in order to serve out that many requests we&#39;d have to pay money, which we don&#39;t want to do.</p>
</div>
        

<div id='comment z13oslqymwinzpzs122ndtna1lqncdyx404'>
  <h4><img src='{{site.baseurl}}//images/avatars/100870561605092848478_photo.jpg'> Adam “Hegz” Fairbrother</h4>
      <p><cite>2013-09-19 19:40:41 (edited: 2013-09-19 19:40:41)</cite></p>
        <p>How many entries are in the codex currently?</p>
</div>
        

<div id='comment z13oslqymwinzpzs122ndtna1lqncdyx404'>
  <h4><img src='{{site.baseurl}}//images/avatars/101025241405784788544_photo.jpg'> Michael Prescott</h4>
      <p><cite>2013-09-19 20:00:54 (edited: 2013-09-19 20:00:54)</cite></p>
        <p>Sounds like someone scraping it?</p>
</div>
        

<div id='comment z13oslqymwinzpzs122ndtna1lqncdyx404'>
  <h4><img src='{{site.baseurl}}//images/avatars/117415966179711277938_photo.jpg'> Sage LaTorra</h4>
      <p><cite>2013-09-19 20:32:55 (edited: 2013-09-19 20:32:55)</cite></p>
        <p>Scraping sounds likely, yeah. Or indexing. <br /><br />I can&#39;t get an easy count right now since we&#39;re over the data store read limit (which apparently applies to the admin console too), but it looks like well over 900. I&#39;d guess 1,000+.</p>
</div>
        

<div id='comment z13oslqymwinzpzs122ndtna1lqncdyx404'>
  <h4><img src='{{site.baseurl}}//images/avatars/115725920587018246269_photo.jpg'> Konrad Zielinski</h4>
      <p><cite>2013-09-20 00:51:29 (edited: 2013-09-20 00:51:29)</cite></p>
        <p>Hmm, Must have been the Sparkly Vampire I added Yesterday.</p>
</div>
        

<div id='comment z13oslqymwinzpzs122ndtna1lqncdyx404'>
  <h4><img src='{{site.baseurl}}//images/avatars/100870561605092848478_photo.jpg'> Adam “Hegz” Fairbrother</h4>
      <p><cite>2013-09-20 06:30:39 (edited: 2013-09-20 06:30:39)</cite></p>
        <p>At one point I was thinking about writing a scraper, to compile all the monsters down into one big PDF file.  I will cease thinking that now.</p>
</div>
        

<div id='comment z13oslqymwinzpzs122ndtna1lqncdyx404'>
  <h4><img src='{{site.baseurl}}//images/avatars/104376161086076258384_photo.jpg'> Robert Kern</h4>
      <p><cite>2013-09-20 09:38:25 (edited: 2013-09-20 09:38:25)</cite></p>
        <p>It looks like you are missing a robots.txt. That will be enough to wave off any well-intentioned crawler.<br /><br /><a href="http://www.robotstxt.org/" class="ot-anchor">http://www.robotstxt.org/</a><br /><br />Providing a compressed bulk dump would channel the bandwidth of those that want to scrape and reuse the content.</p>
</div>
        

<div id='comment z13oslqymwinzpzs122ndtna1lqncdyx404'>
  <h4><img src='{{site.baseurl}}//images/avatars/117415966179711277938_photo.jpg'> Sage LaTorra</h4>
      <p><cite>2013-09-20 15:22:29 (edited: 2013-09-20 15:22:29)</cite></p>
        <p>The well intentioned crawlers aren&#39;t the problem. I checked the logs, the google and bing crawlers are no problem.</p>
</div>
        

<div id='comment z13oslqymwinzpzs122ndtna1lqncdyx404'>
  <h4><img src='{{site.baseurl}}//images/avatars/114058978089705547111_photo.jpg'> Matt Smith</h4>
      <p><cite>2013-09-21 02:50:40 (edited: 2013-09-21 02:50:40)</cite></p>
        <p>I knew it! No, I&#39;ve been lost since the first post.</p>
</div>
        