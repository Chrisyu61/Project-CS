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

Numerical method (max 100 words)
Using the Erdoys Renyi method, we can simulate random interactions in a population and show how the disease spreads when the network is completely random. However, due to the randomness of this method, it has the limitation of assuming equally likely interactions for all nodes. We will also use the scale-free method to fill in this limitation. This method will have nodes with higher connections and some with lesser connections. This will represent scenarios where children go to school, or adults go to work and interact more with other people. 
SIR- This method is a classical framework used to understand the dynamics of infectious diseases. This method categorizes the population into susceptible, infected, or recovered. We use this method to simulate the progression of the disease through these stages, and can be integrated with the Erdos-Renyi and Scale-Free networks to understand how chickenpox spreads. 
SIR Model ODEs:
dSdt = -SIN
dIdt = SIN-I
dRdt = I

Provisioned tools (max 100 words): 
Python
Python Libraries:
Matplotlib
Numpy
Scipy
Pandas	
NetworkX
Seaborn
Scikit-learn
Jupyter Notebook
Github





Plan for division of work (max 100 words):

Task
Person
Project proposal
All
Project proposal peer review
All
Coding
All
Poster
All
Presentation
All



Timeline (max 100 words):
<A short timeline plan from the start of the project till the end of the course. Keep it concise and realistic, no complicated GANT is necessary.>

Due Task
Task
Jan 7 - 10
Project Proposal
Jan 10 - 12
Project Proposal Peer Review
Jan 12 - 22
Code for model, simulation, and visualization
Jan 23 - 28
Write report
Jan 29 - 31
Create Poster and prepare the presentation
Feb 1
Presentation








Reference
Corberán-Vallet, A., Santonja, F. J., Jornet-Sanz, M., & Villanueva, R.-J. (2018). Modeling chickenpox dynamics with a discrete time Bayesian stochastic compartmental model. Complexity, 2018, 1–9. https://doi.org/10.1155/2018/3060368 
Jackson, C., Mangtani, P., Fine, P., & Vynnycky, E. (2014). The effects of school holidays on transmission of varicella zoster virus, England and Wales, 1967–2008. PLoS ONE, 9(6). https://doi.org/10.1371/journal.pone.0099762
Rafiq, M., Ahmed, N., Rafique, M., & Ahmad, M. O. (2020). A Reliable Numerical Analysis of Transmission Dynamics of Chicken Pox (Varicella Zoster Virus). Sci Inquiry Rev, 4(4), 31-45. https://doi.org/10.32350/sir.44.03




