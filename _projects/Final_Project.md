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

# Does the Chosen Side Actually Matter In Professional League of Legends

One question that I and many other people like myself have always had when it comes to the game of League of Legends, is wheather the side of the map that you are on actually matters. Specificallt for the winrate of a champion or character and how this affects proffesional League of legends. 

If you are reading this and have never heard of League of Legends before, the simple way to put it is a team based game where 5 characters are playing against 5 other characters, all of which are unique and controlled by different people. There are two teams, one is the red side which is in the bottom left of the map, and the other is the blue side in the top right.

What I am going to take a look at today with this dataset is if either the red side or the blue side have an effect on the winrate within the professional 2023 year. 

## Visualization 1 - Number of games played on each champion within professional League of Legends

This first Graph seen below is a compilation of all of the professional games played using each character within the 2023 year, and what side that character was played on. This graph is for you to get a general idea of what characters are the most popular, ADD MORE

<vegachart schema-url="{{ site.baseurl }}/assets/json/League_appearance_bar.json" style="width: 100%"></vegachart>

Description 1, dont forget to add that im the author

## Visualization 2 - Rect Plot

<!-- <vegachart schema-url="{{ site.baseurl }}/assets/json/bld_inv_chart.json" style="width: 100%"></vegachart> -->

Descrition 2

## Final thoughts

Although I know that there are pleanty of other factors that go into the winrate of a champion within professional League of Legends.

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/JackLarson01/JackLarson01.github.io/blob/main/_data/League_Dataset.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/JackLarson01/JackLarson01.github.io/blob/main/python_notebooks/League_Plots.ipynb" text="The Analysis" %}
</div>

