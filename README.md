# Analyze A/B Test Results

## Introduction:
A/B tests are used to test changes on a web page. In this test, we divid two groups, a control group uses the old version, and the experiment group use the new version. 
Then we measure the level of engagement for each group. Based on these results we can judge whether one version is better than the other.

## A/B testing 
This test also use two hypotheses:

     Null Hypothesis: The new version is no better or  worse than the old version
     Alternative Hypothesis : The new version is better than the old version

If we fail to reject the null hypothesis, the results would suggest keeping the old version. If we reject the null hypothesis, the results would suggest launching the change.

#### A/B testing also has its drawbacks. 
 - It can ignore the other options because the test compares only two options. 
 - A bias results can be produced Due to:
 
   - Change aversion when existing users give an unfair advantage to the old version because they are unsatisfied,
   even if it is better.
  
   - Novelty Effect: Existing users may give an unfair advantage to the new version because they’re excited or drawn to the change,
   even if it isn’t any better in the long run.
          
### Metric
To complete a A/B testing we comute these measurements:

- The observed difference between the metric, click through rate, for the control and experiment group.
    
- Simulated the sampling distribution for the difference in click through rates.
    
- Using this sampling distribution to simulate the distribution under the null hypothesis, 
    by creating a random normal distribution centered at 0 with the same spread and size.
    
- Computed the p-value by finding the proportion of values in the null distribution that were greater than our observed difference.
    
- Interpret the p-value to determine the statistical significance of our observed difference.

## Tools 

`pandas`

`numpy`

`matplotlib`

`Pingouin`




#### Project LICENSE

    This is a udacity data analyst nanodegree project.



