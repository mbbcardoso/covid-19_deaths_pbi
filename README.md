# covid-19_deaths_pbi
A Power BI report exploring data about deaths caused by the coronavirus pandemic

The web version can be accessed at: https://app.powerbi.com/view?r=eyJrIjoiOWE1N2M0MzEtYmQ2OS00NTlmLWEzMmYtODVmZjIwYWEwMzczIiwidCI6IjczOGM4YjdmLWE0ODctNGNmNy05NjdlLWM1YWFlYjFlMDUwNSIsImMiOjh9

The Overview page shows general data on deaths, allowing to highlight countries:

![](gif_overview.gif)

When clicking the play button on the bottom of the screen, the Timeline page is displayed, showing the day by day progression of the pandemic:

![](gif_timeline.gif)

Lastly, the Country Comparison page allows for detailed analyses of countries' situation at a same height of spread of the disease, starting at the day of 30th death on each country:

![](gif_comparison.gif)

The dataset can be obtained at: https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_global.csv

The COVID-19 deaths.pbix file is configured to fetch that CSV when Refresh is clicked. The web version is refreshed automatically every day at 8:30am CET.
