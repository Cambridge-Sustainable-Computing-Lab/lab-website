---
title: Power Modelling
description: Understanding the power usage of scientific computing
---

# {% include icon.html icon="fa-solid fa-bolt" %}Power Modelling

<p style="text-align: center; font-size: 1.25rem;">Understanding the power usage of scientific computing</p>

{% include section.html %}

The tools developed by our lab, such as the [Green Algorithms online calculator](https://calculator.green-algorithms.org/), rely on predictive models to estimate the power consumption of computational work.
To improve the accuracy, reliability, and validity of these models, we collect and analyse power usage data from a variety of sources.

One important source of data is from experiments run on an in-house <b>computational test bench</b>, purpose built for the collection of fine-grained power measurements under controlled conditions. 
We run a combination of synthetic benchmarks (A.K.A. stress tests) and realistic scientific workloads on the test bench while monitoring the power draw of indivdual compute components and the system as a whole.
Results from these experiments are compared with data sourced from high-performance computing (HPC) clusters and publically-available databases to ensure the accuracy and widespread applicability of the predictive power models we develop.

[//]: # ToDo: potentially add image of test bench?

[//]: # ToDo: callout to collaborators

[//]: # ToDo: Link to protocol (Including: requirements / inputs / how you should prepare your workload before sending, 2) what we do with your workload / The measurement process, and 3) outputs for you / outputs for us )