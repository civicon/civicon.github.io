---
layout: post
title: "Developed a (random) election projection method (Assignment)"
description:
tags:
- democracy
- elections
- statistics
categories:
- blog
- research
permalink: /2005/10/21/election_projection/
lang: en
image:
  feature:
  caption:
  captionlink:
  credit:
  creditlink:
  location:
  locationlink:
---

The first project of this semester’s transdisciplinary University Studies Course on “[Mathematics and Democracy](http://www.jacobs-university.de/academics/courses/Fall_2005/USC/020008_1/)” was to develop and document an election projection method.
My colleagues Anna Kristina Bautista, [Matthias Bröcheler](http://www.matthiasb.com), Ivelina Grozeva, Nora Lücke, [Adina Luican](http://www.physics.rutgers.edu/~aluican/) and me decided to implement a voter movement analysis.
The method employs statistical models to estimate voter movements between parties in the selected (few) election precincts to arrive at a projection for the entire constituency.
Matthias devised and implemented the procedure using [Matlab](http://www.mathworks.com/).

<!--more-->

<figure>
    <a href="http://dl.dropboxusercontent.com/u/5341489/images/election-projection.jpg"><img src="http://dl.dropboxusercontent.com/u/5341489/images/election-projection.jpg"></a>
</figure>

Two questions prominent in real-life election projection remained:
what was to be done with absentee voters?
Which precincts should be selected for faster counting to enter the projection earliest?

We ran several inferential statistics (regression, mean comparisons) to inform our decisions.
We could show that absentee-voters differed significantly in their voting preferences from other voters.
Since it was however not possible to map those ballots to certain precincts, they were excluded from the projection altogether.

For precinct selection, it appears intuitive to select those that were closest to the actual result during the last election.
Surprisingly, however, we found empirically that selecting those precincts yielded poorer results when compared to a simple random selection of precincts.
The scatterplot above provides a possible explanation for this counter-intuitive finding.
It appears that the vote share of one party per precinct is not independent of the deviation from the overall result of that precinct during the last election.
While to some degree, the observed effect may be a statistical artifact (deviations from normality, autocorrelation) the strength of some of the effects (R2 = .23) suggests that the relationship is real.
Possible explanations for this effect may involve the different volatility of voting preferences per precinct, the share of swing voters and the presence of party strongholds.

Update (2014): It occured to me, this might simply be a case of [regression to the mean](http://en.wikipedia.org/wiki/Regression_toward_the_mean).

In the end we arrived at a very precise model that was able to predict the overall result with a marginal error of less than 1% when only the data from 20 out of 1554 precincts was available.

Despite the rather dry and technical nature of this project, I enjoyed very much working on it and cooperating with my colleagues.
The project further incited my interest in quantitative methodology.

Please find attached the complete [essay](http://dl.dropboxusercontent.com/u/5341489/images/documentation_a-bautista-m-broecheler-i-grozeva-n-luecke-a-luican-m-held.pdf) available for download.