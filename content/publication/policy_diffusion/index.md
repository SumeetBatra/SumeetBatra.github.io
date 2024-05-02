---
title: "Generating Behaviorally Diverse Policies with Latent Diffusion Models"

# Authors 
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: 
- Karkala Hegde
- Sumeet Batra
- K.R. Zentner 
- Gaurav Sukhatme 

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2023-12-13T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Conference on Neural Information Processing Systems (Neurips) 2023
publication_short: In Neurips 2023

abstract: Recent progress in Quality Diversity Reinforcement Learning (QD-RL) has enabled learning a collection of behaviorally diverse, high performing policies. However, these methods typically involve storing thousands of policies, which results in high space-complexity and poor scaling to additional behaviors. Condensing the archive into a single model while retaining the performance and coverage of the original collection of policies has proved challenging. In this work, we propose using diffusion models to distill the archive into a single generative model over policy parameters. We show that our method achieves a compression ratio of 13x while recovering 98% of the original rewards and 89% of the original coverage. Further, the conditioning mechanism of diffusion models allows for flexibly selecting and sequencing behaviors, including using language.
Project website: https://sites.google.com/view/policydiffusion/home.

tags: [Diffusion Models, Quality Diversity, Reinforcement Learning, Robotics]

# Display this page in the Featured widget?
featured: true

image: 
  preview_only: true
  focal_point: 'Center'
  placement: 1

links:
- icon: arXiv
  icon_pack: fab
  name: arXiv
  url: https://arxiv.org/abs/2305.18738
  
- icon: website
  name: website
  url: https://sites.google.com/view/policydiffusion/home
  

---
