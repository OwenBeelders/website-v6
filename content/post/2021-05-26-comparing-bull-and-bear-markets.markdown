---
title: Comparing Bull and Bear Markets
author: Owen Beelders
date: '2021-05-26'
slug: comparing-bull-and-bear-markets
categories: []
tags: []
---

## Comparing Bull and Bear Markets

In the previous [post](https://owenbeelders.netlify.app/2021/05/23/seriation/), we reviewed the structure of the correlation matrix during a bull market. We found that fixed income and equity assets formed two distinct asset classes and each highly correlated within the asset class. In the post we calculate and order the correlation during a bear market and compare it to the correlation matrix during a bull market.

## What do we learn from the analysis below?

1. The correlation between asset classes changes according to the state of the market.
2. During the bull market, fixed income and equity assets formed two distinct groups and asset classes are highly correlated within each group.
3. During the bear market, the fixed income asset classes are bifurcated into those without credit risk and those with credit risk.
4. During the bear market, the treasury etfs are most negatively correlated with the equity etfs. TIPS, GNMA and MBS that have no credit risk have a lower negative correlation with equities while Barclays Agg, Munis and the LQD index, that have more credit risk have a positive correlation with equities. HY is also positively correlated with equities and so is CMBS.
5. The two take-aways from this analysis are first, that only treasures have a strong negative correlation with equities during a bear market, and second, the return from the fixed income assets should compensate you for both duration and credit risk because in a bear market the true credit risk will be revealed.
















## Bear Market: 6/1/2007-6/30/2009

* Large Cap equities trend down during this sample period with an especially large drop in 2008.
* In the scree plot of the eigenvalues, the first eigenvector explains 43%, the second explains 23% and the remaining eigenvectors a much smaller proportion of the variation.
* The first eigenvector captures the difference between equities and fixed income while the second eigenvector reflects the systemic shock that impacts all assets during this period.
* The third eigenvector has large weights on HY, the LQD, Muni and Agg indexes; this may reflect the combination of both credit risk and duration risk in these asset classes.
* In the Scatterplot of the first and second eigenvector, equities and treasures continue to be at the two ends of the spectrum, but there is more differentiation between the other asset classes.
* In the correlation matrix that has been ordered by the first principal component (FPC), we see three distinct groups: equities in the top left, treasuries in he bottom right and the middle is occupied by the asset classes that have both equity and credit risk or contain other types of risk, e.g. Muni's. The other feature that stands out in the bottom left and top right is the negative correlation between treasuries and equities.
* When the correlation matrix is ordered by the AOE, the treasuries and equities stand out as groups that have high positive correlation within each group and negative correlated between the groups. The asset classes ordered from LQD through TIPS are all fixed income and are having varying levels of correlation with treasuries and the lower the correlation with treasuries, the less negative the correlation with equities.

<img src="/post/2021-05-26-comparing-bull-and-bear-markets_files/figure-html/crash-1.png" width="672" /><img src="/post/2021-05-26-comparing-bull-and-bear-markets_files/figure-html/crash-2.png" width="672" /><img src="/post/2021-05-26-comparing-bull-and-bear-markets_files/figure-html/crash-3.png" width="672" /><img src="/post/2021-05-26-comparing-bull-and-bear-markets_files/figure-html/crash-4.png" width="672" /><img src="/post/2021-05-26-comparing-bull-and-bear-markets_files/figure-html/crash-5.png" width="672" /><img src="/post/2021-05-26-comparing-bull-and-bear-markets_files/figure-html/crash-6.png" width="672" /><img src="/post/2021-05-26-comparing-bull-and-bear-markets_files/figure-html/crash-7.png" width="672" /><img src="/post/2021-05-26-comparing-bull-and-bear-markets_files/figure-html/crash-8.png" width="672" /><img src="/post/2021-05-26-comparing-bull-and-bear-markets_files/figure-html/crash-9.png" width="672" />


