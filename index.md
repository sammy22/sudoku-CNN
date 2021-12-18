---
layout: default
title: Home
---

## Data Source 
The World Happiness Report is a landmark survey of the state of global happiness. The reports review the state of happiness in the world today and show how the new science of happiness explains personal and national variations in happiness.

[Source](https://www.kaggle.com/unsdsn/world-happiness)

## About the fields 
- Country 
- Region - region the country belongs to 
- HappinessRank - Rank of the country based on the Happiness Score
- HappinesScore 
- StandardError - standard error of the happiness score 
- Economy -  contribution of GDP to the calculation of the Happiness Score.
- Family -  contribution of family to the calculation of the Happiness Score
- Health -  Life expectancy contribution to the calculation of the Happiness Score
- Freedom -  Freedom contribution to the calculation of the Happiness Score.
- Trust  - The extent to which Perception of Corruption contributes to Happiness Score.
- [DystopiaResidual](https://worldhappiness.report/faq/)

    
#### Hypothesis/Questions
- How is the hapiness score related to Economy, Family, trust in govt and Freedom 
- Changes in happiness scores of the countries over the years 2015-19
- Happiest countries in the years 2015-19

#### Code 
 - [NoteBook](https://github.com/sammy22/sudoku-CNN/image_processing.ipynb)
 - [Repository](https://github.com/sammy22/sudoku-CNN)

#### Results
- Average happiness score was lowest in 2017 and highest in 2019 
- Happiest Country in 2015: Switzerland
- Happiest Country in 2016: Denmark
- Happiest Country in 2017: Norway
- Happiest Country in 2018: Finland
- Happiest Country in 2019: Finland
- correlation between different fields of data for year 2019 shows that happiness rank has negative correlation wrt economy, trust, family, Freedom and Health 
- 25% of countries have score less than 4.5
- 50% of countries have score more than 5.37

#### Challenges
- Insufficient datasets. Some countries have scores for 2015 and 2016 only
- Missing columns like Standard Error, limits for few years 
- Inconsistent naming of columns for different years of Happiness Reports.
