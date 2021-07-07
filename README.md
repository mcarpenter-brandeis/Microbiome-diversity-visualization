# Microbiome taxonomic diversity visualization

#Author: Meredith Carpenter
#Assignment 5, Week 10
#Goals: Visualize characteristics of microbiome taxonomic diversity
#Input Files: clinical_data.txt, distanceFiles (per animal), diversityScores (per animal)
#Output Files: clinical_data.stats.txt, plots of 2 highest and 1 lowest diversity score animal of 
#Additional Files: assign5.py and readme.txt

#Program details:
#Step 1: User inputs clinical data file of choice. File is read into a dataframe array
#Step 2: Mean diversity score (with stdev) for each species is calculated and appended to the dataframe
#Step 3: The highest(2) and lowest(1) scoring species are extracted for further consideration
#Step 4: Distance scatterplots are generated for each of the three selected species
#Extra credit: The elbow method produces a plot to determine ideal K. 
#That k is used to generate K Means plot for each of the three species, colored by cluster

#To execute code:
#python3 visualizations.py
#when prompted for the datafile please input: inputfiles/clinical_data.txt
#you can choose your prefered color for each of the three initial distance plots
#please use an acceptable matplotlib color code (i.e. b, 0.2, #1f77b4, tab:pink)
