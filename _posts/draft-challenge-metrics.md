Review of: Thomas & Uminsky (2020) Reliance on Metrics is a Fundamental Challenge for AI
====

This paper apparently began its life as a [blog post](https://www.fast.ai/2019/09/24/metrics)
and then was prepared to be part of 
[Ethics of Data Science Conference](https://hmi.anu.edu.au/events-2/ethics-of-data-science-conference), 
which was canceled due to the pandemic. 
Which is a pity, because I think this paper warrants more attention and careful thought.

Summary
----

1. Introduction
    * Metrics are essential in AI, but also problematic
1. Goodhart's Law and machine learning
    * Goodhart's Law: a metric that becomes a target ceases to be a good metric
    * Mathematical metrics are distinct from KPIs and behavioral metrics, but related concepts
    * ML loss optimization is using a metric as a target
1. Previous related work
    * Manheim and Garrabrant (2019) breakdown subtypes of Goodhart's Law based on the causal and statistical relationships between the metric and the goal
    * In ML, especially in RL, the algorithm often finds the extreme case breakdown of the reward metric (Krakovna 2019)
    * Taylor (2016) and Slee (2019) recommend not optimizing single metrics
1. We can't measure the things that matter most
    * Quantifiable metrics are operational proxies for real world goals
    * Real goals in a complex world are not directly measurable
1. Metrics can, and will, be gamed
    * If people have incentives to fudge numbers, they will be fudged at the expense of untracked costs
    * Examples: EHS, school testing, recommendation systems, automated essay grading
1. Metrics overemphasize short-term concerns
    * Short-term measurable improvements do not add up to long-term improvement
    * Examples: Recommendation systems, Wells Fargo business strategy
1. Many metrics gather data of what we do in highly addictive environments
    * Tech ecosystems built around engagement metrics produce circular feedback
1. A framework for healthier use of metrics
    1. Use a slate of metrics to get a fuller picture and reduce gaming
    1. Combine with qualitative accounts
    1. Involve a range of stakeholders, including those who will be most impacted


Rachel Thomas and David Uminsky (2020) Reliance on Metrics is a Fundamental Challenge for AI. 
*Ethics of Data Science Conference*. https://arxiv.org/abs/2002.08512
