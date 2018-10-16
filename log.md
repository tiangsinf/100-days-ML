# 100 days of ML Challenge!

### Day-5: Oct-15, 18
**What I've learned:**
Learned the `family` argument is `glm()`. It consist of `"gaussian"` for linear regression, `"binomial"` for logistic and `"poison"` for poisson distribution.
Learned the `type` in the `predict()` arguments.

**What I think:**
Skipped day 4 because of family trip to Genting.. 

**What I have done:**
Link to D-5 (failed) work:
https://github.com/tiangsinf/100-days-ML/blob/master/Day-5_15.10.18.md

**What I want to do for tomorrow**
Another try for logistic regression
__________________________________________________________________

### Day-3: Oct-13, 18
**What I've learned:**
Multiple linear regression

**What I think:**
big blunder on analyzing graph :(. I was wondering why the value of intercept from `lm` function return 1 value but the graph shows other value. Reason being the starting point of x-axis wasn't 0. I spent almost a day just to figure this out. Moral of the story, always be mindful of the starting point of x & y axis.


**What I have done:**
Link to D-3 work: 
https://github.com/tiangsinf/100-days-ML/blob/master/Day-3_13.10.18.md


**What I want to do for tomorrow**
learn about `glm`, ` rlm` and `loess`.
Logistic regression
__________________________________________________________________

### Day-2: Oct-12, 18
**What I've learned:**
indepth R markdown.
ggvis - attempted on linear model
simple linear model (SST = SSR(explained) + SSE(unexplained))

**What I think:**
Gained new insight into linear regression. 
Apparently `ggvis` cannot be shown properly in .md format and knitted size for html output is big. Not really neccessary if you are not doing interactive visualisation. That bing said, I will still do a few more days of visualisation using `ggvis` just to get familiar with it.

**What I have done:**
Link to D-2 work: 
https://github.com/tiangsinf/100-days-ML/blob/master/Day-2_12.10.18.md


**What I want to do for tomorrow**
figure out how to extend linear line to intercept with y axis.
apart from `lm`, also learn about `glm`, ` rlm` and `loess`.
__________________________________________________________________

### Day-1: Oct-11, 18
**What I've learned:**
1.  Calculus for PDF (https://www.youtube.com/watch?v=QKA4HNEw3aY)
2.  Plot auc
3.  Spearman's rho & Kendall's tau <- test correlation between 2 non lineary correlated variables
4.  Illustration relationship between
    
    * Categorical / continuous - by functions (`~`) & boxplot
    * Categorical / categorical - proportions table & masaic plot
    * Continuous / continuous - converance, correlation
5.  Refresher of basic probability
6.  Bayer's Theorem / Bayes Inference
$$P(E)*P(H|E) = P(H)*P(E|H)$$
7.  NHST

**What I think:**
Everyone is talking about Bayesian stats and I finally know how it works, eventhough the working of Bayesian stats is a bit counter intuitive to me.

**What I have done:**
Link to D-1 work:
https://github.com/tiangsinf/100-days-ML/blob/master/Day-1_11.10.18.md

**What I want to do for tomorrow**
1.  Learn Bayes (the maths way!)
2.  GADP top-tier prediction with nn
__________________________________________________________________

### Day-0: Oct-10, 18
**What I've learned:**
1.  PMF (for descrete variables), PDF (for continuous variables)
2.  Refresher on basic statistics (spread, population vs sample central tendency)

**What I think:**
I like how i started to understand degree on freedom, *N-1* came about! I have always wanted to know when sample sd needs to be divided by *N-1* instead of *N*.

**What I have done:**
Link to D-0 work:
https://github.com/tiangsinf/100-days-ML/blob/master/Day-0_10.10.18.md

**What I want to do for tomorrow**
1.  understand the calculus to compute area under pdf curve
2.  find a dataset and create a pdf curve.