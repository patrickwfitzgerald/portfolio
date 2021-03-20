# Data Analysis Portfolio
This repository contains data analysis projects stored as notebooks created with Jupyter Notebook.

<br>

## [Automated Exploratory Data Analysis][html_auto_EDA_code]
[View notebook with code][html_auto_EDA_code], [without code][html_auto_EDA_nocode]

Developed in October-December 2020, updated in March 2021

This is a template notebook created to greatly speed up the exploratory data analysis process of
data science projects. Once a dataset is imported and cleaned, running all the cells in the notebook
prints out an overview of the variables it contains. The plots implement the visualization
principles of Edward Tufte and Stephen Few and are inspired by the capabilities of the seaborn
package which provides the very useful pairplot function that displays all numerical-numerical relationships
in a single plot. Unfortunately, the package does not provide similar functions for visualizing numerical-categorical and
categorical-categorical relationships.

There exists other packages such as [Pandas Profiling][link_pprof],
[Sweetviz][link_sv] and [DataPrep][link_dp] which provide useful EDA tools, but they also lack these
types of visualizations. So this notebook attempts to fill this gap by making use of advanced plotting
functions that provide a concise visual overview of any dataset within a few seconds.

Currently, this notebook handles datasets which contain up to about 15 variables of which at least one
must be numerical. It designed to be viewed on a white background. It is under regular development
as I work on analyzing new datasets. Future updates may include converting plots to interactive plots using
packages such as plotly, adding steps to deal with datasets containing many variables, and processing time
series more thoroughly.

Alternative links:
- [Open notebook in nbviewer][nbviewer_auto_EDA]
- [Open notebook file location in GitHub repository][GitHub_auto_EDA]

[html_auto_EDA_code]: https://patrickwfitzgerald.github.io/portfolio/automated-EDA/automated_EDA_code.html
[html_auto_EDA_nocode]: https://patrickwfitzgerald.github.io/portfolio/automated-EDA/automated_EDA_nocode.html
[nbviewer_auto_EDA]: https://nbviewer.jupyter.org/github/patrickwfitzgerald/portfolio/blob/main/automated-EDA/automated_EDA.ipynb
[GitHub_auto_EDA]: https://github.com/patrickwfitzgerald/portfolio/blob/main/automated-EDA/automated_EDA.ipynb

[link_pprof]: https://pandas-profiling.github.io/pandas-profiling/docs/master/rtd/
[link_sv]: https://github.com/fbdesignpro/sweetviz
[link_dp]: https://sfu-db.github.io/dataprep/index.html

<br>

## [Ecological Footprint and Human Development Index][html_EF_code]
[View notebook with code][html_EF_code], [without code][html_EF_nocode]

Developed in September 2020

This notebook analyzes the ecological footprint of countries worldwide in relation to their score on
the Human Development Index. Data is imported through the Global Footprint Network API and merged
with other data sources for the analysis.

Alternative links:
- [Open notebook in nbviewer][nbviewer_EF]
- [Open notebook file location in GitHub repository][GitHub_EF]

[html_EF_code]: https://patrickwfitzgerald.github.io/portfolio/ecological-footprint-countries/ecological_footprint_code.html
[html_EF_nocode]: https://patrickwfitzgerald.github.io/portfolio/ecological-footprint-countries/ecological_footprint_nocode.html
[nbviewer_EF]: https://nbviewer.jupyter.org/github/patrickwfitzgerald/portfolio/blob/9a2b0eef31343ef17c012e8743d0dd14ff542906/ecological-footprint-countries/ecological_footprint.ipynb
[GitHub_EF]: https://github.com/patrickwfitzgerald/portfolio/blob/main/ecological-footprint-countries/ecological_footprint.ipynb

<br>

## [Exploratory Data Analysis in Python][html_EDA_tips_code]
[View notebook with code][html_EDA_tips_code], [without code][html_EDA_tips_nocode]

Developed in September 2020

This notebook illustrates the process of exploratory data analysis with Jupyter Notebook using Python.
A sample dataset from the seaborn package is analyzed using a systematic approach to visualize the
distribution of variables and associations between variables. This approach can be applied to any
other dataset containing similar types of variables.

Alternative links:
- [Open notebook in nbviewer][nbviewer_EDA_tips]
- [Open notebook file location in GitHub repository][GitHub_EDA_tips]

[html_EDA_tips_code]: https://patrickwfitzgerald.github.io/portfolio/exploratory-data-analysis-python/exploratory_data_analysis_in_python_code.html
[html_EDA_tips_nocode]: https://patrickwfitzgerald.github.io/portfolio/exploratory-data-analysis-python/exploratory_data_analysis_in_python_nocode.html
[nbviewer_EDA_tips]: https://nbviewer.jupyter.org/github/patrickwfitzgerald/portfolio/blob/main/exploratory-data-analysis-python/exploratory_data_analysis_in_python.ipynb
[GitHub_EDA_tips]: https://github.com/patrickwfitzgerald/portfolio/blob/main/exploratory-data-analysis-python/exploratory_data_analysis_in_python.ipynb

<br>
 
## License

### Code
The code in this repository is released under a [MIT license](LICENSE-CODE). Read more [here](https://choosealicense.com/licenses/mit/).

### Text
The text content contained in the Jupyter Notebook files is released under a [Creative Commons Attribution 4.0 International License](LICENSE-TEXT.txt). Read more at [Creative Commons][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png

