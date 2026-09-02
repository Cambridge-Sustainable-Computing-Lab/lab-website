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
Results from these experiments are compared with data sourced from high-performance computing (HPC) clusters and publically-available databases to ensure the accuracy and widespread applicability of the power models we develop.

<style>
  .no-shadow-figure .figure-image img {
    box-shadow: none !important;
    border: none;
    border-radius: 0;
  }
</style>
<div class="no-shadow-figure">
{% include figure.html image="images/projects/test-bench-desk-setup-greybg.jpg" caption="Computational test bench (centre) for power measurement of scientific workloads" width="75%" %}
</div>

## Get involved in this work

<b>Are you interested in understanding the energy usage of your scientific workloads?</b>
If so, we would be happy to run a provided workload on the test bench!
You will recieve a detailed report on the power consumption behaviour of your workload while simultaneously assisting us by providing data relevant across different scientific computing fields.

We are currently finalising a standardised protocol to enable a smooth benchmarking procedure and ensure consistency across submissions.
While the full documentation is being prepared, please feel free to get in contact directly with [Jack](/members/Jack-Coker.html) to discuss running your workload on the test bench!

[//]: # ToDo: Link to protocol (Including: requirements / inputs / how you should prepare your workload before sending, 2) what we do with your workload / The measurement process, and 3) outputs for you / outputs for us )