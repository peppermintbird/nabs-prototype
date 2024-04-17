## Handling time-series astronomical data with SNN architecture for exoplanet detection and characterization

<div align=center>
 <img src="https://github.com/peppermintbird/nabs-prototype/assets/148541376/b883130a-d1b4-434c-adea-5ae7e9b7925e" style="width:12%"><h1>NABS</h1>
</div>

> For entertainment purposes, I call it NABS - Neural Astro-Biosignature Scanner, inspired by how many times Mr. Spock says, _“The scanner can’t identify any life forms, captain. Fascinating...”_

---
<table>
  <tr>
    <td rowspan="2" colspan="2">🔭 Project phase: exploration</td>
  </tr>
</table>


### Summary
This study explores the utilization of Spiking Neural Network (SNN) architecture for the analysis of time-series astronomical data, focusing on exoplanet detection and characterization. While SNNs are relatively novel in the domain of astronomical data analysis, this research presents a prototype inspired by Kaggle and snnTorch tutorials as its first model. The primary goal is to train small-scale SNN models capable of discerning subtle changes in time-series data during exoplanet transits and to evaluate its performance across epochs. 


### Overview
Spiking Neural Networks are a type of artificial neural network inspired by the biological neurons in the brain. Unlike traditional artificial neural networks that use continuous-valued activations, SNNs operate on spikes, which are discrete events that represent the firing of a neuron. This spike-based communication allows SNNs to process temporal information and handle asynchronous input. In this project, I want to explore how SNNs can be utilized as the underlying architecture for a deep-learning model aimed at exoplanet detection.


### Problem
The transit method, although highly succesful in detecting exoplanets, can present challenges when considering the practicality of AI-enhanced probes in deep space. The transits are often infrequent and brief, which makes gathering sufficient data time and power-consuming, thus rendering space exploration unsustainable.

### Potential solution
To address this problem, I propose an experiment leveraging Spiking Neural Networks (SNNs). SNNs offer advantages in processing sparse and temporal data, potentially effective in analyzing intermittent transit signals. 

### Goals
- preprocess available data;
- study baseline models and existing methods used for exoplanet detection;
- augment the data for imbalance; 
- train small-scale SNN models to analyze subtle changes in the spectrum during transit;
- evaluate models' performance over each epoch using sensitivity, specificity, test loss and AUC ROC;
- optimize models;
- compare SNN's methods with other methods;
- compare the performance of SNNs with traditional machine learning algorithms;
- documenting experiments and delivering results.

### Note
I'm looking to refine and narrow down the project's objectives and structure. That's why I split it into "phases". Right now, I'm in the exploration phase, tapping into time-series modeling, acquainting myself with various forms of astronomical data, and reviewing literature.

### Milestones
- [x] [First model (light curve data from Kepler and snnTorch package)](snn_proto_exo.ipynb) 
- [ ] Classification testing on the first model
- [ ] Second model (lightkurve package and tsai)
- [ ] Studying random forests and decision trees for benchmarking
- [ ] Studying suitable machine learning models for time series forecasting tasks
- [ ] Third model (atmospheric spectra)














