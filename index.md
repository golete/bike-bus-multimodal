---
layout: default
altair-loader:
  altair-chart-1: "charts/bikecountAltair-008.json"
  altair-chart-2: "charts/bikecountAltair-062.json"
  altair-chart-3: "charts/bikecountAltair-111.json"
hv-loader:
  hv-chart-1: ["charts/vehicleCount.html", "500"] # second argument is the desired height
---

# Multimodal Interactions



This single-page website demos how to display visualizations created with altair, hvplot, and folium.

![map showing MTA transit system]({{ site.url }}{{ site.baseurl }}/assets/img/bbmm_01.png)

![map showing closeups of stops to be considered]({{ site.url }}{{ site.baseurl }}/assets/img/bbmm_02.png)

# Example: Embedding Altair & Hvplot Charts

This section will show examples of embedding interactive charts produced using [Altair](https://altair-viz.github.io) and [Hvplot](https://hvplot.pyviz.org/).

## Altair Example

Below is a chart of the incidence of measles since 1928 for the 50 US states.

<div id="altair-chart-1"></div>

<div id="altair-chart-2"></div>

<div id="altair-chart-3"></div>

This was produced using Altair and embedded in this static web page. Note that you can also display Python code on this page:

```python
import altair as alt
alt.renderers.enable('notebook')
```

![Alt Text]({{ site.url }}{{ site.baseurl }}/assets/img/busBike.gif)

## Passenger counts

Lastly, the measles incidence produced using the HvPlot package:

<div id="hv-chart-1"></div>


![Alt Text]({{ site.url }}{{ site.baseurl }}/assets/img/busPass.gif)

## Notes

- See the [lecture 13A slides](https://musa-550-fall-2021.github.io/slideslecture-13A.html) for the code that produced these plots.

**Important: When embedding charts, you will likely need to adjust the width/height of the charts before embedding them in the page so they fit nicely when embedded.**


