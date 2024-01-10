# Exploring Why Civil Resistance Works
---
#### This is a civil_resistance analysis, machine learning project for the course "Applied Machine Learning" of the 7th semester in "Department of Management Science and Technology" of "Athens University of Economics and Business".
---
In this assignment, you will replicate some of the findings of a well-received book, [Why Civil Resistance Works](https://www.ericachenoweth.com/research/wcrw) by [Erica Chenoweth](https://www.ericachenoweth.com/) and Maria J. Stephan. The two authors examined whether nonviolent campaigns are more effective than violent campaigns. They found that yes; from a data set containing details of campaigns from 1900 onwards, they found that in general peaceful campaigns are more effective in achieving their aims than violent ones.

Following the initial publication of the book in 2011, Erica Chenoweth continued her research on the topic and published a follow-up ten years later, [Civil Resistance: What Everyone Needs to Know](https://www.ericachenoweth.com/research/civil-resistance-what-everyone-needs-to-know). She has also continued to update the data used for her research.

The research became famous for propising the 3.5% rule: "the claim that no government has withstood a challenge of 3.5% of their population mobilized against it during a peak event"; you can find a nice overview at [Questions, Answers, and Some Cautionary
Updates Regarding the 3.5% Rule](https://carrcenter.hks.harvard.edu/files/cchr/files/CCDP_005.pdf). Among other things, you will investigate that rule.

To answer the questions, you will use that data, the [Nonviolent and Violent Campaigns and Outcomes (NAVCO) Dataset](https://dataverse.harvard.edu/dataverse/navco), and in particular the [NAVCO 1.2 Dataset](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/0UZOTX). You will also use data from the [Polity Project](https://www.systemicpeace.org/polityproject.html), in particular the Polity5 version, available from [Integrated Network for Societal Conflict Research (INSCR) ](https://www.systemicpeace.org/inscrdata.html), in particular the [Polity5 Annual Time-Series, 1946-2018](http://www.systemicpeace.org/inscr/p5v2018.xls).

## 1. Exploration of Historical Trends
* *Create a plot showing the frequency of nonviolent and violent campaigns; the frequency should be counted based on their end years, at decades. The violent and nonviolent campaign counts should be stacked on each other.*

* *Create a plot showing, for each decade from 1940 onwards, the number of nonviolent campaigns and the percentage of success. Your plot will have two vertical axes, one for each of the metrics.*

* *Create a plot showing the success rate for violent and nonviolent campaigns by decade. Your plot should show that nonviolent campaigns have higher success probabilities.*

## 2. Largest Resistance Campaigns, 1946-2014
* *Create a horizontal bar plot with the resistance campaigns, for all years, with a percentage of participation at least 2.0%. Investigate, outside the largest resistance campaigns, if you can find anything about Greece.*

## 3. The Effect of Participation on the Probability of Campaign Success

* *Examine the effect of participation on the probability of campaign success. You should run a logistic regression for success on membership per capital, controlling for the location’s logged population the year the campaign ends. Explain your results.* 

* *Having done that, create a scatter plot showing the logged participants per capital, on the $x$ axis, and the probability of success, on the $y$ axis. Explain it as best you can.*

* *Then, do the same but with only the membership per capital as dependent variable. Explain why this plot is different than the previous one.*
## 4. The Level of Participation Tipping Point
* *As we mentioned above, a famous output of the research is the 3.5% rule regarding the population participation in a campaign and the probability of success.Based on your data, create a table and explain how Chenoweth came up with the rule.*
* *Apart from the way Chenoweth came up with the rule, we can derive it in more statistically-based way. From the results you obtained in the previous question, find the percentage of the population that is the tipping point for success in a campaign with 99% probability.*
