# 🔥 Work From Home Burnout Analysis

This project looks into what actually causes burnout in remote workers. I wanted to find out whether it's the number of hours worked, lack of sleep, too many meetings — or something else entirely. The results turned out to be pretty surprising.

---

## What it's about

The dataset contains daily records from 180 remote employees. Each record describes a single day — how many hours the person worked, how much time they spent in front of a screen, how many meetings they had, whether they took breaks, how they slept, and how efficiently they completed their tasks. Each record also includes a burnout score and a risk category (Low / Medium / High).

---

## What I explored

I started by looking at basic averages — how many hours people work on weekdays vs weekends and how their productivity differs. Then I compared groups by burnout risk level to see what sets them apart.

The core part of the analysis was a correlation study — I wanted to find out which metric has the biggest impact on burnout.

---

## How I did it

- **Boolean filtering** to isolate specific groups (High / Medium / Low burnout risk, Weekday / Weekend)
- **Groupby + aggregation** to count users in each burnout category
- **Means and medians** to compare behavior across groups
- **Correlation analysis** between individual work metrics and the burnout score
- **Visualizations** — bar charts for group comparisons, pie chart for burnout risk distribution

---

## What I found

The biggest surprise was that task completion rate turned out to be by far the strongest predictor of burnout — much more than work hours or screen time. People who get things done efficiently tend to have significantly lower burnout scores. Work hours and screen time do play a role, but a much smaller one. Sleep, interestingly, showed almost no direct relationship with burnout in this dataset.

---

## Tools used

- Python
- pandas
- matplotlib
- numpy

---

*Part of my Data Analytics portfolio.*
