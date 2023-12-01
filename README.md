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
In this project we decided to try and optimize recombinant THCA production in a *Aspergillus niger* model. Firstly, the necessary metabolites and reactions were added to the model in order for *A. niger* to be able to produce THCA. The maximum theoretical yield was calculated and phenotypic phase plane analysis was performed. Next to this, different optimization strategies were performed in order to improve the yield. Strategies include the following: OptGene, OptKnock, Manual gene knockout, Flux Scanning based on Objective Flux, Co-factor Swap Targets, Prediction of Heterologous Pathways and Dynamic Flux Balance Analysis. Furthermore the pathways have been visualized using OptFlux. Python was used to computationally perform these strategies and the code can be found in the 'Analysis' folder. 

A summary of what we achieved in this project: 
- Computed a production strategy of heterologous THCA production in *A. niger* using a GSM model, and employed various  computational methods to improve theoretical THCA yield.
- Computed gene regulation optimization and proposed several targets to upregulate and downregulate.
- Investigated co-factor swapping.
- Computed media optimization and proposed several combinations.
- Computed dynamic flux batch analysis.
- Computed metabolic algorithms proposing gene knockouts aiming at optimizing THCA production.




## Project overview
- All of our work and analysis is found in the <b>Analysis</b> folder.
- The report lives in the Report.ipynb notebook.
- Pictures used in the report are stored in the <b>Pictures</b> folder.

