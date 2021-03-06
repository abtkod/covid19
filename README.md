# CovidAlert
Covid19 is a disease that is caused by a coronavirus called SARS-CoV-2. Since its emergence in late 2019, it has affected many regions of the world. Still, there are many regions that are not infected. There is a concern that even those regions that could control this epidemic before, might face other breakouts in the future. Physical interactions among people is one of the main factors addressed in this regard. In this project, we explore the surge of covid19 in different regions of the world as well as the side effect of local communities' mobility in its resurgence.

There are two main datasets used in this project:
1) Time series of the Covid cases provided by John Hopkins University every day;
2) Global mobility report prepared by Google every ~5 days.

There are two main challenges while working with these datasets:
1) Reported data in different parts of the world do not follow the same standard. There are many factors that can affect the precision of a report. These factors are but not limited to: 
* the number of health workers who are actively monitoring covid19 cases; 
* level of expertise  and quality of equipment used to record the results; 
* health-related policies;
* economic, political, and social incentives that derive each report.
2) Comparing the result of one region to other regions is either impractical or requires great knowledge about the demographics of those regions. Besides, the level of sensitivity about fatal issues in each community is dependent on many other factors rather than the region's population or population density. Factors such as life expectancy and standard of living make a big difference here. 

Because of these challenges, in this study, we focus on the comparative condition of a region to its previous condition. Every region is assigned the baseline. This baseline is defined based on the history of reports generated for that region. Using this baseline, we then decide if the changes in daily reports show a positive surge in the number of cases or not.

# Project Structure:
* [data-exploration-notebook](https://nbviewer.jupyter.org/github/abtkod/covid19/blob/master/data-exploration.ipynb) 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/abtkod/covid19/master?filepath=data-exploration.ipynb)
* [predictive-analysis-notebook](https://nbviewer.jupyter.org/github/abtkod/covid19/blob/master/predictive-analysis.ipynb)
