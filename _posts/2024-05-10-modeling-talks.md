---
title: "Alphabet's Modeling Talks"
tags:
  - AI
---

one of the hidden treasures of the Youtube is Alphabet's Modeling Talks that are organized by [Greg Bronevetsky](https://www.linkedin.com/in/gregbronevetsky/). These talks feature researchers applying modeling to all sorts of problems such as economy, public infrastructure, climate change, diseases, chemistry and physics. The breadth of these talks is truly fascinating. They gave me a rare glimpse into what is happening in these research areas. I recommend those talks to anyone looking for research ideas or open science problems to apply AI/ML to.

I encourage you to check the Model talks [homepage](https://sites.google.com/modelingtalks.org/entry/home) and Greg's [youtube channel](https://www.youtube.com/@gregbronevetsky)

Here are some of the talks that were interesting to me:

- [Artificial intelligence for synthetic organic and analytical chemistry](https://sites.google.com/modelingtalks.org/entry/artificial-intelligence-for-synthetic-organic-and-analytical-chemistry) by Prof. Connor W. Coley. What I found interesting is the problem of "one-step retrosynthetic analysis" in which the input is a target molecule structure and an AI (graph neural network) is trained to predict the transformation needed to produce that target molecule. Those trained models are then used in a regressive multi step way so that they can predict all the transformations needed get to the target molecule from currently available molecules. Another interesting point made was about that RL algorithms can help in navigating this search tree of transformation but are limited by the fact that the set of known chemical transformation is imperfect and not definitive.

- [Infrastructure systems, data-driven design and visualization](https://sites.google.com/modelingtalks.org/entry/infrastructure-systems-data-driven-design-and-visualization) by Jennifer Whyte. It was an interesting talk for me because it was the first time I get introduced to how data driven approaches are utilized in public infrastructure construction projects.

- [Modeling climate risks to infrastructure and supply chains](https://sites.google.com/modelingtalks.org/entry/modelling-climate-risks-to-infrastructure-and-supply-chains) by Prof. Jim Hall. I found intriguing the part about the methodology used to create models of the different power networks and subsequent modeling of how weather events can affect those networks. Also interesting was the second part about modeling the global shipping / ports activities and how green fuel production will cause major shifts into those.

- [GraphCast: Learning skillful medium-range global weather forecasting](https://sites.google.com/modelingtalks.org/entry/graphcast-learning-skillful-medium-range-global-weather-forecasting) by Ferran Alet. That was a presentation about GraphCast which is a model for weather forcasting from Deepmind. The interesting part for me was about how they encoded the weather data for the graph neural network. Additionally, the fact that the natural way of selecting the time windows for the input data to the model was unfairly leaking information from the future and that Deepmind might probably be the first to discover this issue given that the data used for training / evaluation was not initially designed for machine learning.


- [Cloud Resolving Modeling on Exascale Computers](https://sites.google.com/modelingtalks.org/entry/cloud-resolving-modeling-on-exascale-computers) by Mark Taylor. That presentation was about the effort in the US Department of Energy to port some components of their Energy Exascale Earth System Model from Fortan to C++. They did so in order to make use of upcoming GPU based Exascale HPC systems. The speaker made an interesting point that the power consumption of GPU nodes is almost 4x CPU nodes which makes the comparison between them tricky. It also seems to me that the code for the world's largest earth models is still written in fortan. Porting it to c++ is a few years worth of effort by a small team of engineers.


