Download Link: https://assignmentchef.com/product/solved-econometrics-ii-a-university-introduces-a-housing-program
<br>
A university introduces a housing program which offers student housing to secondyear students who in their first year have a grade point average (GPA) exceeding 8.0. A researcher applies a difference-in-differences model to estimate the effect of this housing program on academic achievement. The treatment group contains students with a first-year GPA between 8.0 and 9.0, the control group includes students with a first-year GPA between 7.0 and 8.0. The researcher uses as outcomes the first-year GPA (before treatment) and the second-year GPA (after treatment) of the students. Does this approach give a consistent estimator for the causal effect of the housing program? Briefly explain your answer.

<h1>Problem 2</h1>

Even though not everyone likes to think about it in that way, the marriage market is a market like all markets, where demand and supply can have an influence on market outcomes. What is often seen as an important determinant of marriage market outcomes is the sex ratio, the ratio of men to women in the population. The prediction would be that the position of men in the marriage market improves with a reduction in de sex ratio (and vice versa). In this exercise we look at the impact of male scarcity on out-of-wedlock births. Such births could reflect men having more partners or men being able to shift the cost of child rearing to single mothers.

The dataset marriagemarket.dta contains data on the percentage of out-ofwedlock births in France in 91 departments, both before and after World War I (the variable illeg). The variable post indicates whether this percentage is measured before or after the war, mortality is the military mortality rate during the war and sr is the sex ratio (#males 18-59/#females 15-49). Finally, depc is the department code for the 91 departments.

<ul>

 <li>Regress the number of out-of-wedlock births on the sex ratio, using only the observations from the pre-war period. Discuss your result. How can a difference-in-differences approach using the military mortality rate during WWI improve on this estimation strategy?</li>

 <li>Generate a dummy variable that indicates wether the military mortality in a region is above the median military mortality or not. Make a table with the mean percentage of out-of-wedlock births for the high and low mortality regions, both before and after the war. Use the numbers from the table to calculate the difference-in-differences estimator.</li>

</ul>

The variable mortality is actually a continuous variable. In a regression we will therefore use it as a continuous treatment variable.

<ul>

 <li>Estimate the following model, which estimates the difference-in-differences estimator in a regression equation. What is the interpretation of the coefficients <em>β</em><sub>1 </sub>and <em>β</em><sub>2</sub>? What do you conclude about the effect of male scarcity on the number of out-of-wedlock births?</li>

</ul>

illeg = <em>β</em><sub>0 </sub>+ <em>β</em><sub>1</sub>post × mortality + <em>β</em><sub>2</sub>post + <em>u</em>

<em>In order to run this regression you will first have to create a new variable that is equal to post </em>× <em>mortality</em>

<ul>

 <li>Run the same regression but now include dummies for all the departments. Discuss your results. Do you prefer this estimation over the estimation of question iii)? Why?</li>

 <li>What is the key assumption when you apply difference-in-differences? What would be a way to investigate the plausibility of this assumption? Why is that not possible with this dataset?</li>

</ul>