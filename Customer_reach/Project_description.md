### Predicting customer reach using probabilistic models 

#### Probabilistic models used: 
Beta Binomial, Negative Binomial Distribution, Exponential Gamma distribution, Weibull-gamma

1. Joyful Voyages runs vacation cruises to various destinations around the world. In 2006, the company
acquired a new cohort of 18,402 customers who took their frst cruise that year. The cruises.txt fle
records all 25,257 cruises taken by this cohort from 2006 to 2010. By defnition, all customers take a cruise
in the year in which they are acquired (in this case, 2006), so we are modeling only the repeat cruises. For
all parts, assume an annual discount rate of 13%.

(a) Under the assumptions of the BG-BB model, customers may be in either an “active” or “inactive”
state. Describe the distributions of customers’ propensities to take a cruise while in the active state,
and the propensity to transition to an inactive state at the start of each year. Include in your discussion
the the means of the latent parameters, and an assessment of how those parameters vary across the
population.

(b) Suppose that the company acquires a new cohort, with similar characteristics to the 2006 cohort. After
the cohort takes its initial cruise, how many repeat cruises can we expect from the cohort in the next
1, 2, 3, 4, and 5 years?

(c) The company often acquires new customers through targeted online marketing campaigns. It believes
that in an uncoming campaign, it can acquire 1,500 new customers. What is the most that the company
should spend on that campaign? Since the customers have not yet been acquired, payment for the
frst cruise has not yet been made. However, once the customer is acquired, the frst payment will be
certain and immediate.

(d) At the end of the 2010 cruising season, what was the expected residual lifetime value of the 2006
cohort?

2. Using data from text fle, khakichinos.txt, that contains Internet visit data for a sample of 2,728
comScore/Media Metrix panelists who visited at least one online apparel site in the second half of 2008.
This dataset shows the number of visits that each person made at one particular site (with the disguised
name of khakichinos.com) in January, 2009. Ignore the covariate data (the demographic information) for
now.
(a) Fit an NBD model to the data. What do the parameter estimates tell us about the diﬀerent kinds of
customers in the Khakichinos customer base?

(b) Plot the expected reach of the khakichinos website as a function of time, from 0 to 36 months. What
is the expected reach during 12 months?

