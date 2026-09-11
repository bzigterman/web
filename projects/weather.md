---
layout: page
title: Weather
permalink: /projects/weather/
imageurl: https://bzigterman.com/plots/temp_history.png
webappicon: /weather.png
---

## Champaign–Urbana Forecast

<p class="updated_time"> Latest data: 09:24 AM CT, September 11</p>

<picture>
  <source srcset="{{ site.baseurl }}/plots/weather_2026-09-11_1425.png"
          media="(min-width: 750px)">
  <img src="{{ site.baseurl }}/plots/weather_2026-09-11_1425_mobile.png" alt="" />
</picture>

Today's high is 82°, which is 8° **warmer** than yesterday. Tomorrow is expected to be 6° **warmer** than today.

Currently:

- 67°
- Clear
- 89% humidity
- 6 mph wind
- 12% cloud cover
- 54 AQI 🟨
- 0.13 inches of rain in the past 24 hours
- 0.01 inches of rain expected in the next 48 hours

<h3>Outlook</h3>
<pre><code style="font-family: monospace; font-size: 0.75em;">Fri:  0.00"         60 ----------- 82
<b>Sat:  0.00"            67 ----------- 88</b>
<b>Sun:  0.01"        59 ---------- 79</b>
Mon:  0.00"      54 --------- 72
Tue:  0.01"          63 ---------------- 95
Wed:  0.14"              70 ----------- 92
Thu:  0.05"             69 ------------- 94
Fri:  0.24"         60 ------------ 85
<b>Sat:  0.00"       57 ------- 71</b>
<b>Sun:  0.00"     53 ---------- 72</b>
Mon:  0.00"       56 ------- 71
Tue:  0.00"       56 --------- 75
Wed:  0.00"       56 -------------- 84
Thu:  0.01"         60 ------------ 85
Fri:  0.00"    50 ---------- 70
<b>Sat:  0.00"   48 -------------- 76</b></code></pre>

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




