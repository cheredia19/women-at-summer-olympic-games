---
title: Women's participation in the history of the Summer Olympics
description: .
---

## Testing data-rich components

I will add a data table from my data.csv file below:
<FlatUiTable
  data={{
    url: 'women_olympics.csv'
  }}
 />

 Looks kinda cool. What about a linechart? Let's see what this would look like:

 <PlotlyBarChart
  data={{
    url: 'data.csv'
  }}
  title=""
  xAxis="games"
  yAxis="women"
/>

