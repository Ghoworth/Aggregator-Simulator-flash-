
# Linear Aggregarator Simulator Using Flash
Simulations of a complex model of aggregators acting in a market place have been carried out using a Python based agent based modelling framework known as PyEMLab-Agg.

Results from hundreds of simulations using different parameter settings have been analysed using the statistical package SPSS.  Using the said analysis a Flash based simulator was developed using SAP Xclecius.

Flash has been deprecated , so if you want to use this flash (swf object) you will need to use an emulator that works with actionscript3 components - see 
https://nosamu.medium.com/flash-player-emulators-how-to-play-swfs-in-2021-and-beyond-d56c3899b7e6

Ps you could still use the original flash player in a closed environment.


WAFlash can be used to view the swf in this repository.  

Download swf file (linear sim.swf) to your local machine.
Navigate to https://clubpenguinadvanced.github.io/waflash-demo/

Choose file linear sim.swf ( from download location)

After a few minutes, the swf player will be available.  Note user can drag sliders to change key parameters.  Or click risk button to switch on/off risk management.  This swf file was developed as part of my PhD thesis - which provides more details on the various parameters.


## Authors

- [@Ghoworth](https://www.github.com/octokatherine)


## Documentation



Drivers of the Dynamics: The Significant Parameters in this Simulation

Overall, the dynamics of the simulation in this work depend on a number of variables including the level of competing conventional generation; the imbalance volume requirements (flexibility volumes required); the amount of flexibility supplied by domestic & industrial customers; the number of aggregators and so on. There are many variables that can be adjusted, so which ones are more important than the others? A standard approach used in the social sciences and econometrics is to statistically analyse the drivers for statistical significance using techniques like multilinear regression. 

Batch Runs: Parameter Sweep 

PyEMLab was modified to take parameter values from a CSV file and run multiple cases under different parameters. 
 


Around 300 runs, over 3000 ticks/hours were collated and later analysed using SPSS 25. The key element of this analysis was to highlight the significant drivers in the simulation for key output variables including clearing price (CP) , Hurst exponents (an indicator of simulation dynamics), aggregator profits, customer revenues, and Agent_Zero average scores (V, P, S,D). Such analysis could also be used to create simpler models of the process currently being simulated, but care should be taken with this as the equations derived depends on the input data used in the simulation.

To facilitate an initial analysis, a multilinear regression has been performed. The system is clearly non-linear so a linear approximation may be inappropriate in some cases. However, a multilinear regression analysis is easy to interpret than a more complicated nonlinear one. 

The simulator provides a visualisation ogf the deriverd equations.

