# Recent developments in methods for causal inference with panel data
Materials for a short workshop on the latest developments of causal inference with cross-sectional time-series data.

## Introduction
This workshop intended to update advanced political science researchers on the latest developments of statistical methods for causal inference with observational cross-sectional time-series (CSTS) data. This is definitely a mouthful, and so are many other concepts covered throughout the workshop. 

The way I think of this workshop is to have a unified look at recent methods that allow to compute counterfactual outcomes and average treatement effects on treated units using CSTS data. I try to cover the assumptions behind each method, the differences with the "classic" difference-in-difference approach, and some practical implications when programming in R. You will see that the literature covered in this workshop tends to bridge the ground between standard causal inference methods such as difference-in-differences, matching, and synthetic control.

The workshop is not meant to be a complete course on causal inference, so it makes some assumptions on the participant's prior knowledge. First, it requires confidence with basic linear regression stats and an introduction to causal inference based on the so-called *Neymar-Rubin counterfactual outcomes framework*. For a refresher on the latter, see [this post](https://www.causalconversations.com/post/po-introduction/). 

Second, it requires participants to have read **at least** my [notes on the literature](notes/panel_models_notes.pdf), which are meant to guide you through the sometimes bewildering array of alternative methods. 
However, for a better and slightly more technical understanding of recent literature, I **highly** recommend reading the great review paper by [Roth et al.](literature/recommended_readings/roth_et_al_2022.pdf) in the "recommended readings" folder.

## Workshop structure

The workshop's content is centered around a select number of papers that highlight deficiencies of difference-in-differences models in certain settings and suggest extensions to the standard model. After a brief overview of the literature and a dust-off of our knowledge of the basic DiD model, we go through the main violations of basic DiD assumptions, and the alternative methods designed to deal with them.

In the second part, participants are welcome to bring their own CSTS data applications. Together we might brainstorm and discuss which methods are more appropriate for the data, what assuptions might be necessary to make them work, and what R package exist to implement them.

The workshop's contents are the following:

- Overview of DiD literature
- Quick dust-off of basic DiD model
- The DiD assumptions violation tree
- Discussion of selected methods (with R examples):
  - Linear DiDs with staggered treatment adoption
  - Flexible methods for repeated/revesable treatment exposure
- Bring your own problems: Brainstorming data and methods
- Conclusion: Is there a new standard?
