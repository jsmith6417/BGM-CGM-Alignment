# **BGM CGM Alignment**

**Purpose**
Analyze how well blood glucose meter (BGM) readings align with continuous glucose monitor (CGM) values using a fixed pairing window and percent-difference bands.

**Key Idea**
Pair each BGM reading with the closest CGM value within a 15-minute window and compute the percent difference. This notebook prepares the dataset used for the accompanying Tableau visualizations.

**Visualizations**
Link to interactive dashboards on Tableau Public: https://public.tableau.com/app/profile/jeff.smith4760/viz/BGMCGMRange/BGMCGMAlignment

## Requirements
Python 3.10+ and the following packages:
- numpy
- pandas
