---
title: Women's participation in the history of the Summer Olympics
description: 
---

*By [César Heredia](https://x.com/cahered), data journalist*

## Women's participation in every Summer Olympic Games

Participation of Women in the Summer Olympics has been constantly increasing since the Paris 1900 Olympic Games, given that no female athletes competed in the Athens 1896 Olympic Games.

One hundred and twenty-four years ago, 22 women pursued Olympic glory, with Swiss-American sailor [Hélène de Pourtalès](https://olympics.com/es/atletas/helen-de-pourtales) becoming the first woman ever to win an Olympic gold medal aboard the boat Lérina in the first race of 1–2 ton class sailing event. She and other crew members also won a silver medal in the second race of the 1–2 ton class.

British tennis player [Charlotte Cooper](https://olympics.com/en/athletes/charlotte-cooper) also made history as the first female Olympic champion **in an individual competition**.

It was also in the French capital, where over 100 women took part in the global competition for the first time. One hundred and 36 women participated in the Paris 2024 Olympic Games. Three Americans and a British female athlete earned multiple medals:

- Tennis player [Helen Wills (USA)](https://olympics.com/en/athletes/helen-wills): two gold medals.
- Diver [Elizabeth Becker-Pinkston (USA)](https://olympics.com/en/athletes/elizabeth-becker-pinkston): a gold and a silver medal.
- Tennis player [Kathleen McKane (GBR)](https://olympics.com/en/athletes/kathleen-mckane): a silver and a bronze medal.
- Swimmer [Gertrude Ederle (USA)](https://olympics.com/en/athletes/gertrude-ederle): two bronze medals.

 <PlotlyBarChart
  data={{
    url: 'women_olympic_games.csv'
  }}
  title="Total of women participating in every edition"
  xAxis="Games"
  yAxis="Total of women"
/>

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

