---
abstract: Autonomous racing is gaining attention for its potential to advance autonomous vehicle technologies. Accurate race car dynamics modeling is essential for capturing and predicting future states like position, orientation, and velocity. However, accurately modeling complex subsystems such as tires and suspension poses significant challenges. In this paper, we introduce the Deep Kernel-based Multi-task Gaussian Process (DKMGP), which leverages the structure of a variational multi-task and multi-step Gaussian process model enhanced with deep kernel learning for vehicle dynamics modeling. Unlike existing single-step methods, DKMGP performs multi-step corrections with an adaptive correction horizon (ACH) algorithm that dynamically adjusts for varying driving conditions.To validate and evaluate the proposed DKMGP method, we compare the model performance with DKL-SKIP and a well-tuned single-track model, using high-speed dynamics data (exceeding \SI{230}{\kilo\meter\per\hour}) collected from a full-scale Indy race car during the Indy Autonomous Challenge held at the Las Vegas Motor Speedway at CES 2024.The results demonstrate that DKMGP achieves up to 99\% prediction accuracy compared to one-step DKL-SKIP, while improving real-time computational efficiency by 1752x. Our results show that DKMGP is a scalable and efficient solution for vehicle dynamics modeling making it suitable for high-speed autonomous racing control.
# author_notes:
# - Equal contribution
# - Equal contribution
authors:
- admin
- Madhur Behl
date: "2025-06-06T00:00:00Z"
doi: "https://doi.org/10.4271/10-08-03-0019"
featured: false
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false
projects: []
publication: '*7th Annual Learning for Dynamics & Control Conference*'
publication_short: "L4DC"
publication_types:
- "2"
publishDate: "2026-06-06T00:00:00Z"
# slides: example
summary: In this paper, we developed a DKMGP-based E-kin model to capture the dynamics of a full-size autonomous racecar. The DKMGP model overcomes the limitations of existing methods by predicting all state residuals using a single model. Additionally, we present an adaptive correction horizon algorithm that enables DKMGP for multi-step prediction.
tags:
- Source Themes
title: "DKMGP: A Gaussian Process Approach to Multi-Task and Multi-Step Vehicle Dynamics Modeling in Autonomous Racing"
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
