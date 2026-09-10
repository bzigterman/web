---
layout: page
title: Weather
permalink: /projects/weather/
imageurl: https://bzigterman.com/plots/temp_history.png
webappicon: /weather.png
---

## Champaign–Urbana Forecast

<p class="updated_time"> Latest data: 04:41 AM CT, September 10</p>

<picture>
  <source srcset="{{ site.baseurl }}/plots/weather_2026-09-10_0941.png"
          media="(min-width: 750px)">
  <img src="{{ site.baseurl }}/plots/weather_2026-09-10_0941_mobile.png" alt="" />
</picture>

Today's high is 76°, which is 11° *colder* than yesterday. Tomorrow is expected to be 7° **warmer** than today.

Currently:

- 67°
- Light Rain
- 94% humidity
- 5 mph wind
- 39% cloud cover
- 52 AQI 🟨
- 0.1 inches of rain expected in the next 48 hours

<h3>Outlook</h3>
<pre><code style="font-family: monospace; font-size: 0.75em;">Thu:  0.19"            67 ----- 76
Fri:  0.00"           64 --------- 83
<b>Sat:  0.00"           65 ---------- 84</b>
<b>Sun:  0.02"            67 ----------- 89</b>
Mon:  0.00"          62 --------------- 93
Tue:  0.04"                74 ---------- 94
Wed:  0.32"            66 ------------ 91
Thu:  0.32"       57 ------- 70
Fri:  0.00"   49 ---------- 69
<b>Sat:  0.00"   49 ------------ 72</b>
<b>Sun:  0.00"    50 ------------ 74</b>
Mon:  0.00"     53 ------------ 76
Tue:  0.00"      54 ------------- 81
Wed:  0.00"          62 ----------- 84
Thu:  0.00"         61 ------------ 84</code></pre>

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




