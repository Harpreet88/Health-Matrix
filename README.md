**HealthMatrix- Predicting Weight Change Using Diet Analysis**


analyzing various factors that influence weight change using a multilinear regression model. 
Our dataset contains information relating to diet, physical activity and various lifestyle habits that are known to influence weight fluctuations.
Through our analysis, we hope to identify what factors should be limited to prevent weight gain, and what factors should be encouraged to promote weight loss.
Through this analysis, we hope to provide insight and various suggestions as to how to properly manage weight from both individual and public health perspectives. 
Obesity has become an extremely important topic in recent years, causing more health problems than we have ever seen before1. Our main objective will be to predict weight changes based on these lifestyle and
dietary variables. Through the use of our multilinear regression model, we will identify the significant variables that influence weight change, eliminate insignificant variables, resulting in a consistent and 
reliable framework to determine weight change. Other studies in this area identify lifestyle habits such as caloric intake, physical activity and quantity of sleep as important factors2. We expect our analysis to 
suggest that a caloric deficit contributes to weight gain, and vice versa, as well as higher physical activity level, quality sleep, and lower stress levels to contribute positively to weight loss. Duration (in weeks) 
will also be an important factor, but could prove to be insignificant depending on how well each participant scores in the other areas.



Findings show the large role stress levels and sleep quality play on weight change, particularly
how poor sleep and elevated stress levels have a more pronounced impact. Participants from this
study tended to experience more weight loss when connected with poor sleep. While weight loss tended 
to display a wider range for stress levels, we observed much consistent higher weight loss for the 
highest stress levels. These results demonstrate how both physical and mental health causes difficulties when it comes to weight management.
Although our combined model provides the most comprehensive result, it still poses challenges such as with multicollinearity as well as unmet regression assumptions causing limited explanation when it comes to our quantitative predictors. Regardless, after refining the model we should have statistical significance. Despite the fact that some assumptions were not met, and could not be corrected with transformations, 






 equation of: 
 
 
 
 XWeight.Change..lbs. = 0.21766 + 0.18485XSleep.QualityFair − 1.59689XSleep.QualityGood +1.24320XSleep.QualityPoor + 1.21315Xlog(Duration..weeks.) + 0.54944XStress.Level2 −2.44803XStress.Level3 − 1.93746XStress.Level4 − 4.19952XStress.Level5 −0.32160XStress.Level6 − 2.49840XStress.Level7 + 13.14533XStress.Level8 −0.12103XStress.Level9 − 0.06075(XSleep.QualityFair Xlog(Duration..weeks.)) +0.55598(XSleep.QualityGood Xlog(Duration..weeks.)) − 5.29987(XSleep.QualityPoor Xlog(Duration..weeks.)) −0.46614(Xlog(Duration..weeks.)XStress.Level2 ) + 1.45515(Xlog(Duration..weeks.)XStress.Level3 ) +0.89513(Xlog(Duration..weeks.)XStress.Level4 ) + 2.98467(Xlog(Duration..weeks.)XStress.Level5 ) −0.02623(Xlog(Duration..weeks.)XStress.Level6 ) + 1.23485(Xlog(Duration..weeks.)XStress.Level7 ) −12.05261(Xlog(Duration..weeks.)XStress.Level8 ) − 6.05003(Xlog(Duration..weeks.)XStress.Level9 )
 
 
 
 
 This project helped demonstrate the difficulties that may arise when limiting your modeling methods to one variable as opposed to incorporating them all, as seen with the need to halt our modelling for the quantitative model. It also helped uncover the critical factors that not only influence weight change but also reveal how complex human health and behavior are. To build off this analysis in the future, more indepth analyses could be held by integrating additional datasets; for example, adding both longitudinal and temporal studies. Additionally, further investigation into how sleep and stress mitigation could be applied to public health strategies.
