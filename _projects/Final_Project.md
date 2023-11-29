---
name: Does Side Matter In Professional League of Legends
tools: [Python, HTML, vega-lite]
image: #add in new picture
description: This is an analysis of the 2023 season to see if the team that you are on does indeed matter or not
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Visualization 1 - Standard small Scatter plot

<vegachart schema-url="{{ site.baseurl }}/assets/json/League_appearance_bar.json" style="width: 100%"></vegachart>

Description 1, dont forget to add that im the author

# Visualization 2 - Rect Plot

<!-- <vegachart schema-url="{{ site.baseurl }}/assets/json/bld_inv_chart.json" style="width: 100%"></vegachart> -->

Descrition 2

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/JackLarson01/JackLarson01.github.io/blob/main/_data/League_Dataset.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/JackLarson01/JackLarson01.github.io/blob/main/python_notebooks/Homework_9_Plots.ipynb" text="The Analysis" %}
</div>

