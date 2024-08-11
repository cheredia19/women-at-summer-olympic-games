---
title: Women's participation in the history of the Summer Olympics
description: .
---

## Testing data-rich components

I will add a data table from my data.csv file below:
<FlatUiTable
  data={{
    url: 'women_olympic_games.csv'
  }}
 />

 Looks kinda cool. What about a Plotly Bar Chart at this would look like:

 <PlotlyBarChart
  data={{
    url: 'women_olympic_games.csv'
  }}
  title=""
  xAxis="Games"
  yAxis="Total of women"
/>

 <PlotlyBarChart
  data={{
    url: 'women_olympic_games.csv'
  }}
  title=""
  xAxis="Games"
  yAxis="Percent change"
/>

