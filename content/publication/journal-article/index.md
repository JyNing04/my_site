---
abstract: In high-speed autonomous racing, it is necessary to have an accurate racecar vehicle dynamics model in order to push the vehicle closer to its limits. The choice of the dynamics model has to be made by balancing the computational demands in contrast to model complexity. Learning-based methods, such as Gaussian processes (GP)-based regression, have shown promise toward approximating the vehicle dynamics model. In particular, such methods use a simplified model structure that is easy to tune and then use GP to model the mismatch between the output of the simple model and observed system dynamics. However, current GP approaches often oversimplify the modeling process or apply strong assumptions, leading to unrealistic results that cannot translate to real-world settings. This article presents a comprehensive GP-based design for modeling the dynamics of an autonomous racing car. We do so with high-fidelity simulation data, a 1/10-scale autonomous racing car platform, and a full-scale autonomous Indy racing car. In the first part of this article, we present a rigorous empirical analysis highlighting how the open-loop and closed-loop performance of GP models for autonomous racing is highly sensitive to the choice of the GP kernel, the data sample size, and track configurations suggesting there is no single easy choice that always works. We demonstrate this through a combinatorial simulation setup for 1/10-scale autonomous racing cars. We then present a novel method called DKL-SKIP, which uses deep kernel learning to overcome the challenges of kernel selection and scalability for GP modeling. We evaluate DKL-SKIP on a high-fidelity AutoVerse simulator as well as real data from an autonomous real-world full-scale Indy racing car. Our results reveal that DKL-SKIP surpasses scalable GP models and the N4SID algorithm in both real-world and high-fidelity simulation environments.
# author_notes:
# - Equal contribution
# - Equal contribution
authors:
- admin
- Madhur Behl
date: "2024-06-11T00:00:00Z"
doi: "https://doi.org/10.4271/10-08-03-0019"
featured: false
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false
projects: []
publication: '*Gaussian Processes for Vehicle Dynamics Learning in Autonomous Racing, 1*(1)'
publication_short: ""
publication_types:
- "2"
publishDate: "2024-06-11T00:00:00Z"
# slides: example
summary: This journal article provides a comprehensive overview and synthesis of prior research efforts focused on the development and refinement of Gaussian Process (GP) models for the purpose of learning and understanding vehicle dynamics. 
tags:
- Source Themes
title: Gaussian Processes for Vehicle Dynamics Learning in Autonomous Racing
# url_code: ""
# url_dataset: ""
url_pdf: https://saemobilus.sae.org/articles/gaussian-processes-vehicle-dynamics-learning-autonomous-racing-10-08-03-0019
# url_poster: ""
# url_project: ""
# url_slides: example
# url_source: ""
# url_video: ""
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->
