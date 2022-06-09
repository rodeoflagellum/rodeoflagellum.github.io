---
layout: post
category: misc
title:  "Confirmed Cases of Monkeypox in Europe"
date:  2022-06-09 14:00:00 -0400
modified: 2022-06-09 14:07:00 -0400
permalink: "/europe_monkeypox/"
description: "A look at the number of monkeypox cases in Europe."
type: Forecast
status: Unresolved
---

<iframe src="https://www.metaculus.com/questions/embed/10978/" width="100%" height="300"></iframe>

The data source in the question is this spreadsheet: <https://docs.google.com/spreadsheets/d/1CEBhao3rMe-qtCbAgJTn5ZKQMRFWeAeaiXFpBY3gbHE/edit#gid=0>

A visualization of the data around 06/09/2022:

![](/notes/assets/2022/europe_monkeypox/case_count.png)

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

My rationale is the 

