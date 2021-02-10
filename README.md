# Excess mortality during the COVID-19 pandemic

Code: https://github.com/dkobak/excess-mortality/blob/main/all-countries.ipynb<br>
Run in browser: https://colab.research.google.com/github/dkobak/excess-mortality/blob/main/all-countries.ipynb

Data source: https://github.com/akarlinsky/world_mortality

**Preprint:** Karlinsky & Kobak 2021, The World Mortality Dataset: Tracking excess mortality across countries during the COVID-19 pandemic, https://www.medrxiv.org/content/10.1101/2021.01.27.21250604v1

The data are sourced from the [World Mortality Dataset](https://github.com/akarlinsky/world_mortality). Excess mortality is computed relative to the baseline obtained using linear extrapolation of the 2015–19 trend. In the figure below, gray lines are 2015–19, black line is baseline for 2020, red line is 2020, purple line is 2021.

Red number: excess mortality starting from the first officially reported covid19 death.<br>
Gray number: excess mortality as a % of the baseline yearly deaths.<br>
Black number: excess mortality per 100,000 population.<br>
Blue number: ratio to the daily reported deaths over the same period (sourced from JHU).

<p><a href="img/all-countries.png?raw=true"><img src="img/all-countries.png" width="800" title="Excess mortality all over the world"></a>

Top-10 countries in the World Mortality Dataset according to different metrics: 

<p><a href="img/leaderboard.png?raw=true"><img src="img/leaderboard.png" width="600" title="Top countries by excess mortality"></a>

Compare with: [FT](https://www.ft.com/content/a2901ce8-5eb7-4633-b89c-cbdf5b386938), [NYT](https://www.nytimes.com/interactive/2020/04/21/world/coronavirus-missing-deaths.html), [The Economist](https://www.economist.com/graphic-detail/2020/07/15/tracking-covid-19-excess-deaths-across-countries), [WSJ](https://www.wsj.com/articles/the-covid-19-death-toll-is-even-worse-than-it-looks-11610636840)

### Extrapolation until today
Daily reported covid19 mortality and estimated excess mortality across the countries with the most reported covid19 deaths. Note that in this figure the excess mortality in all countries is ESTIMATED using the undercount coefficient times the LATEST daily reported number of deaths. So this corresponds to the gray markers in the figure above.

<p><a href="img/countries.png?raw=true"><img src="img/countries.png" width="600" title="Across countries"></a>


--------------------------

## Excess mortality in Russia

The code for my February 2021 paper in *Significance* [Excess mortality reveals Covid's true toll in Russia](https://rss.onlinelibrary.wiley.com/doi/10.1111/1740-9713.01486) is available in the `significance2021` folder, together with the frozen data and the final figures.

Figures below are updated every month. The up-to-date data can be found in the `russian-data` folder. Code: https://github.com/dkobak/excess-mortality/blob/main/russia.ipynb

<p><a href="img/allregions.png?raw=true"><img src="img/allregions.png" width="800" title="Excess mortality in Russian regions"></a>
  
<p>Animation (English):

<p><a href="img/animation-eng.gif?raw=true"><img src="img/animation-eng.gif" width="600" title="Excess mortality in Russia, animation"></a>

<p>Animation (Russian):

<p><a href="img/animation-rus.gif?raw=true"><img src="img/animation-rus.gif" width="600" title="Excess mortality in Russia, animation RUS"></a>
  
<p>Map (English):

<p><a href="img/map-eng.png?raw=true"><img src="img/map-eng.png" width="600" title="Excess mortality in Russian regions"></a>

<p>Map (Russian):

<p><a href="img/map-rus.png?raw=true"><img src="img/map-rus.png" width="600" title="Excess mortality in Russian regions"></a>

<p>Without regions:

<p><a href="img/russia.png?raw=true"><img src="img/russia.png" width="400" title="Excess mortality in Russia"></a>
 
<p>Yearly deaths:

<p><a href="img/yearly.png?raw=true"><img src="img/yearly.png" width="400" title="Yearly deaths in Russia"></a>

<p>Detailed statistics in regions with the most excess deaths:

<p><a href="img/regions.png?raw=true"><img src="img/regions.png" width="600" title="Regions"></a>
 

### Some technical figures

<p>Extrapolation of the linear trend:

<p><a href="img/average-monthly.png?raw=true"><img src="img/average-monthly.png" width="400" title="Monthly deviations"></a>

<p>Seasonal variation:

<p><a href="img/monthly-deviations.png?raw=true"><img src="img/monthly-deviations.png" width="400" title="Monthly deviations"></a>

<p>Evolution of the undercount coefficient:

<p><a href="img/undercount.png?raw=true"><img src="img/undercount.png" width="400" title="Excess mortality in Russia"></a>
