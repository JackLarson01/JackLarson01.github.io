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
### By: Jack Larson

One question that many, including myself, have always had when it comes to the game of League of Legends is whether the side of the map you are on actually matters. Specifically, we're interested in how it affects the win rate of a champion or character and its impact on professional League of Legends.

If you're reading this and have never heard of League of Legends before, in simple terms, it is a team-based game where five characters play against five other characters, each unique and controlled by different people. There are two teams: the red side, located in the bottom left of the map, and the blue side, positioned in the top right.

Today, I am going to examine whether the red side or the blue side has an effect on the win rate within the professional scene in the 2023 year, using this dataset.

## Visualization 1 - Number of games played on each champion within professional League of Legends

The first graph below compiles all the professional games played with each character within the 2023 year and indicates the side on which each character was played. This graph serves to provide you with a general idea of which characters are the most popular and what kind of information is present within this dataset.

You can hover over each champion to get an idea of the number of games (labeled 'Count of Records') played with that champion on each side.

<vegachart schema-url="{{ site.baseurl }}/assets/json/League_appearance_bar.json" style="width: 100%"></vegachart>

## Visualization 2 - Winrate compared per side

These next graphs show from left to right, the total winrate, the winrate on the blue side, and the winrate for the red side. If you hover over the color next to each of the champion names, it will show you the champion name, their winrate (mean of results) and number of games (count of Records).

<vegachart schema-url="{{ site.baseurl }}/assets/json/League_Comb_Graph.json" style="width: 100%"></vegachart>

## Final thoughts

Although I know that there are pleanty of other factors that go into the winrate of a champion within professional League of Legends, its really interesting to see how the winrate of a champion differes when its on the other side of the game, for example Gnar has almost 1700 games played on the character, however the winrate is almost 8% hgher on the Blue side rather than the Red Side.

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/JackLarson01/JackLarson01.github.io/blob/main/_data/League_Dataset.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/JackLarson01/JackLarson01.github.io/blob/main/python_notebooks/League_Plots.ipynb" text="The Analysis" %}
</div>

