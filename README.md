Download Link: https://assignmentchef.com/product/solved-stat210-410-assessment6-kernel-smoothers
<br>
Modelling rainfall is important for prediction and simulation purposes in many areas of planning, agriculture, forestry, meteorology and hydrology. In this assignment, we’ll fit various parametric and nonparametric models to the annual rainfall in Armidale region (the home of UNE).

The data in the file ArmidaleRainfall.txt comes from the Australian Bureau of Meteorology and contains the annual rainfall (in mm) recorded at six weather stations in Armidale, Uralla and Guyra from 1998 until 2020.

Our research question is: <em>Is there evidence to suggest that the annual rainfall is changing over time?</em>

<ul>

 <li>Using the poly() function in R<a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a>, fit a polynomial regression model to the rainfall as a function of year. Explain how you decided on the order for the polynomial.<a href="#_ftn2" name="_ftnref2"><sup>[2]</sup></a> Plot the data, the fitted curve and the 95% confidence bands. Produce and interpret relevant diagnostics, relating your interpretation to the <em>context </em>of the analysis. <em>[25 marks]</em></li>

 <li>In this topic you have explored kernel smoothers, splines and local polynomials. Applythese methods to the data. Fit a smooth to the rainfall as a function of year. You must justify the amount of smoothing that you think appropriate and compare the fits from the different methods. Comment on the features of the fitted curves. <em>[55 marks]</em></li>

 <li>Summarise your results, relating them to the <em>context of the question</em>, and include a comparison of the parametric and nonparametric approaches that you have used, discussing the advantages and/or disadvantages of the various approaches. <em>[15 marks]</em></li>

</ul>

1

<a href="#_ftnref1" name="_ftn1">[1]</a> You have not used this function in the unit so far. You will need to investigate its use.

<a href="#_ftnref2" name="_ftn2">[2]</a> Do not fit a model of order greater than 10.