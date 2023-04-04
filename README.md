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

## Model Runs 
_Model run no. 1 (40x40 map, 0.01 spatial diffusion, 25 iterations)_
![image](https://user-images.githubusercontent.com/94464752/229818570-c14b5990-34ae-44c6-87ec-2fab0af0e69d.png)

_Model run no. 2 (40x40 map, 0.01 spatial diffusion, 2500 iterations)_
![image](https://user-images.githubusercontent.com/94464752/229819082-ed4af46e-a0d7-402a-b213-7463165a4f0b.png)

_Model run no. 3 (80x80 map, 0.01 spatial diffusion, 2500 iterations)_
![image](https://user-images.githubusercontent.com/94464752/229819367-5da58ea7-f2e6-4a57-854a-0c4981a761a8.png)

_Model run no. 4 (160x160 map, 0.01 spatial diffusion, 2500 iterations)_
![image](https://user-images.githubusercontent.com/94464752/229819807-5fd70a43-d9ec-409a-9ca4-4ca848916c34.png)

_Model run no. 5 (40x40 map, 0.1 spatial diffusion, 2500 iterations)_
![image](https://user-images.githubusercontent.com/94464752/229820030-739f662d-7812-4c13-8843-fc3149e09002.png)

_Model run no. 6 (80x80 map, 0.1 spatial diffusion, 2500 iterations)_
![image](https://user-images.githubusercontent.com/94464752/229820268-77f0e214-6f84-4f86-b872-5d092fb031b6.png)

_Model run no. 7 (160x160 map, 0.1 spatial diffusion, 2500 iterations)_
![image](https://user-images.githubusercontent.com/94464752/229820485-7dd064a7-9ff0-457a-9141-0ff0d248bbea.png)

_Model run no. 8 (40x40 map, 0.001 spatial diffusion, 2500 iterations)_
![image](https://user-images.githubusercontent.com/94464752/229820665-6ce61076-f894-4829-be88-14cb296523f4.png)

_Model run no. 9 (80x80 map, 0.001 spatial diffusion, 2500 iterations)_
![image](https://user-images.githubusercontent.com/94464752/229820861-62052755-41e6-42f4-9b15-4aa782d6e14a.png)

_Model run no. 10 (160x160 map, 0.001 spatial diffusion, 2500 iterations)_
![image](https://user-images.githubusercontent.com/94464752/229820999-9a6701db-b568-4923-915f-563dcff89aea.png)
