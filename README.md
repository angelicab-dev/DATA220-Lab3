
# DATA220 Lab 3

The purpose of this lab is to get familiarized with how to organize project folder,
using Git commands, documenting projects, being specific with what should be 
included in version history, making purposeful commits, connecting to GitHub and publishing
the project. As well as, practicing the workflow using Git when working on new data projects. 

## Data:
The data utilized in this project are synthetic to teach data and how to identify
the tracked sample path.

## Repository Structure:
- scripts/ is a folder that store the Rscript file 
- data/sample/ is a folder that store the raw sample data such as csv files
- docs/ is a folder that contain files with documentation such as data_dictionary.md
- outputs/ is for generated results but does not create files from that directory

## Requirements:
Tested R version does not require additional R packages.

## How to run:
1. Make sure to be inside the root directory /campus-space-project/
2. Run the command: Rscript scripts/summarize_spaces.R data/sample/campus_spaces.csv

## Expected Result: check that these statistics are the output after running the command
Rows: 12
Total seats: 278
Occupied seats: 214
Available seats: 64
Occupancy rate: 77.0%
Busiest observed space: S103

## Outputs:
After the command is ran and successfully outputs the summary, it prints in the terminal
and does not create a file for the result. 
