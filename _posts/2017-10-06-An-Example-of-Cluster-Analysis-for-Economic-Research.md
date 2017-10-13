---
layout: post
title: An Example of Cluster Analysis for Economic Research
tags: 
- employment 
- occupations 
- economics
- clusteranalysis 
- datareduction
- dataanalytics
- researchsnippets
---
![Supplemental Classification Graphic]({{ "/assets/SCGraphic.PNG"}})

Many types of important economic and sociological research include occupation as a predictor or control variable. However, the commonly used Census occupational classification has too many detailed occupations to include as individual predictors in most models. To resolve this issue, I used [cluster analysis](https://datastudio.google.com/open/0BwxrLDRuZ_WxUjFMMXZlMXQyM2s) to reduce the 483 detailed Census occupation codes used in [IPUMS CPS](https://cps.ipums.org/cps/index.shtml) into a smaller set of occupational categories that can be more useful in economic research.

Researchers generally include occupation in analyses using 12 major occupational groups. This classification groups detailed occupations primarily according to common job families, such as business and finance occupations or office administration occupations. Alternatively, I wanted to use a classification that groups detailed occupations based on the common employment experiences of workers in those occupations. My goal was to produce a Supplemental Classification that would provide clearer measures of the effect of occupation on different types of economic outcomes.

![Supplemental Classification Categories]({{ "/assets/SCCategories.PNG"}})

To create the Supplemental Classification, I clustered detailed occupations based on workers' common employment experiences along seven dimensions: (1) job family, (2) education level, (3) management tasks, (4) earnings, (5) unemployment in the previous year, (6) full-time, year-round employment in the previous year, and (7) benefits (such as health insurance and retirement plan). I used data from the 2014 and 2015 Current Population Survey’s Annual Social and Economic Supplement for the cluster analysis. I used a hierarchical, agglomerative method with weighted average linkage to produce a classification scheme with 15 clusters. The graphic above lists the occupational categories included in the Supplemental Classification.

To test the effectiveness of the cluster analysis at producing more coherent occupational groups, I compared the [coefficient of variation (CV)](https://stats.idre.ucla.edu/other/mult-pkg/faq/general/faq-what-is-the-coefficient-of-variation/) from the Supplemental and Job Family classifications for each of the seven employment experiences used in the cluster analysis. For every employment experience except education level, the mean CV across occupational categories is smaller for the Supplemental Classification than for the Job Family Classification. Overall, the Supplemental Classification groups together detailed occupations that are much more similar to each other across multiple employment experiences than does the Job Family Classification.

![Supplemental Classification CV]({{ "/assets/SCCV.PNG" }})

I also tested the performance of the Supplemental Classification compared to the Job Family Classification by examining their correlations with various employment factors and outcomes. Both the Job Family and Supplemental occupational classifications were negatively correlated with 2016 labor force participation and total family income. For instance, people whose most recent occupation was in a higher number category (i.e. non-professional services and goods producing occupations) were less likely to be in the labor force in 2016. However, the Supplemental classification was more strongly correlated with both economic outcomes compared to the Job Family classification.

Overall, the Supplemental Classification scheme provides a viable alternative for using occupation as a predictor or control variable in economic research. For more detailed information on the Supplemental classification, see the interactive brief: ["Supplemental Occupational Classification"](https://datastudio.google.com/open/0BwxrLDRuZ_WxUjFMMXZlMXQyM2s).
