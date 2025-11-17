---
title: "Estimating camera malfunction times from detection histories"
collection: ENVECOSTATS
type: "Contributed Talk"
permalink: /talks/2025-07-02-talk-5
venue: "University of Lancaster"
date: 02/07/2025
location: "Lancaster, UK"
---

In-person presentation for EnvEcoStats conference 2025.

# Abstract 

Camera trap surveys are a popular and efficient method of surveying an environment. Multiple cameras are set up in an array in the study area, and take an image when an individual passes by. The camera detection histories are informative about which species were present at a given time-point and location. However, cameras within the array can malfunction in several ways. The cameras may break or run out of battery, and some cameras may malfunction and continuously take images despite no individuals being present. For long term camera deployments, records about when cameras malfunction and are repaired are not often kept. As such it can be difficult to analyse detection histories when it is not known when cameras are operating normally. The detection histories contain time-stamps for each image taken by a camera, and images can be ‘marked’ if they indicate the presence of an individual. We model these data using a Markov Modulated Mark Poisson Process (MMMPP) in a Bayesian framework. The MMMPP models the latent camera operationality as a continuous time Markov Process, and then detection rates and mark distributions conditional on the underlying state of the camera. Given the posterior distributions for model parameters, we then estimate for each camera the probability that it was operational, non-operational, or mis-firing at each timepoint throughout the survey period. This provides a flexible framework for camera trap practitioners to estimate the malfunction times of cameras during the survey.

[Conference slides](http://millyljones.github.io/files/ENVECOSTATSslides.pdf)

<img src='/images/ENVECOSTATS.png'>
