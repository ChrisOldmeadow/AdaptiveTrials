---
title: "Adaptive trials"
author: "Chris Oldmeadow"
institute: "HMRI, Data Sciences"
date: "27/03/2021"
---

## A different paradigm

![](adaptive_vs_traditional.webp)
<small>Pallmann, P., Bedding, A.W., Choodari-Oskooei, B. et al. Adaptive designs in clinical trials: why use them, and how to run and report them. BMC Med 16, 29 (2018)</small>


<link href="https://use.fontawesome.com/releases/v5.6.1/css/all.css"
rel="stylesheet"  type='text/css' >





## What are the problems with a standard RCT?

- Ignore what occurs before and during trial
- **Inefficient**


## {data-background-image="tenor.gif"}

 <h2 style="color:white"> Driving with your eyes closed </h2>

## {data-background-image="Google_Traffic.png"}

 <h2 style="color:black"> Using a GPS to avoid problems that pop-up</h2>

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
- Treatment arm selection
- Allocation ratios
- Outcome and timepoints

## Advantages of Adaptive Trials

### Statistical efficiency

### More participants get better interventions

### Drop interventions that don’t improve outcomes

### Add new interventions when available

### Increase/stop recruitment in subgroups



## Traditional Frequentist framework

- P-value = probability (under identical replicated experiments) of getting a result more extreme if the null hypothesis were true
-  $\alpha$ = Type 1 error rate
- 
  - Probability of *asserting an effect* if the effect is truly zero
  - $\alpha$ increases with more "looks at the data"
  
## Bayesian framework

- P = Posterior probability of effect (given the data and prior beliefs)
- estimating probability that a treatment is the best
- not conditional on a null hypothesis
- not effected by the number of times it is calculated - it only gets
  more accurate
- 1-P = false positive probability

## Example: "pick the winner"

- Goal: to select an appropriate dose and confirm the safety and effectiveness
- Do this efficiently
- randomise subjects to one of N dose arms (+/- control)
- carry the "best dose" forward to next phase

## Response adaptive randomisation

- Continually evaluate the data (Bayesian framework)
- Adapt allocation ratio depending on "Probability each treatment is the best"
- Information goes where needed
- Drop arms -> accelerates the process



## Sub-group enrichment

* some sub-groups of participants might perform better for different
  interventions
*  A platform trial adapts both the number of interventions (the ratios), and
  the sub-groups



## Disadvantages

- pre planning adaptive design modifications can require more effort at the design stage,
leading to longer lead times between planning and starting the trial.


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



## Example: optimising implementation bundles

* A number of components in an implementation bundle
* Traditional approach -  not feasible to perform a large multi factorial trial
*



