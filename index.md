---
title: "Adaptive trials"
author: "Chris Oldmeadow"
institute: "HMRI, Data Sciences"
date: "01/04/2021"
---

## What are the problems with a standard RCT?
- Design -> wait -> analyse -> learn from mistakes -> repeat
- **Uncertainty** in many design parameters
- *Ignore* what occurs during trial
- **Inefficient**

## {data-background-image="tenor.gif"}

 <h2 style="color:white"> Driving with your eyes closed </h2>

## A different paradigm

![](adaptive_vs_traditional.webp)
<small>Pallmann, P., Bedding, A.W., Choodari-Oskooei, B. et al. Adaptive designs in clinical trials: why use them, and how to run and report them. BMC Med 16, 29 (2018)</small>


<link href="https://use.fontawesome.com/releases/v5.6.1/css/all.css"
rel="stylesheet"  type='text/css' >


## What is an adaptive trial?

> A clinical trial design that
> allows for **prospectively planned** modifications to one or more aspects of the design based on
> accumulating data from subjects in the trial.

<small> 
 Adaptive Design Clinical Trials for Drugs and Biologics Guidance for Industry, Nov 2019.
</small>

## What can we adapt? 

- Sample size
- Patient population (Adaptive enrichment)
- Allocation ratios
- Treatment arm selection
- Outcome and time-points

## {data-background-image="Google_Traffic.png"  data-background-opacity=0.2}

 Using a GPS to find the best course

## When is it appropriate?

- Outcomes are available **shortly** after randomisation
- Recruitment is *slow*

## What about type 1 errors?

## Traditional Frequentist framework

*p-value* = probability (under identical replicated experiments)
  of getting a result more extreme **if the null hypothesis were true**

### 

*$\alpha$* = Type 1 error rate

  + Probability of **asserting an effect** if the effect is *truly zero*
  + increases with more "looks at the data", outcomes, groups
  
## Bayesian framework

 P = Posterior **probability of effect** 

<img src="bayes.png" width="200">

###
- not conditional on a *null hypothesis*
- **not biased** by the number of times it is calculated 

## Example: "pick the winner"

- **Goal:** to select an appropriate treatment dose and confirm the safety and effectiveness
- Do this *efficiently*
- randomise subjects to one of N dose arms
- carry the *"best dose"* forward to next phase

## Response adaptive randomisation

- Continually evaluate the data (Bayesian framework)
- Probability each treatment is best
- **Adapt allocation ratio** depending on P_best
- Information goes where needed
- Decision rules
- *Drop arms* -> accelerates the process

## Sub-group enrichment

* some sub-groups might perform better for different
  interventions
*  A platform trial adapts both the number of interventions (the ratios), and
  the sub-groups

## Advantages of Adaptive Trials

### Statistical efficiency

### More participants get better interventions

### Drop interventions that don’t improve outcomes

### Add new interventions when available

### Increase/stop recruitment in subgroups



## Disadvantages

- *pre planning* adaptive design modifications -> much more **front-loading** of effort
- longer lead times between planning and starting the trial.


## Adaptive trials vs adaptive interventions

- eg SMART trials
- individual tailored interventions
- decisions based at the individuals(or cluster)  performance
- ignore the collective information (different aims)




## Opportunities in implementation trials


### Outcomes can be fast


### Uncertainty in treatments

### Prior data often available


### Multi-stage processes that can be combined into a single on-going study


### Embedding trials into routine care

## Questions/Opportunities/Discusison



