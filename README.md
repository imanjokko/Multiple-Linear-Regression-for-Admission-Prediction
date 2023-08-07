# Multiple-Linear-Regression-for-Admission-Prediction

## Case Profile
Duke University has a graduate school that is quite reputable and is rated moderately high on the list of many top schools. However, there is still room for improvement and enhancement in their competitive strategy.

![](https://github.com/imanjokko/Multiple-Linear-Regression-for-Admission-Prediction/blob/main/admissions.png)

One hallmark of the top schools is the high academic standards they set for applicants, giving the schools a head start on the right pick of students and already ensuring excellent academic output over other universities. This in turn leads to these schools having a better reputation, getting better research funding and donations for facilities, which just furthers their competitive edge over other schools even more.

I created a model to screen the applicants and determine their chance of admission based on their prior academic records, allowing the university to set itself apart by the type of students, quality of academic output, and as long as they uphold excellent teaching standards and provide the appropriate support on their part, they should see an upward trajectory in their competitive position moving forward.

## Methodology
A multiple linear regression model will be applied here because, not only is it useful for analyzing the impact of the independent variables on the dependent variable, it also shows the degree to which each variable affects the dependent variable. Using a multiple linear regression model also allows us to perform predictions on the outcome variable, giving the school a chance to streamline its application screening process and attain its competitive goals.

Multiple linear regression is a statistical technique employed to determine or estimate the relationship between a single quantitative response or dependent variable and multiple explanatory or independent variables. This was done using the Analysis ToolPak add-in in Microsoft Excel, the confidence level was set to 99%, and the model was set to show the residuals.

For this analysis, I began by creating a correlation matrix, which showed that the relationship between the explanatory variables and the response variable ranged from moderately strong to very strong. 

A residual plot was created using the residual table generated, and scatterplots were also created to show the relationship between the statistically significant independent variables and the dependent variable. Then all the visualizations were compiled into one dashboard to give the university a better overview of the analysis.

## Result
### Correlation analysis
![](https://github.com/imanjokko/Multiple-Linear-Regression-for-Admission-Prediction/blob/main/correlation%20matrix.png)
This coefficient matrix shows the correlation between the different variables. We will focus on the correlation between the Chance of Admission and the independent variables. The values range from 0.55 to 1, the higher values indicate a stronger correlation. The variables with the highest correlation are CGPA, GRE Score, and TOEFL Score, while Research has the lowest correlation.

### Regression analysis
![](https://github.com/imanjokko/Multiple-Linear-Regression-for-Admission-Prediction/blob/main/summary%20output.png)
In this analysis, GRE Score, TOEFL Score, LOR, CGPA, and Research are statistically significant predictors of Chance of Admission, while University Rating and SOP are not.

---

![](https://github.com/imanjokko/Multiple-Linear-Regression-for-Admission-Prediction/blob/main/Residual%20plot.jpeg)
In the residual plot, we see that the residuals are evenly and randomly distributed around the horizontal line at zero, there is no pattern shown, which can be interpreted to mean that the regression model is a good fit for the data.


## Conclusion
By applying this model, Duke University can improve its ability to predict the chance of admission for each applicant more accurately, which could help reduce the chances of admitting students who have a history of poor academic performance. By admitting students who have a solid academic track record and greater chances of succeeding in their education, the school will improve its retention rates and graduation rates, along with its reputation. All these will add up to give the university a competitive edge when it comes to attracting future applicants and securing funding, ultimately improving the school's position among the lists of top schools.

--- 

**[Read full documentation with results on Medium](https://medium.com/@imanjokko/linear-regression-for-admission-prediction-a-competitive-strategy-case-study-ca4d1e9ed071)**

[Click here to see each student's variables and their predicted chance of admission in Microsoft Excel.](https://1drv.ms/x/s!AktrPK7pllqDgSEpronHdqlMbpsV)

