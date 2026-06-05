---
layout: blog_post
title: 'My Research Directions: GeoAI, Human Mobility, and Disaster Resilience'
date: 2025-09-15
tags:
  - Research
  - GeoAI
  - Disaster Resilience
---

Starting a Ph.D. is a good moment to pause and articulate what you actually want to work on. I recently joined the [GeoAI Lab](https://www.yingjiehu.com/) at the University at Buffalo, advised by Prof. Dr. Yingjie Hu, and I thought it would be useful to write out my research directions — both for clarity in my own thinking and to share what I find exciting.

My work sits at the intersection of three themes: **GeoAI**, **Human Mobility**, and **Disaster Resilience**. Here's what each of those means to me.

---

## GeoAI: Where Machine Learning Meets Geography

GeoAI is about applying AI and machine learning to geospatial problems — but it's more than just "deep learning on maps." Geography introduces a set of constraints and principles that don't appear in standard ML benchmarks: spatial autocorrelation, scale dependency, the modifiable areal unit problem, and the need to generalize across environments that look very different from the training data.

My prior work gave me a taste of these challenges. In my M.S. research at the University of Zurich and ETH Zürich, I worked on reconstructing high-resolution Digital Elevation Models (DEMs) using Conditional Generative Adversarial Networks (CGANs). The key insight was that terrain has structure — ridges, valleys, watersheds — and capturing that structure requires architectures that encode topographic priors, not just pixel-level patterns. We achieved a 71.96% improvement in reconstruction accuracy over traditional interpolation, which was encouraging, but the more important lesson was about how domain knowledge shapes model design.

Going forward, I want to push this further: how can we design AI models that are genuinely geography-aware, not just spatially indexed?

---

## Human Mobility: Reading Patterns in Where People Go

Human mobility data — from GPS traces, mobile phone records, or geotagged social media — contains a rich signal about how people organize their lives and respond to their environment. Understanding this signal matters for urban planning, public health, and disaster response.

One application I'm particularly interested in is **wildfire smoke exposure modeling**. During major wildfire events, smoke can travel thousands of kilometers, affecting populations far from the fire itself. But exposure is uneven: some people spend more time outdoors, some live in areas with worse air quality, and some lack the resources to avoid exposure. Mobility data lets us move beyond crude geographic proximity to estimate actual exposure at the individual or community level.

This connects human behavior to environmental hazards in a way that static spatial analysis cannot capture.

---

## Disaster Resilience: Understanding Vulnerability and Recovery

The third strand of my research concerns how communities respond to disasters — before, during, and after. Disaster resilience is not just about physical infrastructure; it's about social and economic capacity, information access, and the spatial distribution of vulnerability.

I'm interested in using geospatial data and AI to map informal settlements, which are often among the most disaster-vulnerable communities and are systematically underrepresented in official datasets. Remote sensing offers a path to more complete and up-to-date information about where these communities are and what conditions they face.

---

## What Connects These Themes

All three directions share a common thread: using geospatial data and computational methods to understand human-environment interactions, with particular attention to populations and places that are often overlooked. Whether it's smoke exposure during wildfires, flood risk in informal settlements, or mobility patterns that reveal social inequality, the underlying questions are about who is affected, where, and why.

I'm at the beginning of this journey. If you're working on related problems or have thoughts on any of these directions, I'd love to hear from you.
