# Micro-Nanoplastics
CODE TO ASSESS THE EFFECTS OF MICROPLASTICS/NANOPLASTICS ON GROWTH PATTERN, BODY CONDITION AND GENE EXPRESSION OF ANY FISH

1. Microplastics have been shown to cause direct toxic effects, act as carriers for pathogens, and facilitate the spread of invasive species (Ferreira et al., 2019). However, research on the presence and impacts of nanoplastics in fish remains in its early stages. 
2. Overall, the goal here is to develop and demonstrate the application of a python code that can be used to analyse the effects of micro/nanoplastics on fish under different treatment conditions and create a volcano plot to visualize differentially expressed genes.  
3. Methods
4. Data was generated randomly for the four treatments groups having both length(mm) and weight (g), labelled and assumed to be from a juvenile fish after 48 hours of exposure.
5. Each treatment was assumed to have 16 replicates exposed to 0, 1, 10 and 100 particles/l of polyethylene nanoplastic particles.
6. Gene expression data was obtained from Sanbomics and modified to only include 534 genes (Mark, 2024).
7. Data analysis was performed using python programming language (python version 3.12.7) using Jupyter Notebook, version 7.2.2 through Anaconda Navigator version 2.6.3. Analysis of variance involved both one-way analysis of variance and Kruskal Wallis test even after checking for the assumptions followed by a Post Hock test.
8. This was done to demonstrate the performance of the python code. Gene expression analysis was undertaken using a customizable volcano plot meant to be easy to replicate.


