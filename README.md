## Network-Analysis

# MITx - MicroMasters Program on Statistics and Data Science - Data Analysis: Statistical Modeling and Computation in Applications - Third Project

The third project of the MIT MicroMasters Program course on Data Analysis focused on networks with the goal of understanding the behaviors and relatioships between the actors in two different datasets. The first dataset is from a time-varying criminal network that is repeatedly disturbed by police forces and the second from individuals who were arrested in Quebec between 2003 and 2010.

The first dataset, which can be downloaded from the internet, consists of the CAVIAR investigation that lasted two years from 1994 to 1996. The operation brought together investigation units of the Montréal police and the Royal Canadian Mounted Police of Canada. During this two year period, 11 wiretap warrants, valid for a period of about two months each, were obtained. The case is interesting because, unlike other investigative strategies, the mandate of the CAVIAR project was to seuze the drugs without arresting the perpetrators. During this period, imports of the trafficking network were hit by the police on 11 occasions. The arrests took place only at the end of the investigation. Monetary losses for traffickers were estimated at 32 million dollars. Eleven seizures took place throughout the investigation, where in some phazes there were no seizures and in some multiple, as can be seen from the summary:

    - Phase 4     1 seizure       $2,500,000      300 kg of marijuana
  
    - Phase 6     3 seizures      $1,300,300      2 x 15 kg of marijuana + 1 x 2 kg of cocaine
  
    - Phase 7     1 seizure       $3,500,000      401 kg of marijuana
  
    - Phase 8     1 seizure       $360,000        9 kg of cocaine
  
    - Phase 9     2 seizures      $4,300,000      2 kg of cocaine + 1 x 500 kg marijuana
  
    - Phase 10    1 seizure       $18,700,000     2200 kg of marijuana
  
    - Phase 11    2 seizures      $1,300,000      12 kg of cocaine + 11 kg of cocaine
  
The aim was to analyze the changes in the network structure and to survey the reaction and adaptation of the participants while they were subjected to an increasing number of distressing constraints.
  
The second dataset, that cannot publicly be shared unfortunately, consists of a large number of individuals who were arrested in Quebec between 2003 and 2010. The goal was to use different techniques of graph theory to analyze the network where some of the individuals have commited crimes by themselves and some with other individuals. 
  
The project dealt upon graph theory and the different methods for analyzing and visualizing networks. The application of the different methods and the code for the project was made with Jupyter Notebook which also includes analysis from the written report that was part of the projet.

## Access and Requirements

The file project3.ipynb is the Jupyter Notebook that contains all the code, visualizations and analysis of the project.

The dependencies and requirements can be seen from requirements.txt that can be installed in shell with the command:

      pip install -r requirements.txt

