###  Customer_lifetime_valuation using probabilistic models

#### 1. Answer the following questions about the population of GetFit customers 
1. Assume that a GetFit membership is $70 per month, and that the monthly discount rate is 1.5% (annual rate
of 18%).
(a) What is the most that GetFit should spend to acquire a new customer?
(b) What is the most that GetFit should spend to retain an existing customer who was acquired 1
month ago (about to make her frst renewal decision)?
(c) What is the most that GetFit should spend to retain an existing customer who was acquired 10
months ago?
(d) Explain why ignoring heterogeneity in churn probabilities will lead to an undervaluation of the
customer base. How does the amount of heterogeneity in the population aﬀect that undervaluation?


2. Ben’s Knick Knacks is a manufacturer of commemorative collectibles, such as sports memorabilia, coin
collections, or porcelain fgurines. Much of Ben’s marketing budget is spent on targeted direct mail.
A customer would receive a letter or postcard that contains a special oﬀer for a particular item. To
redeem the oﬀer, the customer either calls a special phone number, or enters a promotional code in
an online order form. This process lets Ben track who receives the targeted oﬀer, and which of those
customers converted to a sale.
Ben’s database contains mailing addresses for 1,552,037 households. Each household belongs to one
of 126 segments. How the segments are constructed is unimportant for this exercise, but in general,
segments would be defned by demographic and psychographic variables (e.g., age, income, education
level, estimated cultural and politcal characteristics), and possibly some past purchase data. The only
descriptive information we have about a segment is the identifcation number, so we can act as if there
are no salient similarities or overlapping characteristics across segments. Some segments contain more
households than others.
A typical direct mail campaign costs $3,343 for every 10,000 mailings. Ben has a limited marketing
budget, and he does not want to “burn out” households with oﬀers that are unlikely to be successful
(thus saving those households for future campaigns). Within a single direct mail campaign, Ben will
target only those segments that he expects to be proftable. His problem is that he does not know
what the expected response rate (long-run sales per mailing) will be for each segment. He addresses
this issue by conducting a test campaign on a small fraction of the database. To run the test, Ben
samples households randomly from the segments, and sends those households a sales ﬂyer. He then
tracks how many of households purchased the item in response to the oﬀer, and uses the results to
decide which segments to target in the full campaign. When rolling out the campaign, the decision to
target a segment is a binary one: the answer is either Yes or No.
Ben’s most recent creation is a baseball-themed commemorative plate. Each plate costs $138.50 to
produce, and the selling price is $300. Sales are limited to one plate per household. The results of a
test campaign (to 3.24% of the database) are in the fle bens_data.txt. For each segment, we have
the number of households who received a test mailing, and the number of households who purchased
the item. Each observation is a segment, not a customer.
(a) What is the aggregate observed response rate (total sales / total mailings) in the dataset?
(b) What is the average segment-level observed response rate ?
(c) Suppose heterogeneity in segments’ response rates(p)is described by a beta(a,b) distribution.
What are the maximum likelihood estimates of a and b?
(d) Under the assumptions of the model in Part 2c, what is the expected response rate for a randomly
chosen segment?
(e) What is the probability that a randomly chosen segment will have a response rate that is less
than your answer in part 2d?
(f) Plot the probability that at least one customer in a randomly chosen segment will purchase the
product after Ben sends m mailings to that segment. On this plot, m will be on the x-axis
(vary m from 1 to 2,000), and the probability will be on the y-axis. Be sure your axis labels are
informative.
Then, give an intuitive explanation for the slope and shape of the curve. What is the maximum
value of this probability if m were to continue to increase (i.e., if m → ∞)?
(g) Ben wants some more information about the potential success of his direct mail campaign, but in
table form. For a small set of possible mail quantities, he wants to know not only the probability
that at least one member of the segment will buy, but also the probability of making two or more
sales, and the expected number of sales.
