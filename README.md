# Coronavirus Analysis
This repository represents a significant body of work to connect the various data sources available in the amazon covid data warehouse, and use them to form insights about how the coronavirus is and has impacted the United States.
* Caveats: Work has not been checked or peer reviewed. Do not draw conclusions from this analysis

### Gifs

* The bigger and more red a circle gets, the higher the death count or death rate is.
* Dates are scrolled in the title area

#### Total Deaths Over Time

It's no suprise that the most coronavirus deaths occur in areas with the biggest populations.  This graph gives an idea of the overall human cost or impact of the virus relative to other areas.

<img src="gif1/movie.gif" width="900">

#### Total Death Rate per 100k People Over Time

This visual shows death rate (as opposed to counts above), so it is more closley connected with the risk (of death by coronavirus) at various places in the US.  Seen this way, many more areas of the country have been severley impacted but their populations are lower and thus not emphasized in the gif above.

<img src="gif2/movie.gif" width="900">

#### Daily Death Rate per 100k People Over Time

This gif moves through time about half as fast as the two above.  It shows the daily death rate, so the circles get bigger and smaller as opposed to the two above.  Thus it shows the change in risk (of death by coronavirus) over time as measured by the average daily death rate.

<img src="gif4/movie.gif" width="900">

### Sources

* Amazon's coronavirus data lake
* Safegraph census for county level data
* Google mobility
* Multiple sources of deaths and cases available (John's Hopkins, New York Times) but CDC is primerily used

### Detailed Report

In depth analysis notebook is here [Notebook](covidVisualizations.ipynb "link to notebook") | [HTML](covidVisualizations.html "link to notebook") and contains:

* Section 1: 
&nbsp;&nbsp;&nbsp; Deaths and Death Rate (per 100k people) by State
&nbsp;&nbsp;&nbsp; Total and Average Daily Cases and Deaths Over Time
&nbsp;&nbsp;&nbsp; Aggregate and Region (Northeast, South, Midwest, West, Other)
* Section2:
&nbsp;&nbsp;&nbsp; Deep Dive on Top 10 Death Count States
&nbsp;&nbsp;&nbsp; County Level Cases, Deaths, and Mobility over Time
&nbsp;&nbsp;&nbsp; Death Rates for Key County Features (Population Density, Age, Socioeconomics, Uninsured, and Race 
* Section 3:
&nbsp;&nbsp;&nbsp; Comparison (Death Rates over Time) of States within Regions (Northeast, South, Midwest, West, Other)
* Section 4:
&nbsp;&nbsp;&nbsp; Death Rates (Entire US) for Key County Features (Population Density, Age, Socioeconomics, Uninsured, and Race 

Note: There may be missing data for some California counties.
