---
title: "Decentralized Control of Quadrotor Swarms with End-to-end Deep Reinforcement Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Sumeet Batra
- Zhehui Huang
- Aleksei Petrenko
- Tushar Kumar
- Artem Molchanov
- Gaurav Sukhatme

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2021-09-13T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Conference on Robot Learning (CoRL) 2021
publication_short: In CoRL 2021

abstract: We demonstrate the possibility of learning drone swarm controllers that are zero-shot transferable to real quadrotors via large-scale multi-agent end-to-end reinforcement learning. We train policies parameterized by neural networks that are capable of controlling individual drones in a swarm in a fully decentralized manner. Our policies, trained in simulated environments with realistic quadrotor physics, demonstrate advanced flocking behaviors, perform aggressive maneuvers in tight formations while avoiding collisions with each other, break and re-establish formations to avoid collisions with moving obstacles, and efficiently coordinate in pursuit-evasion tasks. We analyze, in simulation, how different model architectures and parameters of the training regime influence the final performance of neural swarms. We demonstrate the successful deployment of the model learned in simulation to highly resource-constrained physical quadrotors performing station keeping and goal swapping behaviors. 

tags: [Deep Reinforcement Learning, Machine Learning, Quadrotors]

# Display this page in the Featured widget?
featured: true

image:
  preview_only: true

links:
- icon: arXiv
  icon_pack: fab
  name: arXiv
  url: https://arxiv.org/pdf/2109.07735.pdf

- icon: website
  name: website
  url: https://sites.google.com/view/swarm-rl

- icon: code
  name: code
  url: https://github.com/Zhehui-Huang/quad-swarm-rl


---
{{< youtube 49SlrTAKS18 >}}
