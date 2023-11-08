---
name: Homework 9 Submission
tools: [Python, HTML, vega-lite]
image: assets/pngs/IS445_Homework9.png
description: This is my Submission page for my IS445 Homework 9 assignment
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Visualization 1 - Standard small Scatter plot

<vegachart schema-url="{{ site.baseurl }}/assets/json/bld_inv_bar.json" style="width: 100%"></vegachart>

For my first Viz I just wanted to create a Histogram so that I could easily show the total number of Floors Below Grade and the distribution of them, I beleive this is showing the number of basements in the houses that are represented within this dataset. I decided that overall the Viz was best at its default values because I didn't feel that the viz really added that much when there is different colors or other things added. Because I didn't submit homework 7 properly, Im using very similar plots that I created for that assigment, however did have to change the way that I called the functions through Altair.

# Visualization 2 - Standard small Scatter plot

<vegachart schema-url="{{ site.baseurl }}/assets/json/bld_inv_chart.json" style="width: 100%"></vegachart>

For my second visualization, I really liked the rect that we created in class and wanted to explore how to create one on my own using the some of the data before, in this viz I am using the Floor below grade along the X axis of my graph and the County (or chosen county) for my Y axis. In order to fit the Viz in the correct scale, I had to use a really large height, and used the mark for rect. Similar to the first Viz that I used for this assignment, this one is also very similar to what I created for homework 7, I did have to change a lot more and actually add some interactivity for useers, however it is very simple interactivity. One thing I couldn't figure out how to do is that when the you select onle 1 county, the height of the viz stays the same, however their is only one data point on the Y axis so its way too big for one peice of data.

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/JackLarson01/JackLarson01.github.io/blob/main/_data/building_inventory.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/JackLarson01/JackLarson01.github.io/blob/main/python_notebooks/Homework_9_Plots.ipynb" text="The Analysis" %}
</div>

