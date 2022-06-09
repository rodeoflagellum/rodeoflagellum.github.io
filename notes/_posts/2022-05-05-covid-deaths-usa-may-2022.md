---
layout: post
category: misc
title:  "US SARS-CoV-2 Deaths May 2022"
date:  2022-05-05 13:00:00 -0400
modified: 2022-06-09 14:09:00 -0400
permalink: "/pred_covid_deaths_usa_may_2022/"
description: "My estimate for how many deaths there will be from SARS-CoV-2 during the month of May 2022."
tags: [prediction]
type: Forecast
status: Unresolved
---


__Resolution Update 06/09/2022__: The actual number of COVID deaths in the US for May was around 9479 (993205 for May 1, 1002684 for May 31; see <https://covid.cdc.gov/covid-data-tracker/#trends_totaldeaths>). I should have used the rationale below as just one of many scenarios in some meta-model, rather than just relying on the single model. For context, the rest of this post was written on May 5th 2022. 

<br>

---

<br>

Recently, I submitted an application to participate in an upcoming existential risk forecasting tournament that is being hosted by [Philip Tetlock][tetlock]. Here is a quote-chunk from the application to the tournament:

> Some background information about us: Our research team is based at the University of Pennsylvania (PI: Phil Tetlock) but spans a range of disciplines and perspectives. Our core objective is to help the Effective Altruism community (and society at large) to develop better methods of improving high-stakes debates. The Hybrid Persuasion-Forecasting Tournament will focus on potential threats to humanity in the next century, with a focus in this round on AI, biosecurity, climate, and nuclear war in the short-term (<3 years), medium-term (10 years), and long-term (30+ years).
>
In this initial survey, we ask about your familiarity with existential risk debates and about your baseline beliefs. We also explore your interest in participating in a 3-4 month tournament beginning in late early May. We expect this survey to take roughly 45 minutes. As thanks, we will give you the chance to win a $2,000 prize (ten respondents will be chosen and the chances of winning will rise as a function of the accuracy of your answers to some of the forecasting questions in this survey. We will explicitly label in this survey those questions that affect your probability of winning one of these prizes).

There were many questions in the initial survey, and one was a short-term forecasting question on how many deaths from COVID-19 there would be during May 2022 in the US. I did not spend much time forecasting this, and made use of no models. My final prediction was ~5111 deaths, but I intuitively felt this was somewhat too low; my monkey brain (then and now) put the number of deaths at around 7000.

At the time of writing this, there have already (in the first 3 days of May) been around 700 deaths, and the 7-day moving average of deaths appears to be increasing. All of this means that my estimate might be (and probably is) very incorrect.

Here is the process that I used on April 27th to produce the estimate that ~5111 deaths would occur during May 2022 in the US. The data (for the year 2022) applies only to the US.

__Mean and Standard Deviation of Deaths in Recent Months__

- February: mu = 2204.535, sigma = 1091.020
- March: mu = 983.48, sigma = 553.128
- April: mu = 382.96, sigma = 252.8269

__Trends in the Monthly Death Means__

- 983.48/2204.53 = 0.4461, so the March mean deaths is (0.4461 * February's mean deaths)
- 382.96/983.48 = 0.3893, so the April mean deaths is (0.3893 * March mean deaths)
- 0.3893/0.4461 = 0.8728
- 0.3893 * 0.8728 = 0.33978104, so maybe the May mean deaths is (0.33978104 * April mean deaths)
- Solve for x, where x/382.96 = 0.33978104, so x = ~130.12 (May mean deaths is ~130.12)

__Trends in the Monthly Death Standard Deviations__

- 553.128/1091.020 = 0.50698, so the stdev of deaths in March is (0.50698 * February's stdev deaths)
- 252.8269/553.128 = 0.4570, so the stdev of deaths in April is (0.4570 * March's stdev deaths)
- 0.4570/0.50698 = 0.9014
- 0.4570 * 0.9014 = 0.4119, so maybe the stdev of deaths in May is (0.4119 * April stdev deaths)
- Solve for x, where x/252.8269 = 0.4119, so x = ~104.149 (May death stdev is ~104.149)

Then, doing something like

```python
import numpy as np

monthly_vals = np.random.normal(130.12, 104.149, 31)

# Example output
# array([128.42431429,  78.38993176,  71.77143205, 131.54965954,
#        189.12920174,  80.21024541,  82.75818607, -90.7467262 ,
#        101.12166349,  98.69571877,  67.42117963, 165.83316837,
#         69.98723109,  79.92760326, 269.42842133, 216.51840295,
#        128.90362437, 188.59075136,  92.26024829, 206.20132867,
#        -94.27513434, 111.46428368,  85.03100137,  71.39397795,
#         52.35132579, 198.25977959, 338.97957582, 253.86400065,
#         43.87721903, 228.51099212, 226.88060853])

monthly_count = sum(abs(monthly_vals))

# Taking the absolute value of this (since the deaths cannot go negative)
#       produces something like
# 4242.756937503337
# When I performed this on for the application, I got around 4350
```

After I got this final value, I thought that it seemed too low (only 4350 deaths, really?), so I decided to multiply it by 1.175, which brought the final estimate to around ~5111 deaths. In hindsight, I probably should have multiplied it by something like 1.40, given that I was uncertain whether this year's "inflection" point (during mid-June 2020 and 2021 there was a substantial increase in COVID-19 cases and deaths following a period of gradual decline; I dub this the late Spring inflection point) might have moved to May.

One friend of mine just did 260 * 31 and put ~8060; it would be very funny if he was much closer with this 1 minute estimate than I was, but that's how life sometimes works. Hopefully my prediction is correct, as that would mean fewer lives actually end up being lost.

[tetlock]: https://en.wikipedia.org/wiki/Philip_E._Tetlock "https://en.wikipedia.org/wiki/Philip_E._Tetlock"

[cdc]: https://covid.cdc.gov/covid-data-tracker/#trends_dailydeaths "https://covid.cdc.gov/covid-data-tracker/#trends_dailydeaths"
