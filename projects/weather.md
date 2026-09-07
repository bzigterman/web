---
layout: page
title: Weather
permalink: /projects/weather/
imageurl: https://bzigterman.com/plots/temp_history.png
webappicon: /weather.png
---

## Champaign–Urbana Forecast

<p class="updated_time"> Latest data: 01:08 AM CT, September 07</p>

<picture>
  <source srcset="{{ site.baseurl }}/plots/weather_2026-09-07_0608.png"
          media="(min-width: 750px)">
  <img src="{{ site.baseurl }}/plots/weather_2026-09-07_0608_mobile.png" alt="" />
</picture>

Today's high is 81°, which is 2° *colder* than yesterday. Tomorrow is expected to be 8° **warmer** than today.

Currently:

- 63°
- Partly Cloudy
- 82% humidity
- 5 mph wind
- 40% cloud cover
- 38 AQI 🟩

<h3>Outlook</h3>
<pre><code style="font-family: monospace; font-size: 0.75em;">Mon:  0.00"          59 ---------- 81
Tue:  0.00"          59 -------------- 89
Wed:  0.04"               70 ------- 86
Thu:  0.19"            64 ------- 79
Fri:  0.00"          59 ------------- 87
<b>Sat:  0.01"             66 ------------ 92</b>
<b>Sun:  0.08"               71 ----------- 94</b>
Mon:  0.14"                72 ---------- 94
Tue:  0.24"       52 --------- 72
Wed:  0.00"   45 ---------- 65
Thu:  0.00"     48 ---------- 70
Fri:  0.00"        56 ----------- 79
<b>Sat:  0.21"       52 ------ 66</b>
<b>Sun:  0.00"   44 --------- 64</b>
Mon:  0.00"   45 ----------- 69</code></pre>

The current weather is posted regularly on Mastodon <a rel="me" href="https://mastodon.social/@ChampaignWeather">@ChampaignWeather@mastodon.social</a>

## [Compare Forecast Models »]({{ site.baseurl }}/projects/weather/forecasts)



## Temperature History

<iframe src="/interactive/champaign_weather_year.html" width="100%" height="500"> 
</iframe>

The chart above is my attempt at recreating the classic [*New York Times* weather chart](https://www.nytimes.com/interactive/2016/02/18/upshot/the-times-classic-weather-chart-now-online-with-3000-cities.html), which was [highlighted by Ed Tufte](https://www.edwardtufte.com/bboard/q-and-a-fetch-msg?msg_id=00014g) in his book *The Visual Display of Quantitative Information*.

## [Seasonal Forecast »]({{ site.baseurl }}/projects/weather/seasonal)

<picture>
  <source srcset="{{ site.baseurl }}/plots/temp_history.png"
          media="(min-width: 750px)">
  <img src="{{ site.baseurl }}/plots/temp_history_mobile.png" alt="" />
</picture>

## [Soil »]({{ site.baseurl }}/projects/weather/soil)

## Severe Thunderstorm Outlook

![](https://www.spc.noaa.gov/products/activity_loop.gif)

<p class="updated_time">Source: <a href="https://www.spc.noaa.gov">NOAA/NWS Storm Prediction Center</a>.</p> 




