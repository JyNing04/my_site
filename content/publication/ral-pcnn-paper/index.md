---
abstract:  Autonomous racing is a critical research area for autonomous driving, presenting significant challenges in vehicle dynamics modeling, such as balancing model precision and computational efficiency at high speeds ( > 280 km/h), where minor errors in modeling have severe consequences. Existing physics-based models for vehicle dynamics require elaborate testing setups and tuning, which are hard to implement, time-intensive, and cost-prohibitive. Conversely, purely data-driven approaches do not generalize well and cannot adequately ensure physical constraints on predictions. This letter introduces Deep Dynamics, a physics-constrained neural network (PCNN) for autonomous racecar vehicle dynamics modeling. It merges physics coefficient estimation and dynamical equations to accurately predict vehicle states at high speeds. A unique Physics Guard layer ensures internal coefficient estimates remain within their nominal physical ranges. Open-loop and closed-loop performance assessments, using a physics-based simulator and full-scale autonomous Indy racecar data, highlight Deep Dynamics as a promising approach for modeling racecar vehicle dynamics.
authors:
- John Chrosniak
- admin
- Madhur Behl
date: "2024-06-01T00:00:00Z"
doi: "10.1109/LRA.2024.3388847"
featured: true
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false
# links:
# - name: Custom Link
#   url: http://example.org
projects:
- internal-project
publication: In *IEEE Robotics and Automation Letters*
publication_short: In *RAL 2024*
publication_types:
- "1"
publishDate: "2024-06-01T00:00:00Z"
# slides: example
summary: This letter introduces Deep Dynamics, a physics-constrained neural network (PCNN) for autonomous racecar vehicle dynamics modeling.
tags:
- Source Themes
title: Deep Dynamics: Vehicle Dynamics Modeling With a Physics-Constrained Neural Network for Autonomous Racing
url_pdf: https://ieeexplore.ieee.org/abstract/document/10499707
# url_poster: https://drive.google.com/file/d/1X7j7fjZ_5uMGaTjjYIBgr75FSJEmYaB0/view?usp=sharing


---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->

