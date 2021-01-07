---
title: Investigating Knowledge Tracing using Simulated Students 
layout: post
img: /images/bkt_streak_random.png
date: 2021-12-07
comments: false
---

Intelligent Tutoring Systems (ITS) are widely applied in K-12 education to help
students to learn and master skills. Knowledge tracing algorithms are
embedded in the tutors to keep track of what students know and do not know, in
order to better focus practice. While knowledge tracing models have been
extensively studied in offline settings, very little work has explored their
use in online settings. This is primarily because conducting experiments to
evaluate and select knowl- edge tracing models in classroom settings is
expensive. We explore the idea that machine learning models that simulated
students might fill this gap. We conduct experiments using such agents
generated by Apprentice Learner (AL) Architecture to investigate the online
use of different knowledge tracing models (Bayesian Knowledge Tracing and the
Streak model). We were able to successfully A/B test these different approaches
using simulated students. An analysis of our experimental results revealed an
error in the implementation of one of our knowledge tracing models that was not
identified in our previous work, suggesting AL agents provide a practical
means of evaluating knowledge tracing models prior to more costly classroom
deployments. Additionally, our analysis found that there is a positive
correlation between the model parameters achieved from human data and the
param- eters obtained from simulated learners. This finding suggests that it
might be possible to initialize the parameters for knowledge tracing models
using simulated data when no human student data is yet available.