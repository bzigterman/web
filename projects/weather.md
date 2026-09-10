---
layout: page
title: Weather
permalink: /projects/weather/
imageurl: https://bzigterman.com/plots/temp_history.png
webappicon: /weather.png
---

## Champaign–Urbana Forecast

<p class="updated_time"> Latest data: 10:15 PM CT, September 09</p>

<picture>
  <source srcset="{{ site.baseurl }}/plots/weather_2026-09-10_0315.png"
          media="(min-width: 750px)">
  <img src="{{ site.baseurl }}/plots/weather_2026-09-10_0315_mobile.png" alt="" />
</picture>

Today's high is 87°, which is 0° **warmer** than yesterday. Tomorrow is expected to be 5° *colder* than today.

Currently:

- 71°
- Mostly Cloudy
- 85% humidity
- 4 mph wind
- 63% cloud cover
- 48 AQI 🟩
- 0.02 inches of rain expected in the next 48 hours

<h3>Outlook</h3>
<pre><code style="font-family: monospace; font-size: 0.75em;">Wed:  0.00"              71 -------- 87
Thu:  0.02"            67 -------- 82
Fri:  0.00"           64 -------- 81
<b>Sat:  0.00"           64 ----------- 87</b>
<b>Sun:  0.00"             68 ----------- 90</b>
Mon:  0.00"              70 ------------ 95
Tue:  0.07"           64 -------- 81
Wed:  0.02"          62 ------ 75
Thu:  0.39"         60 -------- 76
Fri:  0.03"     53 -------- 68
<b>Sat:  0.00"    50 ---------- 70</b>
<b>Sun:  0.00"   48 ------------ 72</b>
Mon:  0.00"     52 ------------ 76
Tue:  0.00"       57 --------------- 86
Wed:  0.00"         60 ------------- 87
Thu:  0.00"    50 ------- 64</code></pre>

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




