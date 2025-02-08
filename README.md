# Missing_data

This code script was written and submitted as Missing data assignment in  Data science for Epidemiology course. The following tasks were completed in the assignment:


## 1. Data Exploration 

The [can_path_student_dataset](https://canpath.ca/student-dataset/) was used in this assignment to explore the dataset to identify the extent, patterns, and potential reasons for missing data. To reduce computational demands running the entire dataset, 15 columns with percentage of missing data less than 20%. Methods such as [little_mcar](https://search.r-project.org/CRAN/refmans/misty/html/na.test.html) and regression model(using "NA") was performed on the datasets to 
understand the nature of missingness. Even though this methods were suggested, it was not used as means of proving type of missingness in the data. Results were interpreted as an assumption.
Findings were summarize  using tables, charts, and heatmaps to visualize missingness. The project used the [naniar](https://cran.r-project.org/web/packages/naniar/vignettes/getting-started-w-naniar.html) and [visdat](https://cran.r-project.org/web/packages/visdat/vignettes/using_visdat.html) special packages for missing data task in R

## 2. Apply Imputation Methods

Mean imputation,  Multiple Imputation by Chained Equations (MICE) and  K-Nearest Neighbors (KNN) imputation were used to fill the missing data in the  [can_path_student_dataset](https://canpath.ca/student-dataset/).
The imputation process for each method/imputation approach has been documented in the attached files. 

## 3. Evaluation of Imputation Methods

The performance of each method was analyzed by comparing changes in key summary statistics and visualizing comparisons of distributions before and after imputation using boxplot and density charts. 
Regression model was also developed to see how the various imputation  methods affects the relationship between quantity of fruits consumed and physical activity.

 A table was presented at the end of the rmarkdown file showing how the various methods affects the sample mean and regression model. 
 
# Files Attached to Repository:

The [Missing_Data_Imputation.Rmd](https://github.com/Bernard-AI4PH/Missing_data/blob/main/Bernard_Asante_CHEP_898_Missing_Data_Imputation.Rmd) file contains the script for the assignment.

The [Missing_Data_Imputation.html](https://github.com/Bernard-AI4PH/Missing_data/blob/main/Bernard_Asante_CHEP_898_Missing_Data_Imputation.html) file is the knitted .rmd file which can be downloaded and opened in a web browser
 
 

