# Excess mortality during the covid19 pandemics

Code: https://github.com/dkobak/excess-mortality/blob/main/all-countries.ipynb<br>
Run in browser: https://colab.research.google.com/github/dkobak/excess-mortality/blob/main/all-countries.ipynb<br>

The data are sourced from the Human Mortality Database (and removing the last two weeks), FT, and NYT. Ukraine data scraped by Иван Зайцев <a href="https://navizv.github.io/covid">here</a>. Excess mortality is computed relative to the baseline using linear extrapolation of the 2015–19 trend. 

Red: excess mortality starting from the first officially reported covid19 death.<br>
Gray: excess mortality as a % of the usual yearly deaths.<br>
Black: excess mortality per 100,000 population.<br>
Blue: ratio to the daily reported deaths over the same period (sourced from https://ourworldindata.org/covid-deaths).

<p><a href="img/all-countries.png?raw=true"><img src="img/all-countries.png" width="800" title="Excess mortality all over the world"></a>
  
Compare with:<br>
FT: https://www.ft.com/content/a2901ce8-5eb7-4633-b89c-cbdf5b386938<br>
NYT: https://www.nytimes.com/interactive/2020/04/21/world/coronavirus-missing-deaths.html<br> 
The Economist: https://www.economist.com/graphic-detail/2020/07/15/tracking-covid-19-excess-deaths-across-countries<br>

--------------------------

# Excess mortality in Russia

Code: https://github.com/dkobak/excess-mortality/blob/main/russia.ipynb

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

<p>Detailed statistics in regions with the most excess deaths:

<p><a href="img/regions.png?raw=true"><img src="img/regions.png" width="600" title="Regions"></a>

<p>Daily reported covid19 mortality and estimated excess mortality across the countries with the most reported covid19 deaths. Undercount estimates are taken from The Economist, NYT, Financial Times, and other sources. Note that in this figure the excess mortality in all countries is ESTIMATED using the undercount coefficient times the latest daily reported number of deaths:

<p><a href="img/countries.png?raw=true"><img src="img/countries.png" width="600" title="Across countries"></a>



### Some technical figures

<p>Extrapolation of the linear trend:

<p><a href="img/average-monthly.png?raw=true"><img src="img/average-monthly.png" width="400" title="Monthly deviations"></a>

<p>Seasonal variation:

<p><a href="img/monthly-deviations.png?raw=true"><img src="img/monthly-deviations.png" width="400" title="Monthly deviations"></a>

<p>Evolution of the undercount coefficient:

<p><a href="img/undercount.png?raw=true"><img src="img/undercount.png" width="400" title="Excess mortality in Russia"></a>


