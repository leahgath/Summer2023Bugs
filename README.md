# Summer2023Bugs

Goals for dataset:
1. Calculate plant diversity within quadrats 
2. Calculate plant diversity across quadrats at a site
3. Calculate plant diversity across sites
4. If possible, also calculate plant diversity metrics for plant structural types 
5. Write code in a way that vibrational data can be plugged in and run through the same code
  to determine vibrational signal diversity at quadrat level, site level, and across site level

My files will be structured following a numeric system, such that all files related to
data tidying will begin with 01, all files related to data analyses will begin with 02,
and all files related to figure development and results will begin with 03. The raw data file
will begin with 00. All files will be organized into a data folder, coding folder, and results
folder depending on their type. 

Currently, I am planning for my naming system to look as follows: 
00_Summer23_Plants_Site.csv 
00_Summer23_Signals_Site.csv 
01_Summer23_Plants_Site_CLEAN.csv
01_Summer23_Signals_Site_CLEAN.csv

01_Summer23_DiversityData_Tidy.R
02_Summer23_DiversityAnalysis.R
03_Summer23_DiversityGraphs.R

02_Summer23_DiversityResults_Plants.Rmd
02_Summer23_DiversityResults_Signals.Rmd

03_Summer23_PlantAlpha_Quadrat_Site_Figure.pdf
03_Summer23_PlantBeta_QuadAQuadB_Site_Figure.pdf
03_Summer23_PlantGamma_SiteA_SiteB_Figure.pdf
03_Summer23_SignalAlpha_Quadrat_Site_Figure.pdf
03_Summer23_SignalBeta_QuadAQuadB_Site_Figure.pdf
03_Summer23_SignalGamma_SiteA_SiteB_Figure.pdf