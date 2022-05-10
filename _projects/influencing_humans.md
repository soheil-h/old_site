---
layout: page
title: Influencing Human-Robot Teams
description: RILI: Robustly Influencing Latent Intent
img: assets/img/projects/influencing_humans/arxiv2022.jpg
importance: 1
category: PhD
---

When robots interact with human partners, often these partners change their behavior in response to the robot. On the one hand this is challenging because the robot must learn to coordinate with a dynamic partner. But on the other hand ---if the robot understands these dynamics ---it can harness its own behavior, <em>influence</em> the human, and guide the team towards effective collaboration. Prior research enables robots to learn to influence other robots or simulated agents. In this paper we extend these learning approaches to now influence <em>humans</em>. What makes humans especially hard to influence is that ---not only do humans react to the robot--- but the way a single user reacts to the robot may change over time, and different humans will respond to the same robot behavior in different ways. We therefore propose a <em>robust</em> approach that learns to influence changing partner dynamics. Our method first trains with a set of partners across repeated interactions, and learns to predict the current partner's behavior based on the previous states, actions, and rewards. Next, we rapidly adapt to new partners by sampling trajectories the robot learned with the original partners, and then leveraging those existing behaviors to influence the new partner dynamics. We compare our resulting algorithm to state-of-the-art baselines across simulated environments and a user study where the robot and participants collaborate to build towers. We find that our approach outperforms the alternatives, even when the partner follows new or unexpected dynamics.


<p align="center"><iframe width="560" height="315" src="https://www.youtube.com/embed/lYsWM8An18g?rel=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>
