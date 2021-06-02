# Root Insurance Data Science Challenge

Optimizing ad spending in a hypothetical vertical search website. A project for the 2021 Erdős Institute Data Science Boot Camp.

TargetedMinimumBids.ipynb walks through my initial exploratory analysis, identifying several key features of the data set that I then use to build a simple but robust and effective bid strategy. This strategy is based on targeting customers that are unlikely to purchase policies and submitting a minimum bid (presumably $0.01) for them.

OptimizedVariableBids.ipynb walks through  a model built around the assumption that increasing a bid price by $2.50 will shift an ad's display rank by one slot. I identify a sequence of random walks that allow an efficient optimization of bid strategies within the framework of the model, and various optimized strategies are then identified and offered as a strategy consideration for management.

RootInsuranceChallengePresentation.pdf is a presentation that highlights the results of my exploratory analysis and briefly walks through the two modeling approaches, including a component of practical recommendations.

RootInsuranceChallengeExecutiveSummary.pdf offers a similar overview in a one-page text format. it also includes printouts of the two specific bid strategies identified for the two models when targeting a 400 policy sales goal.
