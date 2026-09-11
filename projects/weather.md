---
layout: page
title: Weather
permalink: /projects/weather/
imageurl: https://bzigterman.com/plots/temp_history.png
webappicon: /weather.png
---

## Champaign–Urbana Forecast

<p class="updated_time"> Latest data: 11:35 PM CT, September 10</p>

<picture>
  <source srcset="{{ site.baseurl }}/plots/weather_2026-09-11_0435.png"
          media="(min-width: 750px)">
  <img src="{{ site.baseurl }}/plots/weather_2026-09-11_0435_mobile.png" alt="" />
</picture>

Today's high is 74°, which is 13° *colder* than yesterday. Tomorrow is expected to be 8° **warmer** than today.

Currently:

- 65°
- Clear
- 93% humidity
- 4 mph wind
- 1% cloud cover
- 59 AQI 🟨
- 0.13 inches of rain in the past 24 hours

<h3>Outlook</h3>
<pre><code style="font-family: monospace; font-size: 0.75em;">Thu:  0.14"            65 ---- 74
Fri:  0.00"           62 ---------- 83
<b>Sat:  0.00"             67 ----------- 90</b>
<b>Sun:  0.02"             66 --------- 86</b>
Mon:  0.08"          61 -------------- 90
Tue:  0.08"                74 ---------- 95
Wed:  0.42"            64 ------ 78
Thu:  0.18"            64 --- 72
Fri:  0.16"            64 ---------- 87
<b>Sat:  0.91"            64 ----- 76</b>
<b>Sun:  0.02"       54 ----- 65</b>
Mon:  0.00"   45 --------- 65
Tue:  0.00"    47 ----------- 71
Wed:  0.00"       53 ----------- 77
Thu:  0.00"        57 ------------ 81
Fri:  0.00"          61 ------------ 87</code></pre>

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




