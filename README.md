# **BGM CGM Alignment**

**Purpose**
Analyze how well blood glucose meter (BGM) readings align with continuous glucose monitor (CGM) values using a fixed pairing window and percent-difference bands.

**Key Idea**
Pair each BGM reading with the closest CGM value within a 15-minute window and compute the percent difference. This notebook prepares the dataset used for the accompanying Tableau visualizations.

## Visualizations  
[Tableau Public – BGM CGM Alignment](https://public.tableau.com/views/BGMCGMRange/BGMCGMAlignment?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  

## Article at JCS Analytics   
[Aligning CGM and BGM Readings Using Python and Tableau](https://jcsanalytics.com/index.php/articles/automation-and-workflows/aligning-cgm-and-bgm-readings-using-python-and-tableau)

## Python Version Compatibility

This program has been updated and tested using Python 3.15. It incorporates explicit lazy imports (lazy import and lazy from), introduced in Python 3.15.

If you are using Python 3.14 or earlier, remove the lazy keyword from the import statements before running the program.

This restores the standard import behavior used in earlier versions of Python.
