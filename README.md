# Anti-Cancer Drug Study

## Background:

Pymaceuticals Inc., is a burgeoning fictional pharmaceutical company. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

I have analyzed data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 

This demo creates all of the tables and figures needed for the technical report of the study and includes a top-level summary of the study results.

## Results:
### Observations and Inferences:
TODO: Add Observations and Inferences.

### Tables and Figures:
TODO: Add Tables and Figures.

## Methods: 

1. Data was assessed for duplicate mice and all data associated with duplicate mouse IDs was removed.

2. A summary statistics table was created consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

3.  A bar plot was created (using both Pandas's DataFrame.plot() and Matplotlib's pyplot) showing the number of mice per time point for each treatment regimen throughout the course of the study.
NOTE: These plots look identical, as they merely demonstrate different methods.

4. A pie plot was creates (using both Pandas's DataFrame.plot() and Matplotlib's pyplot) that shows the distribution of female or male mice in the study.
NOTE: These plots look identical, as they merely highlight different methods.

5. Final tumor volume was calculated for each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Quartiles and the IQR (Interquartile Range) were calculated and used to quantitatively determine if there were any potential outliers across all four treatment regimens.

6. Using Matplotlib, a box and whisker plot was generated for the final tumor volume of all four treatment regimens. Potential outliers were highlighted in the plot by changing their color and style.

7.A line plot of time point versus tumor volume was generated for a single mouse treated with Capomulin.

8. A scatter plot was created showing mouse weight versus average tumor volume for the Capomulin treatment regimen. The correlation coefficient and a linear regression model were calculated between mouse weight and average tumor volume for the Capomulin treatment. The linear regression model was plotteed on top of the scatter plot.

9.  Observations and inferences were determined by looking at all generated figures and tables.
