# SISMID

Instructor(s):
Palacios, Julia, Müller, Nicola

Prerequisites: This module assumes knowledge of the material in Module 1: Probability and Statistical Inference, though not necessarily from taking that module.

This module covers the use of phylogenetic and bioinformatic tools to analyze pathogen genetic variation and to gain insight into the processes that shape their diversity. The module focuses on phylogenies and how these relate to population genetic processes in infectious diseases.

In particular, the module will cover Bayesian Evolutionary Analysis by Sampling Trees (BEAST). This software will be used in class exercises that are mainly focused on estimating epidemic time scales, reconstruction changes in viral population sizes through time and inference of spatial diffusion of viruses. Evolutionary processes including recombination and selection will also be considered.

Topics:
1. Introduction to molecular epidemiology and infectious disease phylodynamics

2. Phylogenetic Inference: Sequence Alignment

3. Phylogenetic Inference: Building Trees

4. Alignment and tree reconstruction using Seaview: A hands-on practical

5. Bayesian phylogenetics

6. <del> Advanced Bayesian Phylogenetics: Phyloalignment </del>

7. Advanced Bayesian Phylogenetics: Recombination and Reassortment *Nicola*

8. Estimating Evolutionary Rates and Divergence times: Is there clock signal.

9. Estimating rates and dates from time-stamped sequences: A hands-on practical

10. Viral epidemiology and the Coalescent

11. Non-Parametric Bayesian Population Dynamics Inference *Julia

12. Revealing the evolutionary dynamics of influenza

13. Accounting for population structure

14. Phylogeographic inference in discrete space: A hands-on practical

15. Phylogeographic inference in continuous space: A hands-on practical

16. Learning to Count:Tests for Evolutionary Innovation and Robust Sequence Distance
Estimation  [Potential change: Julia to testing different tree distributions  https://juliapalacios.github.io/research/publications/2019.12.23.887125v1.full.pdf]

17. Research Acknowledgments

## Schedule
The tutorials will all follow the same overall workflow, which will naturally lead to a lot of repetition. 

1st Day: What are tree and how to get them, what is Bayesian Phylogenetics and how to run a Bayesian Phylogenetics analysis
- Morning: Introduction to Phylogenetics, including how to get from viruses to sequences to trees
    * Running a basic BEAST analysis. Suggested tutorial: [https://taming-the-beast.org/tutorials/Introduction-to-BEAST2/](https://taming-the-beast.org/tutorials/Introduction-to-BEAST2/)

- Afternoon 1: Evolutionary Models (clock and site models), 
    * Running different clock models, estimate. Suggested tutorials: [https://taming-the-beast.org/tutorials/Molecular-Dating-Tutorial/](https://taming-the-beast.org/tutorials/Molecular-Dating-Tutorial/), [https://taming-the-beast.org/tutorials/Substitution-model-averaging/](https://taming-the-beast.org/tutorials/Substitution-model-averaging/)

- Afternoon 2: Tree Priors/Population models (Coalescent + birth death models), skyline dynamics *JULIA*:
    * Running a skyline analysis. Suggested tutorial: [https://taming-the-beast.org/tutorials/Skyline-plots/](https://taming-the-beast.org/tutorials/Skyline-plots/)

2nd Day: How to deal with different evolutionary and population processes and maybe how to present your analyses

- Morning: Accounting for population structure: Neutral trait models (DTA) and structured population models (struct coal + multitype birth death) *NICOLA*
    * Tutorial on one of these models. Suggested Tutorials: [https://taming-the-beast.org/tutorials/Mascot-Tutorial/](https://taming-the-beast.org/tutorials/Mascot-Tutorial/), [https://taming-the-beast.org/tutorials/Structured-birth-death-model/](https://taming-the-beast.org/tutorials/Structured-birth-death-model/).
    
- Afternoon 1: Typical issues with beast runs and how to fix them + What are priors
    * A few shorter tutorials on convergence etc. Suggested Tutorials: [https://taming-the-beast.org/tutorials/Troubleshooting/](https://taming-the-beast.org/tutorials/Troubleshooting/), [https://taming-the-beast.org/tutorials/Prior-selection/](https://taming-the-beast.org/tutorials/Prior-selection/)


- Afternoon 2: How to visulize and interpret trees, including phylogenetic uncertainty. Dealing with outliers. Alternatively, how to get your data ready. From databases to sequences alignment
    * Plotting trees tutorial
    
3rd Day: More complex topics
- Selection, fitness, recombination, Reassortment. *Nicola*
   * Inferring Reassortment networks. Suggested Tutorial: [https://taming-the-beast.org/tutorials/Reassortment-Tutorial/](https://taming-the-beast.org/tutorials/Reassortment-Tutorial/)
   



  
