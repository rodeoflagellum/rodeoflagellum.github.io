---
layout: post
category: misc
title:  "Confirmed Cases of Monkeypox in Europe"
date:  2022-06-09 14:00:00 -0400
modified: 2022-06-09 14:07:00 -0400
permalink: "/europe_monkeypox/"
description: "A look at the number of monkeypox cases in Europe by July 1st 2022."
type: Forecast
status: Unresolved
tags: [prediction]
---

<iframe src="https://www.metaculus.com/questions/embed/10978/" width="100%" height="300"></iframe>

The data source in the question is this spreadsheet: <https://docs.google.com/spreadsheets/d/1CEBhao3rMe-qtCbAgJTn5ZKQMRFWeAeaiXFpBY3gbHE/edit#gid=0>

A visualization of the data around 06/09/2022:

![](/notes/assets/2022/europe_monkeypox/case_count.png)

More specifically (from [my Metaculus comment](https://www.metaculus.com/questions/10978/total-monkeypox-cases-in-europe-july-1-2022/#comment-94616)): 

> {'2022-05-06': 1, '2022-05-12': 1, '2022-05-13': 1, '2022-05-15': 4, '2022-05-17': 3, '2022-05-18': 21, '2022-05-19': 16, '2022-05-20': 46, '2022-05-21': 16, '2022-05-23': 73, '2022-05-24': 34, '2022-05-25': 44, '2022-05-26': 88, '2022-05-27': 51, '2022-05-28': 16, '2022-05-29': 15, '2022-05-30': 123, '2022-05-31': 66, '2022-06-01': 83, '2022-06-02': 125, '2022-06-03': 94, '2022-06-04': 7, '2022-06-06': 112, '2022-06-07': 97}
> 
> Cumulative sum of confirmed cases: [ 1 2 3 7 10 31 47 93 109 182 216 260 348 399 415 430 553 619 702 827 921 928 1040 1137]
> 
> Differences between cumulative cases: [ 1 1 4 3 21 16 46 16 73 34 44 88 51 16 15 123 66 83 125 94 7 112 97]

My code:

```python
import matplotlib.pyplot as plt
import numpy as np

plt.rcParams['text.usetex'] = True
plt.rcParams['text.latex.preamble'] = r''
plt.rcParams["font.family"] = "Times New Roman"

with open("dates_monkey_pox_of_06092022.txt", "r") as f:
    dlines = f.readlines()
    dlines = [elt.replace("\n",'') for elt in dlines if elt != "\n"]
    f.close()
    

d = {}
dates = sorted(set(dlines))
for elt in dates:
    d[elt] = dlines.count(elt)

fig = plt.figure(figsize=(9.5,6))
ax = fig.add_subplot()
ax.set_xticklabels(labels=list(d.keys()), rotation=45)
ax.set_title("Total Monkeypox Cases in Europe by July 1, 2022", fontsize=17.0)
ax.set_ylabel("Case Count", fontsize=15.0)

ax.plot(
    list(d.keys()), 
    list(d.values()), 
    label="Cases Each Day", 
    color='cyan'
)

ax.plot(
    list(d.keys()), 
    np.cumsum(list(d.values())), 
    label="Cumulative Cases", 
    color='blue'
)

plt.show()
```

As of 06/09/2022, my forecast is as follows: 

![](/notes/assets/2022/europe_monkeypox/monk_for_06092022.png)

My rationale for this present forecast:

- If cases the number of confirmed cases became 100 per day on average for the rest of the month, there'd be an additional 2300 cases, implying a rough case count of 3.3k total by July 1st. This seems plausible.
