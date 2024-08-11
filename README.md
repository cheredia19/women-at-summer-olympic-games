---
title: Welcome to your template dataset page!
description: This is a template for publishing your dataset with Datahub Cloud.
---

## Testing data-rich components

I will add a data table from my data.csv file below:
<FlatUiTable
  data={{
    url: 'data.csv'
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

