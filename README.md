[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12060742&assignment_repo_type=AssignmentRepo)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/[PUT-YOUR-REPOSITORY-HERE]/main)

# 27410 - Group assignment - Group 5 - THC production in Aspergillus niger

> Dear students, thank you for accepting the group assignment. Please fill in the
> requested information below and above ([Group Number] and [TITLE]) and remove this quoted part before submission (everything prepended with a >).
> Please also replace `[PUT-YOUR-REPOSITORY-HERE]` up in the first line 👆 with the name of your repository here on GitHub.
> That way someone can click on the Binder badge icon and open your project in Jupyter lab to explore it.
> For this to work you will also have to keep `requirements.txt` up to date (by running `pip freeze > requirements.txt`).
> Furthermore, this will only work if you decide to make your repository public (which you can do under Settings -> Options),
> which I would encourage you to do – up to you. A lot of good science happens out in the open these days.
> Good luck!

## Project summary (<300 words)
Describe the overall aim of your project and what you have achieved.

## Project overview
In this project we decided to try and optimize recombinant THC production in a Aspergillus niger model. Firstly, the necessary metabolites and reactions were added to the model in order for Aspergillus to be able to produce THC. The maximum theoretical yield was calculated and phenotypic phase plane aalysis was performed. Next to this, different optimization strategies were performed in order to improve the yield. Strategies include the following: Optgene, Optknock, Manual gene knockout, Flux Scanning based on Objective Flux, Co-factor Swap Targets, Prediction of Heterologous Pathways and dynamic Flux Balance Analysis. Furthermore the pathways have been visualized using OptFlux. Python was used to computationally perform these strategies and the code can be found in the 'Analysis' folder. 




#Example report:

## Project summary (<300 words)
This project is aimed at introducing the heterologous biosynthetic pathway for psilocybin production in an existing GSM of *A. niger*, and thereafter use computational methods to identify which changes to the model could optimize production. Cofactor swap optimization revealed swapping cofactor specificity of two reactions in the model from NADPH to NADH could potentially improve theoretical yield of psilocybin. Investigation of gene regulation targets revealed several reactions that could be either upregulated or downregulated to improve psilocybin production flux. Two of the enzymes targeted for upregulation are in the shikimate pathway, which leads to the psilocybin precursor tryptophan, and were also shown to improve psilocybin production in previous studies. Several new gene prediction targets for upregulation, including methylation reactions, were found that could lead to promising results in follow up studies on the effect of their upregulation. Media optimization showed that addition of YEPD to the media led to a slight reduction in yield, but an increase in the production flux of the last step in psilocybin biosynthesis by a factor of 17.

A summary of what we achieved in this project: 
- Computed a production strategy of heterologous psilocybin production in *A. niger* using a GSM model, and employed various  computational methods to improve theoretical psilocybin yield.
- Computed gene regulation targets
- Investigated co-factor swapping 
- Media optimization


## Project overview
- Our project is organized with two folders in the main folder. All of our work and analysis of the GSM, ATCC1015 iJB1325, including the model, is found in the <b>Analysis</b> folder.
- The report lives in the Report.ipynb notebook, and contains links to the notebooks in the <b>Analysis</b> folder.
- Pictures used in the report are stored in the <b>Pics</b> folder.
- Appendix is found in the <b>Analysis</b> folder. 

