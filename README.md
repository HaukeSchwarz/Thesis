# Master Thesis "Assessing the Fairness of Mortgage Lending Decisions: Leveraging Explainability to Quantify the Trade-Off between Fairness and Performance in Algorithmic Decision-Making"
## Hauke Schwarz
## Católica Lisbon School of Business & Economics
## Summer 2024

This repository contains all code that my Master's Thesis *"Assessing the Fairness of Mortgage Lending Decisions: Leveraging Explainability to Quantify the Trade-Off between Fairness and Performance in Algorithmic Decision-Making"* is based upon.

### Abstract

The increase in the application of algorithmic decision-making has given rise to concerns about the fairness of machine-made decisions. Specifically in areas that heavily impact individuals like healthcare, recidivism, or finance, a thorough understanding of how decisions have been made is crucial from a regulatory and moral standpoint.


However, improving algorithms in terms of their predictive performance often comes at the cost of increased complexity and thereby reduced understandability. This is especially true for algorithms without a direct interpretation method like neural networks, so-called “black box” models.


This thesis aimed to examine whether 2022 Home Mortgage Disclosure Act mortgage lending data can be used to train a neural network to predict whether a mortgage will be granted based on demographic data, specifically focusing on geography and sensitive attributes such as applicant race. Both fairness and explainability requirements were incorporated into the process, all with the aim of keeping the model’s predictive performance high.


Iteratively adapting the initial neural network with different fairness-focused algorithms as well as trying to uncover its inner workings using explainability algorithms showed mixed results. While some results were promising with regards to the scope of this thesis, none of the iterations applied managed to significantly improve fairness and/or predictive performance of the proposed model. This is most likely the effect of underlying discriminatory factors underlying in the data, that cannot directly be mitigated by controlling for the race of mortgage applicants, leaving an important focus for future research.