# DSP
Digital Signal Processing

## Overview
This project aims to detect epileptic seizures by performing digital signal
processing (DSP) on EEG signals. Using Fourier analysis methods, such as Fast
Fourier Transform (FFT) and Discrete Fourier Transform (DFT), the signals are 
analyzed in the frequency domain. Additionally, statistical analysis is 
conducted in the time domain to improve detection accuracy. The project 
leverages MATLAB for signal processing, analysis, and visualization.

## Features
1. - Fourier Analysis: Utilizes FFT and DFT to transform EEG signals from the   time domain to the frequency domain for identifying seizure patterns.
2. - Time-Domain Analysis: Conducts statistical analysis (e.g., mean,variance)  of EEG signals to enhance detection in the time domain.
3. - Signal Processing: Uses MATLAB for signal analysis, visualization, and     interpretation of the data.
4. - Detection of Epileptic Seizures: Accurately identifies epileptic seizures  through frequency-based irregularities in EEG signals.


## Project Structure
src/: Contains MATLAB code for signal processing and seizure detection.
data/: Includes EEG signal datasets used for analysis.
results/: Stores the output plots and detection results for different EEG signals.
docs/: Documentation and reports on the project, including analysis and findings.


## Installation steps

1. - Fork the [repo](https://github.com/akki541/DSP---Course-project.git)
   - Clone the repo to your local machine `git clone https://github.com/akki541/DSP---Course-project.git`
   - Change current directory `cd DSP---Course-project`
2. run the file matlab file .m
   - run('src/EEGSeizureDetection.m')


## Results
The project successfully detects epileptic seizures by analyzing EEG signals. The following types of results are generated:

1. - Frequency-Domain Analysis: Visual representation of frequency components,  with spikes in particular ranges indicating seizures.
2. - Time-Domain Analysis: Plots that show the statistical behavior of EEG      signals over time.
