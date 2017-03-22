---
layout: post
title: Interactive Tableau visualizations
---

I wanted to post a couple of interactive Tableau charts from previous projects here, both to check out what interactive features are available, and to provide additional insights. The mechanics for accomplishing this are fairly straightforward - save the worksheet to "Tableau Public" using the "Server" dropdown menu on the Tableau Desktop program, and use the shareable link provided on <a href="https://public.tableau.com"><font color="008000"><b>Tableau Public</b></font></a> to embed the chart in the blog post using an ```<iframe>``` tag.

```html
<iframe src="https://public.tableau.com/views/airport_delays/map_2014?:showVizHome=no&:embed=true"
width="900" height="600"></iframe>
```

#### Airport delays

See <a href="https://karthik-33.github.io/FAA-flight-delays"><font color="008000"><b>FAA Airport flight delays</b></font></a> for the original post on this topic. The chart below shows % on-time departures for various airports in the continental USA from 2004-2014, based on FAA data. Small airports in the vicinity of the largest airports (by annual traffic volume) showed the worst on-time departure rates.

<iframe src="https://public.tableau.com/views/airport_delays/map_2014?:showVizHome=no&:embed=true" width="900" height="600" frameborder="0"></iframe>


#### IMDB movie ratings

See <a href="https://karthik-33.github.io/IMDB-Top-250-movies"><font color="008000"><b>Predicting IMDB Top 250 movie ratings </b></font></a> for the original post on this topic. The chart below shows the effect of number of Oscars (nominated for or won), and number of countries associated with the movie on movie ratings.

<iframe src="https://public.tableau.com/views/ratings_oscars_0/Sheet6?:showVizHome=no&:embed=true" width="900" height="600" frameborder="0"></iframe>


#### Caterpillar tube assembly pricing

See <a href="https://karthik-33.github.io/capstone"><font color="008000"><b>Predict pricing for Caterpillar tube assemblies used in Caterpillar equipment </b></font></a> for the original post on this topic. The chart below shows the effect of the number of CP-26 components in a tube assembly on quoted price, as a function of quoted quantity of tube assemblies. Also available in the tooltip are tube assembly wall thickness and diameter - additional factors that affect quoted price.

<iframe src="https://public.tableau.com/views/caterpillar_ta_cp26_0/cp?:showVizHome=no&:embed=true" width = "900" height = "600" frameborder="0"></iframe>
