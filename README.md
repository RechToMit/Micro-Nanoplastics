
# Micro-Nanoplastics
CODE TO ASSESS THE EFFECTS OF MICROPLASTICS/NANOPLASTICS ON GROWTH PATTERN, BODY CONDITION AND GENE EXPRESSION OF ANY FISH
BACKGROUND
1. Microplastics have been shown to cause direct toxic effects, act as carriers for pathogens, and facilitate the spread of invasive species (Ferreira et al., 2019). However, research on the presence and impacts of nanoplastics in fish remains in its early stages. 
2. Overall, the goal here is to develop and demonstrate the application of a python code that can be used to analyse the effects of micro/nanoplastics on fish under different treatment conditions and create a volcano plot to visualize differentially expressed genes.
NB: The code can be scaled to work with any number of treatments, and also extended(code not available)  to statistically analyze/compare  spatial/temporal variations in grow patterns, body condition, levels of mnps from  field samples
 
4. Methods
5. Data was generated randomly for the four treatments groups having both length(mm) and weight (g), labelled and assumed to be from a juvenile fish after 48 hours of exposure.
6. Each treatment was assumed to have 16 replicates exposed to 0, 1, 10 and 100 particles/l of polyethylene nanoplastic particles.
7. Gene expression data was obtained from Sanbomics and modified to only include 534 genes (Mark, 2024).
8. Data analysis was performed using python programming language (python version 3.12.7) using Jupyter Notebook, version 7.2.2 through Anaconda Navigator version 2.6.3. Analysis of variance involved both one-way analysis of variance and Kruskal Wallis test even after checking for the assumptions followed by a Post Hock test.
9. This was done to demonstrate the performance of the python code. Gene expression analysis was undertaken using a customizable volcano plot meant to be easy to replicate.

Instructions:
1. Download all the python files and the two datasets (GENE_EX and Microplastics1).
2. Put all the files in your working directory
NB: For ease of replication, a) when using a different dataset, just change the name of the variables in the code
b) Don't forget to change variable names under if statements. c) Remember to adjust the thresholds as required. 
3. The intended outputs are shown in the .png files while other summary statistics are availabe within the code

Limitation
The datasets used were not directly generated from actual fish experiments and their interpretation should only be left for demonstrating the functionality of the code. Also, top DEG are still not shown in the vaolcano plot.
