# Findings — Student Performance (Question 2)

## Data preparation
- Data: 1000 students, 8 columns.
- Missing values: 0. Duplicate rows: 0. All scores are between 0 and 100.
- Added `overall_avg` = average of math, reading and writing.
- All figures are 800×600 px, 300 DPI.

## V1 — Gender boxplots (math vs reading)
Q: Are there gender differences in math vs reading?
A: Boys do better in math (average 68.7 vs 63.6). Girls do better in reading (average 72.6 vs 65.5). So the gap depends on the subject. The boxes overlap a lot, so many girls and boys have similar scores. The lowest math score (0) belongs to a girl.

## V2 — Test prep impact on math
Q: Do students who completed test prep score higher in math?
A: Yes, students who finished test prep score higher in math. Their average is 69.7, compared with 64.1 for students with no prep. That is about 6 points more, and the difference is significant (p < 0.001). The 'none' group has more very low scores. But the two shapes overlap a lot, so test prep alone does not decide the score.

## V3 — Lunch type and average performance
Q: Does lunch type (standard vs free/reduced) relate to outcomes?
A: Students with standard lunch score higher in every subject. Their overall average is 70.8, compared with 62.2 for free/reduced lunch. The biggest gap is in math (about 11 points). Free/reduced lunch often means the family has less money. So family income seems linked to test scores, but this does not prove lunch causes it.

## V4 — Subject correlations
Q: How strongly do the three subjects move together?
A: All three subjects are strongly linked. Reading and writing are almost the same (r = 0.95). Math is also strongly linked to reading (r = 0.82) and writing (r = 0.80). This means a student who is good in one subject is usually good in the others. Math is a little less linked, maybe because it uses different skills.

## V5 — Math vs reading with trend lines by test prep
Q: How strongly are math and reading associated, and does test prep change the slope?
A: Math and reading are strongly linked (r = 0.82): higher reading usually means higher math. The completed group line has slope 0.84 (n=358). The none group line has slope 0.86 (n=642). The two lines are almost the same, and the difference is not significant (p = 0.61). So test prep does not change how math and reading are related.
