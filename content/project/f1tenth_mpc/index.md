---
title: Approximating Race Car Vehicle Dynamics With Gaussian Processes For Autonomous Racing
summary: We evaluate the closed-loop performance of the GP model using model predictive control on racecar dynamics learning.
tags:
- Vehicle dynamics
- Simulator
- Self-driving

date: "2022-09-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  # caption: Photo by rawpixel on Unsplash
  focal_point: Smart
  # filename: DSC05889.JPG

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
# url_code: ""
# url_pdf: ""
# url_slides: ""
url_video: https://youtu.be/bfdYB09AGcg

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

In high-speed autonomous racing, it is necessary to have an accurate racecar vehicle dynamics model. The choice of the model has to be made by balancing the computational demands in contrast to model complexity. Recent studies have explored learning-based methods, such as Gaussian Process (GP) regression, for approximating the vehicle dynamics model. However, these efforts do not delve into rigorous process of how to construct the best GP model, and use simple track layouts. This paper presents the most detailed analysis of the use of GP models for approximating vehicle dynamics for autonomous racing.  In particular we construct an extended kinematic model for the F1Tenth autonomous racing platform.  We investigate the effect of kernel choices, sample sizes, racetrack layout, racing lines, and velocity profiles on the efficacy of the learned dynamics. We conduct over 400 simulations on real F1 track layouts to provide, concrete recommendations to the research community for training accurate GP regression for single-track vehicle dynamics.  In addition, we evaluate the closed-loop performance of the GP model to show that it is able to achieve a lap performance within $94\%$ of the full dynamical model. 

- We present a comprehensive analysis of the effects of training sample size, kernel choice, velocity profiles, racing lines, and track geometry on the accuracy of the extended kinematic GP model. 
- We compare the racing performance of the best GP model against the knowledge of true dynamics using model predictive control.
- We use Formula One racetracks layputs from Shanghai International Circuit, Sepang International Circuit, and Yas Marina Circuit, to conduct this analysis in the F1tenth Gym environment. 