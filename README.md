[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12060742&assignment_repo_type=AssignmentRepo)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/[PUT-YOUR-REPOSITORY-HERE]/main)

# 27410 - Group assignment - Group 5 - THCA production in Aspergillus niger

## Project summary
Implementing and optimization of recombinant THCA production in a *Aspergillus niger* is done in the GSM-model CBS513.88. Firstly, the necessary metabolites and reactions were added to the model in order for *A. niger* to be able to produce THCA.
This gave a maximum theoretical yield of 0.3557 molTHCA/molGLC. A phenotypic phase plane analysis and dynamic flux balance analysis are performed which validate the production of THCA and biomass. Different optimization strategies were performed in order to improve the yield, including OptGene, OptKnock, Flux Scanning based on Objective Flux and Co-factor Swap Targets. Python was used to computationally perform these strategies and the code can be found in the 'Analysis' folder. 

A summary of what we achieved in this project: 
- Computed a production strategy of heterologous THCA production in *A. niger* using a GSM model CBS513.88, and employed various computational methods to improve theoretical THCA yield.
- Computed gene regulation optimization and proposed several targets to upregulate and downregulate.
- Computed media optimization and proposed several combinations.
- Computed dynamic flux batch analysis.
- Computed metabolic algorithms proposing gene knockouts aiming at optimizing THCA production.
- Investigated co-factor swapping.

## Project overview
- The GSM, implementations of the THCA pathway and performed analysis can be found in the <b>Analysis</b> folder.
- The report lives in the Report.ipynb notebook, with links to the corresponding analysis.
- Pictures used in the report are stored in the <b>Pictures</b> folder.

