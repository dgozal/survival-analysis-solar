# Survival Analysis: Solar Panel Tax Credits

Not everyone feels the same way about the pace of adopting renewables. Some want it quick, some want it slow. Using data from the [correlates of state policy](http://ippsr.msu.edu/public-policy/correlates-state-policy), we can see what factors differentiate states that move faster or slower in implementing a piece of pro-renewables policy: solar panel tax credits. 

A nifty way of approaching this is to use survival analysis, which is usually used to model the chances at which certain entities will continue to "survive" as time passes. By designating "survival" here as a continuation of the status quo - that is, no solar panel tax credits (in which case "death" is simply the implementation of solar tax credits) - we can use survival analysis to study the determinants of state behavior in when it chooses to implement this piece of policy (if it ever does).

The above is implemented using R, and is a slightly modified version of previous coursework I did in college. 

## Instructions
You will only need the R Markdown and csv file attached to re-run my analysis. Detailed explanations are provided in the R Markdown file attached. Data from the correlates of state policy are downloaded through their API, which is directly incorporated in the attached Markdown file.
