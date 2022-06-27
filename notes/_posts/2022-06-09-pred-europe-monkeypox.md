---
layout: post
category: misc
title:  "Confirmed Cases of Monkeypox in Europe"
date:  2022-06-09 14:00:00 -0400
modified: 2022-06-26 14:07:00 -0400
permalink: "/europe_monkeypox/"
description: "A look at the number of monkeypox cases in Europe by July 1st 2022."
type: Forecast
status: Unresolved
tags: [prediction]
---

__Forecast Update 06/26/2022__: It's been awhile since I posted an update. I had intended to do this on the 17th, and have been updating on Metaculus almost every day, but have been too lazy to add to this post. In the previous written update and original entry, I made the mistake of only looking at confirmed cases, and not confirmed + suspected cases. As of (06/26/2022), there are x confirmed () and suspected () cases. My updates and the data are as follows. When the group of monkeypox questions resolve on July 1st 2022 on Metaculus, I will post my performances in a final update. 

![](/notes/assets/2022/europe_monkeypox/update3.png)

![](/notes/assets/2022/europe_monkeypox/monkeypox_confirmed_cases_europe_may-july_2022_june17a.png)

![](/notes/assets/2022/europe_monkeypox/monkeypox_confirmed_cases_europe_may-july_2022_june17b.png)

```python 

```

<br>

---

<br>

__Forecast Update 06/16/2022__: The number of confirmed Monkeypox cases in Europe is now somewhere around 2100. I've used best fit lines to explore 4 business as usual scenarios, and have updated my forecast in the following manner (note that I updated the forecast in one undocumented way before this update): 

![](/notes/assets/2022/europe_monkeypox/update2.png)

> - Expected Cases (BFL, May 20th) for June 30th: 3106.319999999998
- Expected Cases (BFL, May 6th) for June 30th: 2754.0889037433144
- Expected Cases (BFL, June 1st) for June 30th: 3370.305882352942
- Expected Cases (BFL, June 8th) for June 30th: 3443.3333333333358

![](/notes/assets/2022/europe_monkeypox/monkeypox_confirmed_cases_europe_may-july_2022_june16a.png)

![](/notes/assets/2022/europe_monkeypox/monkeypox_confirmed_cases_europe_may-july_2022_june16b.png)

Some updated code that produces the final of these graphs: 

```python 
import matplotlib.pyplot as plt
import numpy as np

plt.rcParams['text.usetex'] = True
plt.rcParams['text.latex.preamble'] = r''
plt.rcParams["font.family"] = "Times New Roman"

# this file is the copied and pasted dates from the spreadsheet that 
# is present in the question on Metaculus 
with open("dates_conf_06162022.txt", "r") as f:
    dlines = f.readlines()
    dlines = [elt.replace("\n",'') for elt in dlines if elt != "\n"]
    f.close()

d = {}
dates = sorted(set(dlines))
for elt in dates:
    d[elt] = dlines.count(elt)

fig = plt.figure(figsize=(9.5,6))
ax = fig.add_subplot()

ax.set_title("Total Monkeypox Cases in Europe, May-June 2022", fontsize=17.0)
ax.set_ylabel("Case Count", fontsize=15.0)

days = [elt.replace("2022-", "") for elt in list(d.keys())]

ax.plot(
    days, 
    list(d.values()), 
    label="Cases Each Day", 
    color='cyan',
    marker='o',
    markersize=4.0,
    markeredgecolor='black',
    markeredgewidth=1.0,
)

ax.plot(
    days, 
    np.cumsum(list(d.values())), 
    label="Cumulative Cases", 
    color='blue',
    marker='o',
    markersize=4.0,
    markeredgecolor='black',
    markeredgewidth=1.0,
)

date_counts = list(range(len(list(d.keys()))))
days.extend([f"06-{elt}" for elt in list(range(16+1, 30+1))])

# line of best fit for all days 
plt.plot(days, np.poly1d(np.polyfit(date_counts[8:], np.cumsum(list(d.values()))[8:], 1))(list(range(len(days)))), color='red', label="Since May 20")
plt.plot(days, np.poly1d(np.polyfit(date_counts, np.cumsum(list(d.values())), 1))(list(range(len(days)))), color='green', label="Since May 6th")
plt.plot(days, np.poly1d(np.polyfit(date_counts[-16:], np.cumsum(list(d.values()))[-16:], 1))(list(range(len(days)))), color='pink', label="Since June 1st")
plt.plot(days, np.poly1d(np.polyfit(date_counts[-8:], np.cumsum(list(d.values()))[-8:], 1))(list(range(len(days)))), color='orange', label="Since June 8th")

print(f"Expected Cases (BFL, May 20th) for June 30th: {np.poly1d(np.polyfit(date_counts[8:], np.cumsum(list(d.values()))[8:], 1))(list(range(len(days))))[-1]}")
print(f"Expected Cases (BFL, May 6th) for June 30th: {np.poly1d(np.polyfit(date_counts, np.cumsum(list(d.values())), 1))(list(range(len(days))))[-1]}")
print(f"Expected Cases (BFL, June 1st) for June 30th: {np.poly1d(np.polyfit(date_counts[-16:], np.cumsum(list(d.values()))[-16:], 1))(list(range(len(days))))[-1]}")
print(f"Expected Cases (BFL, June 8th) for June 30th: {np.poly1d(np.polyfit(date_counts[-8:], np.cumsum(list(d.values()))[-8:], 1))(list(range(len(days))))[-1]}")


print(f"Total confirmed Moneypox cases, as of June 16th: {np.cumsum(list(d.values()))[-1]}")
print(f"Cases by day: {d}")

ax.set_xticklabels(labels=days, rotation=90)

plt.savefig('monkeypox_confirmed_cases_europe_may-july_2022_june16c.png', dpi=300)
plt.legend()
plt.show()
```

<br>

---

<br>

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
