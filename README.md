# Jeloo
<div style="text-align: center;"><a></a><br /></div>

### Table of Contents

- [Description](#description)

---

## Description

This is an elo-based ranking for the high school division nationwide in Science Olympiad. 

I spent the summer of 2023 hand-scrapping state websites, looking at each state's state competition from the past seven years. If a state had data for their state competition for the past seven years and a school within that state had qualified for the state competition 5/7 times, they would be qualified to be ranked. 

Based on participation, national spots, and other factors, I gave each state a score that represented how hard it was to do good in each state. Of course, this has some subjectivity due to the data I choose to use and the data I choose to use and not use, but I accept that. Then I calculated the elo of each school within each state based on how they did at their state competition over the past seven years. I did consider recent tournaments more critical than previous ones, so I implemented a 10% exponential loss for each year extracted from 2023. 

From this, I took teams that had qualified for the national tournament and created an expected score that a team given a certain elo should score at nationals, then I compared this to how the teams actually did, adjusting the delta based on how far we were removed, from the competition. 

#### Technologies

- HTML, CSS, JS
- Python
- Excel

---

