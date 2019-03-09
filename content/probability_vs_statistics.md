Title: Probability vs. Statistics - What is the difference?
Date: 2018-12-09 10:20
Category: concepts
Status: draft

#### TL;DR
__Probability__ deals with predicting the likelihood of future events, while __statistics__ involves the analysis of the frequency of past events.

In a typical probability problem, one starts by assuming that a certain random variable has some given probability distribution, say the number of people entering a supermarket follows a Poisson distribution, and then goes on to compute probabilities such as the chance that more than 100 people (max capacity) require service at the same time.

In a typical statistical problem, one observes the distribution, that is to say, the number of people entering the supermarket over a period of time, and then finds a model to best represent the observed pattern.

So, basically, with statistics we are trying to determine the probability model that will allow us to assign probability values to future events


In order to start our discussion about the differences between probability and statistics, I think it is important to have a very clear understand of what these tools are on their own.



### Notes:
#### https://www.thoughtco.com/probability-vs-statistics-3126368
1. The main difference between probability and statistics has to do with knowledge. By this, we refer to what are the known facts when we approach a problem
2. A problem in probability would start with us knowing everything about the composition of a population
3. If instead, we have no knowledge about the types of socks in the drawer, then we enter into the realm of statistics. Statistics helps us to infer properties about the population on the basis of a random sample
4. Of course, probability and statistics do have much in common. This is because statistics is built upon the foundation of probability. Although we typically do not have complete information about a population, we can use theorems and results from probability to arrive at statistical results. These results inform us about the population.
5. Underlying all of this is the assumption that we are dealing with random processes. This is why we stressed that the sampling procedure we used with the sock drawer was random. If we do not have a random sample, then we are no longer building upon assumptions that are present in probability.

#### http://www.statisticalengineering.com/probability_and_statistics.htm
1. Engineers know that stress and strain are not synonymous: they don't mean the same thing, even though the popular press uses the terms interchangeably.
2. Probability can be viewed either as the long-run frequency of occurrence or as a measure of the plausibility of an event given incomplete knowledge
3. Statistics are functions of the observations (data) that often have useful and even surprising properties. 
4. The sample mean,, is a statistic; the population mean,  ,is not.  That is because a statistic is observable, being computed from the observations, while a population parameter, being a philosophical abstraction, is not observable, and thus must be estimated.  Statistics, like  , are often used to population parameters like  .  The fidelity of the estimate depends on the number of observations used in computing the statistic.  Notice that the estimate changes slightly every time you take a sample, whereas the population parameter doesn't.
5. The population parameters are required to estimate probabilities, based on a probability density function, pdf (or probability mass function, pmf, if X is a discrete random variable).
6. So (finally) we see the relationship between probability and statistics: From the observations we compute statistics that we use to estimate population parameters, which index the probability density, from which we can compute the probability of a future observation from that density.
7. Notice that estimating the population parameters is only half the battle.  The density from which the observations were taken must also be known


#### https://www3.cs.stonybrook.edu/~skiena/jaialai/excerpts/node12.html
1. Probability deals with predicting the likelihood of future events, while statistics involves the analysis of the frequency of past events.   
2. Probability is primarily a theoretical branch of mathematics, which studies the consequences of mathematical definitions. Statistics is primarily an applied branch of mathematics, which tries to make sense of observations in the real world.
3. If this mathematician were a probabilist, she would see the dice and think: Six-sided dice? Presumably each face of the dice is equally likely to land face up. Now assuming that each face comes up with probability 1/6, I can figure out what my chances of crapping out are.
4. If instead a statistician wandered by, she would see the dice and think: Those dice may look OK, but how do I know that they are not loaded? I'll watch a while, and keep track of how often each number comes up. Then I can decide if my observations are consistent with the assumption of equal-probability faces. Once I'm confident enough that the dice are fair, I'll call a probabilist to tell me how to play.

#### https://www.quora.com/What-is-the-relationship-between-statistics-and-probability
1. Statistics are used to quantify observations of phenomena whose behaviour is predicted by probability.
2. You cannot actually observe a probability: when you toss a coin, it either falls heads or tails. The underlying probability law is not directly visible. But you can see manifestations of probability, by gathering statistics. How? Well, very often, by repeating the same experience over and over again
3. And that’s pretty much how all of statistics work. You make the assumption that a random experiment follows a certain distribution, of which you don’t know the parameters. You repeat that experience many times, and gather the results. You confront your statistical measurements with what the probability law predicts, and use that to infer the parameters.
4. All that’s left is confidence in your model. Say you toss a coin twice, and get heads twice. Would it be reasonable to infer that this coin will yield heads every time? No. Because your sample size is too small for you to be confident in the inferred model.
5. Again, the law of large numbers (and its corollaries) is the vital tool for statistical analysis, which helps you infer statistical models from repeated experiments, but it implies that you must have a sample set as large as possible to be confident in your model.

#### https://www.linkedin.com/pulse/20140716063624-1901345-the-difference-between-probability-and-statistics/
1. Statistics, on the other hand, is a branch of applied mathematics that addresses inquiries in the reverse direction; namely, it begins with experimental observations and tries to make inferences about the phenomenon that led to the observations in terms of probability models


#### https://www.reddit.com/r/math/comments/1ztwg5/what_is_the_difference_between_statistics/
1. I heard the following, which I rather like. You have a a bag full of marbles with known contents, you close your eyes and pull out a handful of marbles. What's in your hand? That's probability. Now there's another bag with unknown contents, with eyes open you pull out a handful of marbles. What's in the bag? That's statistics.


#### https://junkcharts.typepad.com/numbersruleyourworld/2013/04/statistics-as-inverse-probability.html
1. In a typical probability problem, one starts by positing that a certain quantity has some given probability distribution, say the number of people entering a bank branch follows a Poisson distribution, and then goes on to compute probabilities such as the chance that more than 100 people (max capacity) require service at the same time. In a typical statistical problem, one observes the distribution, that is to say, the number of patrons over a period of time, and then finds a model to best represent the observed pattern.

#### https://tms30x30.wordpress.com/tag/the-difference-between-probability-and-statistics/
1. Like salt and pepper on every dining table, probability and statistics are essential elements to market research. An understanding of what they mean is equally essential.
2. For an easy-to-understand definition of the two, probability is the chance that something will happen, how likely it is that some event will happen. While statistics is the study of data: how to collect it, summarize it and present it.
3. To better understand this difference, we can have a look at the interrelation between the two. Let’s say we have a statistical experiment that studies the effect of EDM (electronic dance music) on average driving speed. After administering the test to a representative sample, tabulating the results and doing all things statistics we now need to do something with those results aside from simply looking at them. That’s where probability comes in. The statistics should be able to predict what the probability is of EDM having an effect on average speeds in the population that we sampled.



$$frac{n!}{k!(n-k)!}$$

$$\int_0^\infty e^{-x^2} dx=\frac{\sqrt{\pi}}{2}$$

$$
{n+1\choose k} = {n\choose k} + {n \choose k-1}
$$

$$x^2$$