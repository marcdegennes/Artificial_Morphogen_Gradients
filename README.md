# Artificial_Morphogen_Gradients

Source codes for the paper "Patterning and growth control in vivo by an engineered GFP gradient ". 
The codes describe the measurement and analysis of experimental data, as well as simulations of the theory described in the supplementary materials.
The folder "Part1" is about artificial morphogen gradients with a single receptor, and the folder "Part2" is about gradient formation with two receptors.

# Part1

**Science-Part1_Measuring_gradient_properties.ipynb**

In this notebook we measure the characteristic of the artificial gradients of the 1st part of the paper, and of the pMad gradients of the 2nd part of the paper.
For each curve ,when applicable, the length at half maximum and the ratio of the plateau value over the maximal value are measured. 

![Alt text](./apical_model_varying_h.eps?raw=true)

**Science-Part1_Figures_and_Fitting_procedure.ipynb**

In this notebook we simulate the formation of artificial gradients with one receptor. The code is used to generate figures 2B,2C,3A,S5-H,I,J,K and S6-A of the paper. We then show the minimization procedure used to fit the parameters of the model, as well as an example of the statistical bootstrapping method used to test the validity of our fit. 

**Science_Part1_Effect_of_boosting.ipynb**

GFP is known to fluoresce 1.5 times stronger when bound to the high affinity nanobody. In this notebook we fit the parameters taking this effect in account, and show that the fitted parameters and the predictive curve vary very little when this boosting in GFP fluorescence is included. The graphs of Fig S4-B,D,F are drawn. 

**Science -Part1_Invasion_of_tissue_by_a_GFP_bath_.ipynb**

In this notebook we look at the invasion of GFP along the baso-apical direction of cells when the pouch is put in contact with GFP baths at different concentrations (see Supplementary 1.7). From the dynamics we infer the surface density and diffusivity of receptors. The notebook performs several tests validating the quasi static approximation of equation (30) of the supplementary material. It then fits the experimental data to find the diffusion constant and quantity of receptors, and displays an example of the statistical method used to estimate the error on those parameters.   


**Science-Part1_Apical_Gradients.ipynb**

This notebook is about the formation of gradients in the peripodial space, on the apical side of cells (see Supplementary 1.8). It first plots the experimental apical profiles for the different conditions (Fig S3-C,D), and then simulates the formation of apical profiles (Fig S3-E).

# Part2

**Science-Part2_two-receptors.ipynb**

In this notebook we define the dynamics of the two-receptor artificial gradient model studied the the 2nd part of the paper. We simulate the steady state gradients for the three experimental conditions of interest (SR, SR+SR, SR+NR) and study the role of NR diffusion and handover by exploring the parameter space around the estimates provided in Supplementary Tables 2-3. The graphs of Fig 5,S5G,S13 are drawn.


