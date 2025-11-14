---
title: "Estimating camera inactivity periods from capture histories"
collection: publications
category: manuscripts
permalink: /publication/Camera_Malfunctions
date: '01/01/1970'
paperurl: 'TBD'
citation: 'TBD'
---

Link to online draft can be found [here](http://millyljones.github.io/files/Camera_Malfunctions.pdf). 
Target journal: ???.

# Summary

Camera arrays record multi-species detections in continuous time, but individual cameras may fail or malfunction at unknown intervals. A key challenge is to distinguishing between time intervals with no detections because a species is inactive and intervals with no detections because the camera is not working. Failure to account for the working state of the camera can lead to bias in estimated detection rates and species activity levels. To address this, we model the underlying camera state as a discrete-state space Markov process, and allow detection rates to depend on this latent working state.

A common approach is to discretise detections into counts over fixed time intervals and analyse them using Poisson hidden Markov models (HMMs). However, these arbitrary time interval discretisations constrain the latent state process to be estimated only over these discrete time points, which can obscure state transitions and lead to a loss of finer resolution detail.

We propose a continuous-time formulation using a Markov-modulated mark Poisson process (MMMPP). This framework allows detections to be modeled in continuous time in addition to modelling the latent camera state continuously as a continuous time Markov chain (CTMC). This approach aims to reduce information loss introduced by discretization, and allow for the camera states to be monitored in continuous time.
