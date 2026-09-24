# Findings — Frailty & Grip Strength (Question 1)

## I. Summary statistics (numeric columns)

|                |    mean |   median |    std |
|:---------------|--------:|---------:|-------:|
| Height_in      |  68.6   |   68.45  |  1.671 |
| Weight_lb      | 131.9   |  136     | 14.232 |
| Age_yr         |  32.5   |   29.5   | 12.86  |
| Grip_kg        |  26     |   27     |  4.522 |
| Height_m       |   1.742 |    1.739 |  0.042 |
| Weight_kg      |  59.829 |   61.689 |  6.455 |
| BMI            |  19.682 |   19.185 |  1.781 |
| Frailty_binary |   0.4   |    0     |  0.516 |

## AgeGroup counts

| AgeGroup   |   count |
|:-----------|--------:|
| <30        |       5 |
| 30–45      |       3 |
| 46–60      |       2 |
| >60        |       0 |

## II. Grip strength ↔ Frailty

| Frailty   |   count |   mean |   median |   std |
|:----------|--------:|-------:|---------:|------:|
| N         |       6 |  27.67 |     29.5 |  4.63 |
| Y         |       4 |  23.5  |     23   |  3.42 |

- Correlation between `Grip_kg` and `Frailty_binary`: **r = -0.476** (p = 0.164, n = 10).
- The relationship is **moderate and negative**: frail participants (Y) average **23.50 kg** grip strength
  vs **27.67 kg** for non-frail participants (N), a difference of 4.17 kg.
- This agrees with the literature statement that reduced grip strength in females is associated with higher frailty.
- Caveat: with only 10 participants the p-value is 0.164, so the result is not statistically significant at α = 0.05;
  a larger sample would be needed to confirm the effect. Correlation also does not imply causation.
