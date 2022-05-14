# Assignment-ASB
ASB - Research on a phylogenetic analysis paper. Recreation of methods and studies.

For this assignment, done in the biological sequence analysis curricular unit, a paper chosen by the students was studied with the goal of replicating or improving the studies carried out.
We chose to replicate most of the steps in the phylogenetic analysis (with the exception of the network analysis (NA)) and used the most suitable model for the construction of the phylogenetic trees. The original paper: "Phylogeny and differentiation of the St genome in Elymus L. sensu lato (Triticeae; Poaceae) based on one nuclear DNA and two chloroplast genes".

## lemanel2.0 
First, we created a bash script (“lemanel2.0”), with two parameters: the first one chooses the type of database that we are accessing (nucleotides, proteins...) and the second parameter reserved for the protein number. And has to be executed using the comand line of the terminal. 

This scipt uses Esearch and Efecth functions in order to colect from NCBI the intended sequences. A filter was also created to keep only the species name and sequence number.

## Phylogenetic analysis
The three files generated were aligned with the MUSCLE algorithm.
Using the software MEGA we checked which would be the ideal model and chose the following ones: "nrlTS" -> GTR, "matK" -> TN93 and "trnH-psbA" -> F81 .
The UGENE software was used to construct the trees, allowing the construction and separation of the tree groups into 5 large groups painted with the colors of the paper.

### more information:
The results and discussion, aswell as all the procedures that we carried out, are available in the report. 
