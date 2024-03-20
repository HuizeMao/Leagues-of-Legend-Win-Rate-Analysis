# Leagues of Legend Win Rate Analysis

by Raymond Wang, Huize Mao

***Note***: If you choose a repo name and title as uninspired as the ones here, I will be quite sad.

---

## Introduction

In this project, we studied the effectiveness of spice challenges in building team morale.

---

## Cleaning and EDA
### Data Cleaning

### Univariate Analysis
![My Image](./plots/univar_hist_gold.png "Univariate Histogram Plot: Distribution of Gold per Game")
This histogram plot shows the frequency of total gold each team makes in all games. The plot has a peak around 51000 and has a longer tail on the right so it’s right-skewed, meaning in some games a team makes significantly more gold than the others possibly indicating their dominance in the game.

### Bivariate Analysis 1
![My Image](./plots/bivar_scatter_WinRate_DifCS.png "Bivariate Scatter Plot: Win Rate vs CS at Ten Minute")


### Bivariate Analysis 2



---

## Assessment of Missingness

Here's what a Markdown table looks like. Note that the code for this table was generated _automatically_ from a DataFrame, using

```py
print(counts[['Quarter', 'Count']].head().to_markdown(index=False))
```

| Quarter     |   Count |
|:------------|--------:|
| Fall 2020   |       3 |
| Winter 2021 |       2 |
| Spring 2021 |       6 |
| Summer 2021 |       4 |
| Fall 2021   |      55 |

---

## Hypothesis Testing

---

## Prediction Problem

---

## Baseline Model

---

## Final Model

---

## Fairness Analysis





---