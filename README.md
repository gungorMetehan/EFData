# EFData
**EFData: Eternal Fire Datasets**

<p align="center"><img src="https://github.com/gungorMetehan/EFData/assets/102655648/bade2838-0d3f-4f6d-924c-6c685f81dcc5" width="200" height="100"></p>

As a gamer who plays CS:GO / CS2 (Counter Strike: Global Offensive / 2), I also enjoy following matches of professional players/teams. I especially watch [Eternal Fire](https://eternalfire.gg/), the biggest team in Turkey. As someone interested in statistics, it would be inevitable for me not to be interested in data about CS players and teams. Therefore, I decided to create datasets containing statistics of the team and players I follow. Thus, a large dataset folder has been prepared for those interested in analyzing both EF and CS data.

This dataset consists of statistics provided by [hltv.org](https://www.hltv.org/).

<p align="center"><img src="https://github.com/gungorMetehan/EFData/assets/102655648/d3149d82-38e3-481d-b4fd-9cd67abbc6dd" width="300" height="150">  <img src="https://github.com/gungorMetehan/EFData/assets/102655648/04b809f9-2447-4f1e-9941-440b6fc3e1eb" width="300" height="150"></p>
<p align="center"><b>#forEF - #battleforEF</b></p>

## How to Import the Data Into R
```
# importing XANTARES dataset to R (Windows)
XANTARES <- read.csv("https://raw.githubusercontent.com/gungorMetehan/EFData/main/XANTARES.csv")
```

## How to Import the Data Into Python
```
# importing EF_world_ranking dataset to Python (Windows)
import pandas as pd
EF_world_ranking = pd.read_csv("https://raw.githubusercontent.com/gungorMetehan/EFData/main/EF_world_ranking.csv")
```

## What’s Inside
There are multiple data sets in this repo:
1. `EF_world_ranking`: Eternal Fire World Ranking
2. `EF_team_stats`: Eternal Fire Team Stats
3. `EFA_world_ranking`: Eternal Fire Academy Team World Ranking
4. `EFA_team_stats`: Eternal Fire Academy Team Stats
5. `XANTARES`: İsmailcan 'XANTARES' Dörtkardeş's Stats
6. `woxic`: Özgür 'woxic' Eker's Stats
7. `MAJ3R`: Engin 'MAJ3R' Küpeli's Stats
8. `Calyx`: Buğra 'Calyx' Arkın's Stats
9. `Wicadia`: Ali Haydar 'Wicadia' Yalçın's Stats
10. `imoRR`: Ömer 'imoRR' Karataş's Stats
11. `paz`: Ahmet 'paz' Karahoca's Stats

## Annotation
I’m planning to edit the dataset folder regularly. Therefore, I am open to your requests and comments.


