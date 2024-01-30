# Project-CS
Project plan
Project Title (max. 200 characters): Varicella Dynamics: Understanding Vaccination and Immunity in Age-Specific Populations
Team members: Christina Keng(13044567)
                           Yuqi Yang(13103083)
                           Yixuan Cui(13594303)
Team number and team name (optional): 11

Scientific question (max. 350 words)
Spread of Varicella (chickenpox)
Background of the problem  
Varicella (Chickenpox) is a highly contagious disease caused by the Varicella-Zoster Virus (VZV), which belongs to the shingles family of viruses. Infected people are infected through airborne droplets or contact with a person with the shingles virus. In the present day, chickenpox still exists and is widespread throughout the world. This disease is most common among children, and we are interested in the network that the virus spreads and the factors that may affect the spreading of the disease. 

Research problem

To what extent do age and vaccine affect the number of infected people in different networks?
1. The number of people infected with chickenpox in different age groups 
2 To what extent does the vaccine help people not to have chickenpox 


Expected outcome

1. High rates of illness during childhood and infancy
2. Vaccinated people are less likely to get sick


Code:
The file pcs11-3.ipynb is a jupyter notebook that contains all the codes for the simulations in the Erdos-Renyi, Scale-Free, Watts Strogatz, and ODE models. The results from these simulations are retained within the notebook to facilitate quick review and verification without the need to re-run the simulations. The structure of the code in the notebook is as follows: 

Erdos-Renyi Networks: The code for these networks is located in cells 'In[4]' to 'In[11]'.

Scale-Free Networks: The relevant code can be found in cells 'In[12]' to 'In[13]'.

Watts-Strogatz Network: This network's code is in cells 'In[18]' and 'In[19]'.

The results of the non-vaccinated will always be the first to be presented, as it is considered as the control group of the experiment. Followed by the results of the vaccinated. A clear comparison is given in cells In[16] and In[17] together with the ODE approximations. 

Necessary Imports. 
To run the code in this notebook, the following libraries must be installed:

import matplotlib.pyplot as plt

import networkx as nx

import numpy as np

Installation Guide for Visual Studio Code Users. 

If you are using Visual Studio Code, it's recommended to install the following packages before running the code:

pip3 install networkx

pip3 install numpy

pip3 install matplotlib

A unit test is added by the end of the file that will check whether the functions are returning the correct number, length, and type. 




Reference
Corberán-Vallet, A., Santonja, F. J., Jornet-Sanz, M., & Villanueva, R.-J. (2018). Modeling chickenpox dynamics with a discrete time Bayesian stochastic compartmental model. Complexity, 2018, 1–9. https://doi.org/10.1155/2018/3060368 
Jackson, C., Mangtani, P., Fine, P., & Vynnycky, E. (2014). The effects of school holidays on transmission of varicella zoster virus, England and Wales, 1967–2008. PLoS ONE, 9(6). https://doi.org/10.1371/journal.pone.0099762
Rafiq, M., Ahmed, N., Rafique, M., & Ahmad, M. O. (2020). A Reliable Numerical Analysis of Transmission Dynamics of Chicken Pox (Varicella Zoster Virus). Sci Inquiry Rev, 4(4), 31-45. https://doi.org/10.32350/sir.44.03




