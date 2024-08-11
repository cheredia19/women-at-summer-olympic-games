---
title: Women's participation in the history of the Summer Olympics
description: 
---

*By [César Heredia](https://x.com/cahered), data journalist*

## Women's participation in every Summer Olympic Games

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
  title="Total of women participating in every edition"
  xAxis="Games"
  yAxis="Total of women"
/>

 <PlotlyBarChart
  data={{
    url: 'women_olympic_games.csv'
  }}
  title="Percentage change between Olympic Games"
  xAxis="Games"
  yAxis="Percent change"
/>

<PlotlyBarChart
  data={{
    url: 'women_olympic_games.csv'
  }}
  title="Percentage of women out of total athletes"
  xAxis="Games"
  yAxis="Percentage of women"
/>

