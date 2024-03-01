---
title: "Proximal Policy Gradient Arborescence for Quality Diversity Reinforcement Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Sumeet Batra
- Bryon Tjanaka
- Matthew Fontaine
- Aleksei Petrenko
- Stefanos Nikolaidis
- Gaurav Sukhatme


date: "2024-01-13T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In International Conference on Learning Representations (ICLR) 2024 spotlight paper 
publication_short: In ICLR 2024 (**Spotlight paper**)

abstract: Training generally capable agents that thoroughly explore their environment and learn new and diverse skills is a long-term goal of robot learning. Quality Diversity Reinforcement Learning (QD-RL) is an emerging research area that blends the best aspects of both fields -- Quality Diversity (QD) provides a principled form of exploration and produces collections of behaviorally diverse agents, while Reinforcement Learning (RL) provides a powerful performance improvement operator enabling generalization across tasks and dynamic environments. Existing QD-RL approaches have been constrained to sample efficient, deterministic off-policy RL algorithms and/or evolution strategies, and struggle with highly stochastic environments. In this work, we, for the first time, adapt on-policy RL, specifically Proximal Policy Optimization (PPO), to the Differentiable Quality Diversity (DQD) framework and propose additional improvements over prior work that enable efficient optimization and discovery of novel skills on challenging locomotion tasks. Our new algorithm, Proximal Policy Gradient Arborescence (PPGA), achieves state-of-the-art results, including a 4x improvement in best reward over baselines on the challenging humanoid domain.

tags: [Quality Diversity, Deep Reinforcement Learning, Robotics]

# Display this page in the Featured widget?
featured: true

image:
  preview_only: true
  focal_point: "Center"

links:
- icon: arXiv
  icon_pack: fab
  name: arXiv
  url: https://arxiv.org/abs/2305.13795
  
- icon: code
  name: code
  url: https://github.com/SumeetBatra/PPGA

---
