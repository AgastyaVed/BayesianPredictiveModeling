## Bayesian Predictive Modeling

### Customer valuation
GetFit is a company that runs outdoor health ftness classes. The classes run on a monthly cycle
that begins on the frst day of each month. New customers are “booked” at the beginning of the
month, and decide to renew or cancel just before the beginning of the next month. For example, a
cohort that is acquired initially on January 1 will be active for all of January. Just before February
1, some members of the January cohort will renew (and will be active in February), while others
will cancel. By defnition, those who cancel have been active for one month, while those who renew
are active for at least two months. At the end of February, some members of the January cohort
will renew for March (active for at least three months), while others will cancel (active for exactly
two months).
GetFit acquired 2,132 new customers for January. These customers can be considered to be a
random sample from the population of potential GetFit customers. It is now the end of September.
The following table shows how many of those customers were active in each month since acquisition.

|Month          |Active         |
| ------------- |:-------------:| 
|January        |2,132          |
|February       |1,406          |
|March          |1,069          |
|April          |894            |
|May            |765            |
|June           |656            |
|July           |578            |
|August         |525            |
|September      |482            |

Answer the following questions. Maintain the assumptions of the beta-geometric (BG) model for all of your answers.
1. Estimate a BG model using the customer count data for GetFit’s January cohort. Report the
maximum likelihood estimates (MLE) of the model parameters, and well as the log likelihood
at the MLE.
2. Consider a randomly-chosen member of the population who was newly acquired in January.
(a) What is the expected probability that this customer will cancel service after only one
month?
(b) What is the expected probability that this customer will cancel service after two months?
(c) Suppose this customer renewed his membership for February. What is the expected
probability that he will renew for March?
(d) What is the expected renewal probability for a customer who remained active through
August?
(e) How many members of the cohort do we expect to be active through the end of the year?

3. GetFit will acquire 2,132 new customers in September, October, November and December.
These customers are all random samples from the same population as the January cohort.
The company wants to estimate the total number of customers from these new cohorts that
they will have in each month, through August of the next year. Clearly, there are no surviving
October customers in September, November customers in September or October, etc.
(a) Using your inferences about the population that you derived from the January cohort,
complete the table below (i.e., use predicted counts from the BG model).

|Month     |Sept   |Oct.    |Nov.   | Dec.  | Total
| -----|:-----:|-----:|-----:|-----:|-----:|     
|Sep |2,132 | | | |2132
|Oct | |2,132        |
|Nov | | |2,132          |
|Dec | | |  |2,132            |
|Jan            |
|Feb           |      |
|Mar           |           |
|Apr        |           |
|May      |           |

(b) Examine the retention rates from January to August for each cohort, and for the aggregated customer base. How do the implied shapes of the retention curves diﬀer? Give an
intuitive explanation of these patterns. You do not need to create plots of the retention
curves (although that might be helpful). Only a discussion of changes in retention rates
is necessary
