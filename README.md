# panel_models_workshop
Short workshop on the latest developments of causal inference with panel data

## Introduction
This repo contains materials for a short workshop intended to update advanced researchers on the latest developments of statistical methods for causal inference with observational cross-sectional time-series (CSTS) data. This is definitely a mouthful, and so are many other concepts explained throughout the workshop. 

The way I think of this workshop is to have a unified look at recent methods that allow to compute counterfactual outcomes of CSTS, the assumptions behind each method, and some practical implications when programming in R. You will see that the literature covered in this workshop tends to bridge the ground between the classic difference-in-differences and the synthetic control designs.

The workshop is not meant to be a complete course on causal inference, so it makes some assumptions on the participant's prior knowledge. First, it requires confidence with basic linear regression stats and an introduction to causal inference based on the so-called *Neymar-Rubin counterfactual outcomes framework*. For a refresher on the latter, see [this post](https://www.causalconversations.com/post/po-introduction/). Second, it requires participants to have read at least one paper.

## Structure
The workshop is centered around a select number of papers that highlight deficiencies of difference-in-differences models in certain settings and suggest extensions to the standard model. In addition to the readings, I wrote some notes to guide you through the sometimes bewildering array of alternatives, their unique advantages and data requirements/assumptions.
