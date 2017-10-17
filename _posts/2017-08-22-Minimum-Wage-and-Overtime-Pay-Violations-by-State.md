---
layout: post
title: Minimum Wage and Overtime Pay Violations by State
author: China Layne
thumbnail: "/assets/MWTrendThumb.png"
tags: [employmentresearch, dataanalytics, researchsnippets]
---
I recently created a [dashboard](https://datastudio.google.com/open/0BwxrLDRuZ_WxaC1xMlNGd2xvd2c) to examine and illustrate minimum wage and overtime pay enforcement across states. Using this dashboard, I found a number of points of interest about wage enforcement in the U.S.

<h5 align="center">Dashboard of Minimum Wage and Overtime Pay Violations by State</h5>
[<img class="center" src="/assets/MWDashboard.png">](https://datastudio.google.com/open/0BwxrLDRuZ_WxaC1xMlNGd2xvd2c)

<h5 align="center">Minimum Wage and Overtime Pay Violations 2000 to 2015</h5>

<img class="center" src="/assets/MWTrend.PNG">

From 2005 to 2015, the number of investigations conducted nationwide by the [Wage and Hour Division (WHD)](https://www.dol.gov/whd/) decreased 20% from 20,825 to 16,612. However, during the same time period, the number of wage violations found during investigations increased slightly, from 533 to 542. These trends suggest WHD investigators have become more effective at uncovering wage violations.

In Oklahoma, 3.7 of every 1,000 workers were affected by a wage violation, a total of almost 5100 workers. The state with the second highest rate was North Dakota. The 1,100 workers affected by a wage violation represented 3.1 of every 1,000 workers in the state.

<h5>Map of Back Wages Owed by State</h5>

<img class="left" src="/assets/MWMap.PNG">

The average amount of back wages owed due to wage violations ranged from a low of $106 in Montana to a high of $1,928 in California. The states with the highest amount of back wages owed per affected worker were California, Wisconsin, Texas, Oregon, Arizona, and New Mexico.

These statistics are a few examples from the [dashboard](https://datastudio.google.com/open/0BwxrLDRuZ_WxaC1xMlNGd2xvd2c) I created. The dashboard includes three pages. The first page presents summary statistics of investigations, violations, and back wages owed. The second page presents detail and trend data on wage violations, as well as safety and health violation data. The third page presents state-level business and labor market information related to wage violations.

To create the dashboard, I combined data from four sources: public versions of the [Wage and Hour Investigative Support and Reporting Database (WHISARD)](https://enforcedata.dol.gov/views/data_summary.php), [Occupational Safety and Health Administration (OSHA) database](https://enforcedata.dol.gov/views/data_summary.php), along with data from the [County Business Patterns](https://www.census.gov/programs-surveys/cbp.html) and the [Current Population Survey (CPS) accessed from IPUMS](https://cps.ipums.org/cps/). I used Google's Cloud Platform products to create the dashboard: Cloud storage to store the data sets, BigQuery to query the data sets using SQL, and Data Studio to create the charts and draft the dashboard.

For a closer look at all of the information available, check out ["Minimum wage and overtime pay violations by state, 2015"](https://datastudio.google.com/open/0BwxrLDRuZ_WxaC1xMlNGd2xvd2c).
