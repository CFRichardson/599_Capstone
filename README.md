# Abstract
---------------------------
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;It has been well-documented that there are racial disparities in policing in cities across the United States.  In 2018, the Racial and Identity Profiling Act of 2015 was implemented in the city of San Diego to help understand and alleviate such disparities.  We analyze and model such data to assess if San Diego Police Department's policing habits have changed since the implementation and if committed crimes are in response to temperature.  Various Decision Tree-based models, such as Bagged Trees and Adaptive Boosting, were explored.  Sadly our analysis showed that racial profiling persists throughout the city.  African Americans, in particular, are pulled over roughly 3.23x more than their White and Hispanic counterparts.  In contrast, Asians are pulled over 1/4 less the time in comparison to their White and Hispanic counterparts.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dejectedly utilized models underperformed, showing that the state of the dataset was transformed to be utilized and demonstrated little to no patterns other than the obvious and that weather in San Diego is not a good predictor of crime reported in the RIPA dataset.  The obvious being, as the phrase goes, you do the crime, you do time, or at least you get cited.



# Table Of Contents
--------------
- [Business Background](#background)
- [Problem Statement](#problem-statement)
- [Business Background](#business-background)
- [Business Questions](#business-questions)
- [Scope of Analysis](#scope-of-analysis)
- [Approach](#approach)
- [Limitations](#limitations)
- [Solution Details](#solution-details)
- [Concluding Summary](#concluding-summary)
- [Call to Action/Contributors](#call-to-action/contributors)
- [Link to Data Sets](#link-to-data-sets)


# Business Background
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In recent years, traffic stops have emerged as a key factor driving some of these inequities and an area of potential reform. Additionally, this study addresses racial profiling when the traffic stop outcome is a citation. We have used this article to figure out how much of this disparity is because of discrimination and how much is due to other factors, but untangling these other factors is challenging. The data was collected by San Diego police agency under a 2015 state law that mandates efforts to eliminate racial profiling by law enforcement.


# Problem Statement
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As America becomes even more ethnically diversified than it already is, it is more crucial than ever that we understand police patterns of behavior to create programs and policies to construct harmonious coexistence. By utilizing police RIPA reports, alongside weather, plus demographic and socio-economics of the area of the stop, we may be able to predict the reason for stop and predict whether those stops are based on races and possible outcomes.

# Summary of the Findings
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Based on analysis, Black drivers are pulled over roughly 3.23x more than their White and Hispanic counterparts.  In contrast, Asians are pulled over 1/4 less the time in comparison to their White and Hispanic counterparts.  

# Business Questions
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Traffic stops are the most common interaction between police and the public, accounting for roughly 40% of all contacts. In conducting their jobs, police officers exercise a great deal of discretion when stopping, arresting, and searching individuals. An officer can use a person's race as one of several factors used to identify a suspect, but race cannot be the sole reason for an officer's actions or suspicion of criminal activity.

# Scope of Analysis
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The scope of analysis includes analyzing San Diego police stops based on races and whether those led to citation or not. We have used Weather data to analyze further to know if those stops are related to weather or not. We have used variables like date_stop, time_stop, address_city, address_block, beat, beat_name, gender_nonconforming, gender_nc & gend from San Diego police stop data for the year 2018-2021.

# Approach
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;We have used visual techniques to discover trends, patterns & to check assumptions with the help of statistical summary and graphical representations using RIPA dataset from San Diego police stop. We have used a data wrangling process of removing errors and combining complex data sets to make them more accessible and easier to analyze. Further we ran multiple algorithms like Decision Tree, Bagging, AdaBoost & K-Nearest Neighbor.

# Limitations
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;These RIPA numbers are a starting point for understanding racial disparities in traffic stops, but they do not, per se, provide strong evidence of racially disparate treatment. In particular, per-capita stop rates do not account for possible race-specific differences in driving behavior, including amount of time spent on the road and adherence to traffic laws. Moreover, drivers may not live in the jurisdictions where they were stopped, further complicating the interpretation of population benchmarks. Quantifying potential bias in stop decisions is a statistically challenging problem, in large part because one cannot readily measure the racial distribution of those who actually violated traffic laws because the data contain information only on those stopped for such offenses.

# Solution details
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;With further refinement of the utilized data and modeling techniques, it is possible to identify which police beats, otherwise known as San Diego Police Departments, are curbing profiling habits and which police beats are trending toward profiling-related issues

# Concluding summary
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In conclusion, RIPA data is a starting point for understanding racial disparities in traffic stops, but they do not, per se, provide strong evidence of racially disparate treatment.  With that said, the data shows that African Americans/Blacks are pulled over disproportionately more than their racial counterparts, and Asian Americans are pulled over disproportionately less.

# Call to action (CTA)/Contributers:
Please reach out to us for further details:

* Richardson, Christopher
    * :email: (christopherr@sandiego.edu)
* Sing, Ashutosh
    * :email: (asingh@sandiego.edu)

# Link to Data Sets
Data Link via Google drive<br>
https://drive.google.com/drive/folders/1bsstUmLAC_geoznV8jxQTEC87hw_gPsD?usp=share_link <br><br>
Please contact christopherr@sandiego.edu if you encounter any difficulties accessing the data.  Thank you.
