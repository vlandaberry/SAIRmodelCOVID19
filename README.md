# SAIR model COVID-19
In this repository you cand fin the code and equations for the SAIR model to analyze COVID-19 spread in a particular country. We created this model whith [@jmsancho](https://github.com/jmsancho). It is based on the more traditional epidemiological models (SIR and SEIR) but we add some modifications to adapt the dynamic of the model to some features of COVID-19 spread. 


COVID-19 has spread all over the world and different measures have been taken
by countries to control its propagation. We have used the SIR (Susceptible, Infected and Recovered) and SEIR (Susceptible, Exposed, Infected and Recovered)
models to analyze the dynamics of the propagation, estimate the number of infected population, the duration of the spread and the capacity of the healthcare
system to provide attention to patients with severe and critical symptoms.
One of the main issues of using these models to analyze COVID-19 is that
the dynamics of the virus is different from what the classical models assume, and
countries have taken measures such as quarantines, affecting the final results of
the spread of the virus.
In particular, the SIR model supposes that a susceptible person that is infected by entering in contact with an infected person remains infected and, thus,
infecting the rest of the population during all the period that it takes to recover.
The SIR model, on the other hand, does not take into account the possibility
that measures such as quarantine affect the spread once that one person has
been detected as infected.
On the other hand, the SEIR model considers that there is a latent period in
which the infected person does not transmit the disease (during this period, it’s
counted as Exposed). This assumption is not aligned with the evidence we have
so far about the nature of contagion. Indeed, COVID-19 is highly contagious,
and according to Laurel SA et al. (March, 2020) people that get the virus are
contagious since then. Also, we can have some asymptomatic cases, about 30%
of the population, that are infected and transmitting the virus, but they are not
aware of this situation and they are not identified as infected by statistics.
We present a SAIR model (Susceptible, Asymptomatic infected, Infected
tested and Recovered or dead model) that introduces some particular aspects
of COVID-19. Our goal is to adjust the estimations that we obtained using the
classical models by introducing some changes in the dynamics of the virus.

We provide the following documentation and code:
- SAIR.pdf is the model, and the equations. 
- SAIR.py is the code in python. 

The example in the code is with data from slovenia, but you can change the data (using the data of the country you are intersted in) and see the results. 


