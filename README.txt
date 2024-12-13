This project was created as the final project for WLF553 reproducible data science class.

This workflow is part of PhD research being carried out by Kristen Whyle at the University of Idaho on the movement ecology of bighorn sheep in Hells Canyon. 

One of the objectives of this project is to quantify the interactions between the population dynamics and spatial dynamics of these bighorn sheep, in particular to quantify how demographic and environmental factors shape herd ranges and the probability of out-of-range movements including forays and dispersals.

To address this objective we are creating a multi-state model that will assign bighorn sheep locations to 1 of three different spatial states: 1) a home range state (for points located within an individuals home population) 2) an other-range state (for points located in any Hells Canyon population range other than an individual’s home population range) and 3) a transit state (for points that are not located within any bighorn sheep population range). It will also identify when individuals’ movement steps switch between states.

Once states and state switches are identified by the model we can examine the probability of individuals switching between states based on environmental variables and population demography variables.

In this workflow we focus only on the first two components of the multi-state model; assigning states and identifying state switches in the movement data.