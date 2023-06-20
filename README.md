# Python Challenge
### Project description:
This project provide area-wide analysis for school budgeting as well as students scoring (reading & math) for 15 schools. The analysis aggregates the data and showcase obvious trends in school performance.
#### Key Analysis Features
1. Merging two datasets
2. Generating **html report using ydata_profiling** to explore the data stattistically and numerically based on sample dataset (6k records). 


#####  Analysis breakdown: 
1. Local Govenrment Area (LGA) Summary (see key metrics below):
    * Total number of unique schools
    * Total students
    * Total budget
    * Average maths score
    * Average reading score
    * % passing maths (the percentage of students who passed maths)
    * % passing reading (the percentage of students who passed reading)
    * % overall passing (the percentage of students who passed maths AND reading)

2. School summary (key metrics for each school, see **blew metrics**):
    * School name
    * School type
    * Total students
    * Total school budget
    * Per student budget
    * Average maths score
    * Average reading score
    * % passing maths (the percentage of students who passed maths)
    * % passing reading (the percentage of students who passed reading)
    * % overall passing (the percentage of students who passed maths AND reading)
3. Highest Performing schools (by % Overall Passing) - Top 5
4. Lowest Performing schools (by % Overall Passing) - Bottom 5
5. Math Score by Year
6. Reading Score by Year
7. Score by School Spending


#### Folder structure
``` yml
.
├── PyCitySchools/Starter_Code
│   ├── Images                         # This folder contain the education.png image
│   │   ├── education.png    
│   └── ..                  
|   ├── PyCitySchools                  # This folder contains the csv files and starter code
│   |   ├── Resources
│   │   |   ├── school_complete.csv
│   │   |   ├── students_complete.csv        
│   |   ├── PyCitySchools_starter.ipynb            
│   └── ..
|   ├── SchoolAnalysis.ipynb           # This is my analysis notebook            
|   ├── SchoolAnalysis_Hreport.html    # This is the html report           
|              
|___README.md
``` 
