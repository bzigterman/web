---
layout: page
title: Weather
permalink: /projects/weather/
imageurl: https://bzigterman.com/plots/temp_history.png
webappicon: /weather.png
---

## Champaign–Urbana Forecast

<p class="updated_time"> Latest data: 07:56 AM CT, September 10</p>

<picture>
  <source srcset="{{ site.baseurl }}/plots/weather_2026-09-10_1256.png"
          media="(min-width: 750px)">
  <img src="{{ site.baseurl }}/plots/weather_2026-09-10_1256_mobile.png" alt="" />
</picture>

Today's high is 76°, which is 12° *colder* than yesterday. Tomorrow is expected to be 8° **warmer** than today.

Currently:

- 66°
- Mostly Cloudy
- 96% humidity
- 2 mph wind
- 78% cloud cover
- 57 AQI 🟨
- 0.21 inches of rain expected in the next 48 hours

<h3>Outlook</h3>
<pre><code style="font-family: monospace; font-size: 0.75em;">Thu:  0.24"           65 ------ 76
Fri:  0.00"           64 ---------- 83
<b>Sat:  0.00"            66 ----------- 87</b>
<b>Sun:  0.05"            66 ------------- 91</b>
Mon:  0.00"          63 ---------------- 93
Tue:  0.18"             68 ------------ 92
Wed:  0.96"       58 ---------- 77
Thu:  0.02"       57 ----- 67
Fri:  0.00"   50 ------------ 72
<b>Sat:  0.00"    52 ------------ 74</b>
<b>Sun:  0.00"     53 ----------- 75</b>
Mon:  0.00"       57 ---------- 76
Tue:  0.00"        59 ---------- 79
Wed:  0.00"      56 ----------- 77
Thu:  0.01"    52 -------------- 79
Fri:  0.17"        59 ------------ 82</code></pre>

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




