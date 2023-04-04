# GIMA5-SpatioTemporalModel

Keywords: critical transitions, discrete Fourier transform, early warning signals, patch-size distribution, regime shifts, spatial diffusion, spatial skewness, spatial variance.

# Testing the Effectiveness of Various Predictors of Critical Transitions to Lower Biomass

## Research Context
Complex dynamical systems can have tipping points at which a sudden regime shift may occur, resulting in significant and irreversible ecological consequences if thresholds will be surpassed and go beyond critical transitions. Early warning signals could recognize tipping points of critical transitions at an early stage and will be crucial to anticipated to abrupt ecological transitions and avoid negative consequences. 

## Research Problem
This study investigates the problem regarding the difficulty of predicting critical transitions, in specific the critical transition to lower biomass when a limit of grazing pressure is exceeded. Predicting these tipping points of critical transitions would be possible by indicating effective early warning signals. 

## Research Objectives
Two objectives are pursued in this paper: first, to find out how effective the predictors spatial variance and spatial skewness are at detecting a critical transition to lower biomass, both individually and collectively; and second, how well other (less widely used) predictors discrete Fourier transform (DFT), and patch-size distributions can predict the critical transition. For patch sizes, two predictors are calculated: total patch count, and average patch size. In addition, by taking the parameter spatial diffusion into consideration, the effectiveness of the predictors for detecting critical transitions is checked. 

## Research Design
Investigating the main objectives is done based on a simulated vegetation growth model of grazing. By extending the developed vegetation model with these predictors, and evaluating their potential to predict the transition, this paper shows the possibility to detect transformations before critical transitions. 

## Research Findings
The main findings of this study are that spatial variance, spatial skewness, discrete Fourier transform (DFT) and total patch count are effective at detecting the critical transitions under the conditions specified for this model. The average patch size predictor fails to detect the transition when the dispersion rate is small, and the simulation map is medium-to-large in size. One potential downside of early prediction using the discrete Fourier Transform is its computational requirements.

Model run no. 1 (40x40 map, 0.01 spatial diffusion, 25 iterations)
![image](https://user-images.githubusercontent.com/94464752/229818570-c14b5990-34ae-44c6-87ec-2fab0af0e69d.png)

Model run no. 2 (40x40 map, 0.01 spatial diffusion, 2500 iterations)
![image](https://user-images.githubusercontent.com/94464752/229819082-ed4af46e-a0d7-402a-b213-7463165a4f0b.png)

Model run no. 3 (80x80 map, 0.01 spatial diffusion, 2500 iterations)
![image](https://user-images.githubusercontent.com/94464752/229819367-5da58ea7-f2e6-4a57-854a-0c4981a761a8.png)
