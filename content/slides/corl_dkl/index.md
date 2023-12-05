---
title: Scalable Deep Kernel Gaussian Process for Vehicle Dynamics in Autonomous Racing​
summary: An introduction to Deep Kernel Learning in Gaussian Process model for learning vehicle dynamics of a full-size racecar.
authors: [Jingyun Ning and Madhur Behl]
tags: []
categories: []
date: "2023-11-05"
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: league
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: dracula
---

## Scalable Deep Kernel Gaussian Process for Vehicle Dynamics in Autonomous Racing

[Paper](https://openreview.net/pdf?id=zUiH8UUYDo) | [Conference](https://www.corl2023.org/)

---

### Vehicle Dynamics Modeling Is Challenging​

- Building dynamic vehicle models capable of modeling non-linear behaviors
- Obtaining physics-based model coefficients is often time and cost prohibitive.​
    - Learning drivetrain dynamics requires dyno testing
    - Understanding tire dynamics involves experimenting with specialized tire rigs.  
[Slide image](slides1.png)
---

### Approximate Dynamics Using Simpler Model

[single-track models](table.png)
- Approximate the observed dynamics with a simpler model (single-track model)
- Build a GP model to capture the residuals between the simpler model output and observations.  
    {{% fragment %}} **Ekin Model $+$ GP** {{% /fragment %}}
    {{% fragment %}} **$\approx$** {{% /fragment %}}
    {{% fragment %}} **Observed Dynamics** {{% /fragment %}}  
[Slide image](slides2.png)
---

### DKL-SKIP GP Method

- DKL captures the most relevant information while reducing its dimensionality.

$$
k(d_i, d_j;\theta) \rightarrow k(g(d_i,w),g(d_j,w)|\theta,w)
$$

- SKIP-GP utilizes SKI & product kernel structure to reduce the computing complexity of GP  
[Slide image](slide4.png)  
---

### Experiment Setup

- Conduct experiments using data collected from a real-world autonomous Indy car @ LVMS.
- Collect data from Autoverse, a high-fidelity racing simulator @ TMS.
- Compare the open loop one-step prediction performance of DKL-SKIP with the SKIP-GP and N4SID method.​  
[Slide image](slide5.png)

---

