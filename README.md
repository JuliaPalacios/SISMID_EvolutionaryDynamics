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

1st Day:
- Morning: Introduction to Phylogenetics
    -> Introduction Beast: Getting beast run.

- Afternoon 1: Tree Priors (Coalescent + birth death models):
    -> Running a skyline analysis

- Afternoon 2: Typical issues with beast runs and how to fix them + What are priors
    -> A few shorter tutorials on convergence etc.

2nd Day:
- Morning: Evolutionary Models (clock and site models), 
    -> Running different clock models, estimate 

- Afternoon 1: Accounting for population structure: Neutral trait models (DTA) and structured population models (struct coal + multitype birth death)
    -> Tutorial on one of these models

- Afternoon 2: How to visulize and interpret trees, including phylogenetic uncertainty
    -> Plotting trees tutorial
    
3rd Day:
- How to deal with recombination, Reassortment
  -> Inferring Reassortment networks
  
- Afternoon 1 Off
