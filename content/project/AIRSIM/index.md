---
title: End-to-End Deep learning for Autonomous Driving based on AirSim
summary:  In this project, I focused on constructing an end-to-end deep learning architecture to train the autonomous car based on an open-source simulator called AirSim, which is developed by Microsoft.
tags:
- Simulator
- Self-driving

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by [**AirSim**](https://github.com/microsoft/AirSim)
  focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: https://drive.google.com/file/d/1I-88aDtW4OkEFdaC0PtPwxo57nP09qr8/view?usp=sharing
url_slides: ""
url_video: https://youtu.be/0cGFGLdZwaA

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---
Deep learning architecture-based artificial intelligence has become a cornerstone in the automotive industry, with applications spanning computer vision, natural language processing, sensor fusion, target recognition, and autopilot systems. Recent advancements in software, hardware, and cloud computing have facilitated the processing of vast data volumes, catalyzing the pursuit of higher autonomy levels, particularly levels 4 and 5. According to Nidhi Kalra (2016), reaching these autonomy levels necessitates training on an immense scale, requiring hundreds of millions to even hundreds of billions of miles of data to ensure reliability.

However, the current rate of data collection is still not adequate to satisfy the stringent demands of autonomous driving. This gap underscores the necessity of simulation technologies. Simulation platforms, such as AirSim, are invaluable in this context. They not only enable the efficient gathering of data from a diverse array of scenarios, which would otherwise take years to accumulate, but also provide a safe environment for testing trained models. The advent of behavioral cloning in these simulations allows individuals with the requisite expertise to develop highly effective models. These models can be initially honed in simulated environments and subsequently fine-tuned with a smaller dataset derived from real-world conditions, thereby optimizing the development process of autonomous driving technologies.

In this project, I successfully trained an autonomous driving vehicle using an end-to-end deep learning architecture, employing a self-collected dataset with AirSim. The dataset was strategically split, with 80% for training and 20% for testing. The model, honed through neural network training, achieved a notable validation loss of approximately 0.001, indicating effective learning and enabling the vehicle to autonomously navigate for about 3 minutes without any crashes. While there is room for further development and improvement, this project has been a significant learning experience. Moving forward, I am eager to enhance the model's performance and explore new frontiers in autonomous vehicle technology.