### Probabilistic marketing models

1. Take the parameter estimates for the NBD, and NBD with HCNB models from the coﬀee creamer
example that is described in the data in question1 of the markdown file.

The penetration of a consumer good is the proportion of the target segment that purchases at least
one unit during some period of time. It is the analog to “reach” from media metrics.

(a) What do each of the models predict will be the penetration of coﬀee creamer purchases after 1
period? What about after 5 periods? 26 periods?

(b) If you were the product manager for this particular brand of coﬀee creamer, and your manager
asked you to estimate the maximum penetration that you could expect from this product, what
one answer would you give? How would you justify the answer

2. Ace Snackfoods, the maker of Krunchy Bits, conducted a trial launch in Tulsa. They monitored
purchases of 1,300 panelists for 52 total weeks. The fle KB_Tulsa.txt contains the ID number of each
panelist, the Market (Tulsa for everyone), and the week of the purchase.

(a) Divide the sample into a 20-week “calibration” set, and a 32-week “holdout” set. Estimate and
describe the distribution of purchase rates using only the calibration data.

(b) Using the parameter estimates from the calibration set, compare the predicted counts for both
the calibration and holdout periods. That is, using the parameters estimated from the frst 20
weeks of data, predict for those same 20 weeks, and forecast for the next 32 weeks. Compare the
predictions/forecasts with the observed data, and assess the model performance. Explain why the
models perform as well as, or as poorly as, they do.

(c) Using the same model that you used in part 2a, estimate and describe the distribution of purchase
rates using only the data in the holdout sample. Compare and contrast the estimated distribution
with the one from part 2a.

(d) Given your answers to the preceding parts, give an overall, intuitive explanation of diﬀerences
between the calibration and holdout periods. How might you refne your model to account for
the diﬀerences?

3. I estimated the exponential-gamma model using all 52 weeks of the Krunchy Bits data, and got estimates of r = 0.045 and alpha = 6.764.

(a) Using these parameter estimates, what is the probability that a randomly chosen person makes
his or her initial purchase within the frst year (by the end of week 52)?

(b) What is the probability that someone who has not yet purchased Krunchy Bits by the end of
the frst year would make his initial purchase by the end of year 2 (week 104)? 

(c) Are your answers to parts 3a and 3b the same, or diﬀerent? Give an intuitive explanation of why
