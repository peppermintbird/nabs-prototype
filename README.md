## Handling time-series astronomical data with SNN architecture for exoplanet detection and characterization

Deep learning prototype model to analyze subtle spectral data from exoplanets. 

> For entertainment purposes, I call it NABS - Neural Astro-Biosignature Scanner, inspired by how many times Mr. Spock says, _“The scanner can’t identify any life forms, captain. Fascinating...”_


### Summary
This study explores the utilization of Spiking Neural Network (SNN) architecture for the analysis of time-series astronomical data, focusing on exoplanet detection and characterization. While SNNs are relatively novel in the domain of astronomical data analysis, this research presents a prototype model inspired by Kaggle and snnTorch tutorials. The primary goal is to train a small-scale SNN model capable of discerning subtle changes in spectral data during exoplanet transits and to evaluate its performance across epochs. 

However, the transit method, often used in exoplanet detection, poses challenges due to limited data and resource-heavy observations. To address this, I propose utilizing SNNs, known for efficiently processing temporal data to improve the analysis of transit signals and promote a look into sustainable space exploration.

### Goals
- Train a small-scale Spiking Neural Network model to analyze subtle changes in the spectrum during transit
- Evaluate model's performance over each epoch

### Data source 

In the context of promising space missions like NASA's Kepler and TESS missions, there were three main types of astronomical observation data—target pixel files, light curves, and tabular stellar information. However, when it comes to studying exoplanet atmospheres and identifying subtle spectral data, spectroscopic data becomes more useful.

Subtle spectral data refers to the faint and nuanced signals in the spectrum of light emitted or absorbed by celestial objects, such as exoplanet atmospheres. From spectroscopic observations, we can access clues about the composition of exoplanets' atmospheres, like water vapor, methane, or carbon dioxide molecules.

#### Transmission spectroscopy
Transmission spectroscopy involves observing a star as an exoplanet passes in front of it (transit), allowing scientists to analyze the spectrum of light that passes through the exoplanet's atmosphere. 

#### Transit method

When an exoplanet passes in front of its host star (again, transits), it blocks a portion of the star's light, causing a temporary decrease in brightness — similar to an eclypse. This dip in brightness is recorded as a characteristic pattern in the light curve.

<video src="https://github.com/peppermintbird/nabs-prototype/assets/148541376/4708d5fb-552c-4296-9e24-22e82cf3accb">
</video>
<h6>Source: https://exoplanets.nasa.gov/alien-worlds/ways-to-find-a-planet/#/2</h6>


#### Problem
The transit method, although highly succesful in detecting exoplanets, can present challenges when considering the practicality of AI-enhanced probes in deep space. The transits are often infrequent and brief, which makes gathering sufficient data time and power-consuming, thus rendering space exploration unsustainable.

#### Potential solution
To address this problem, I propose an experiment leveraging Spiking Neural Networks (SNNs). SNNs offer advantages in processing sparse and temporal data, potentially effective in analyzing intermittent transit signals. 














