---
title: 'Analysis and Optimization of Wind Turbine Power Generation Using Supervisory Control and Data Acquisition (SCADA) Data: Exploring the Impact of Wind Speed and Direction on Performance'
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2024-12-07'
author-meta:
- Yuhao
- Trix Li
- YUlin Zhu
- Jingfei Qiao
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Analysis and Optimization of Wind Turbine Power Generation Using Supervisory Control and Data Acquisition (SCADA) Data: Exploring the Impact of Wind Speed and Direction on Performance" />
  <meta name="citation_title" content="Analysis and Optimization of Wind Turbine Power Generation Using Supervisory Control and Data Acquisition (SCADA) Data: Exploring the Impact of Wind Speed and Direction on Performance" />
  <meta property="og:title" content="Analysis and Optimization of Wind Turbine Power Generation Using Supervisory Control and Data Acquisition (SCADA) Data: Exploring the Impact of Wind Speed and Direction on Performance" />
  <meta property="twitter:title" content="Analysis and Optimization of Wind Turbine Power Generation Using Supervisory Control and Data Acquisition (SCADA) Data: Exploring the Impact of Wind Speed and Direction on Performance" />
  <meta name="dc.date" content="2024-12-07" />
  <meta name="citation_publication_date" content="2024-12-07" />
  <meta property="article:published_time" content="2024-12-07" />
  <meta name="dc.modified" content="2024-12-07T18:36:34+00:00" />
  <meta property="article:modified_time" content="2024-12-07T18:36:34+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Yuhao" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_orcid" content="0000-0000-0000-0000" />
  <meta name="twitter:creator" content="@johndoe" />
  <meta name="citation_author" content="Trix Li" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_institution" content="Department of Whatever, University of Something" />
  <meta name="citation_author_orcid" content="0000-0000-0000-0000" />
  <meta name="citation_author" content="YUlin Zhu" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_institution" content="Department of Whatever, University of Something" />
  <meta name="citation_author_orcid" content="0000-0000-0000-0000" />
  <meta name="citation_author" content="Jingfei Qiao" />
  <meta name="citation_author_institution" content="Department of Civil and Environmental Engineering, University of Whatever" />
  <meta name="citation_author_institution" content="Department of Whatever, University of Something" />
  <meta name="citation_author_orcid" content="0000-0000-0000-0000" />
  <link rel="canonical" href="https://uiceds.github.io/project-team-all-right/" />
  <meta property="og:url" content="https://uiceds.github.io/project-team-all-right/" />
  <meta property="twitter:url" content="https://uiceds.github.io/project-team-all-right/" />
  <meta name="citation_fulltext_html_url" content="https://uiceds.github.io/project-team-all-right/" />
  <meta name="citation_pdf_url" content="https://uiceds.github.io/project-team-all-right/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://uiceds.github.io/project-team-all-right/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://uiceds.github.io/project-team-all-right/v/7e6ac0dfc08551193013c704cde6139ee340e793/" />
  <meta name="manubot_html_url_versioned" content="https://uiceds.github.io/project-team-all-right/v/7e6ac0dfc08551193013c704cde6139ee340e793/" />
  <meta name="manubot_pdf_url_versioned" content="https://uiceds.github.io/project-team-all-right/v/7e6ac0dfc08551193013c704cde6139ee340e793/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://uiceds.github.io/project-team-all-right/v/7e6ac0dfc08551193013c704cde6139ee340e793/))
was automatically generated
from [uiceds/project-team-all-right@7e6ac0d](https://github.com/uiceds/project-team-all-right/tree/7e6ac0dfc08551193013c704cde6139ee340e793)
on December 7, 2024.
</em></small>



## Authors



+ **Yuhao**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0000-0000-0000](https://orcid.org/0000-0000-0000-0000)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [johndoe](https://github.com/johndoe)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [johndoe](https://twitter.com/johndoe)
    · ![Mastodon icon](images/mastodon.svg){.inline_icon width=16 height=16}
    [\@johndoe@mastodon.social](https://mastodon.social/@johndoe)
    <br>
  <small>
     Department of Something, University of Whatever
     · Funded by Grant XXXXXXXX
  </small>

+ **Trix Li**
  ^[✉](#correspondence)^<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0000-0000-0000](https://orcid.org/0000-0000-0000-0000)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [trixli](https://github.com/trixli)
    <br>
  <small>
     Department of Something, University of Whatever; Department of Whatever, University of Something
  </small>

+ **YUlin Zhu**
  ^[✉](#correspondence)^<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0000-0000-0000](https://orcid.org/0000-0000-0000-0000)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [yulinzhu](https://github.com/yulinzhu)
    <br>
  <small>
     Department of Something, University of Whatever; Department of Whatever, University of Something
  </small>

+ **Jingfei Qiao**
  ^[✉](#correspondence)^<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0000-0000-0000](https://orcid.org/0000-0000-0000-0000)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [jingfeiqiao](https://github.com/jingfeiqiao)
    <br>
  <small>
     Department of Civil and Environmental Engineering, University of Whatever; Department of Whatever, University of Something
  </small>


::: {#correspondence}
✉ — Correspondence possible via [GitHub Issues](https://github.com/uiceds/project-team-all-right/issues)
or email to
Trix Li \<zhouxin2@illinois.edu\>, 
YUlin Zhu \<yulinz7@illinois.edu\>, 
Jingfei Qiao \<jqiao3@illinois.edu\>.


:::


## Introduction

Wind energy is a critical component in both large utility networks and small microgrids, providing numerous socio-economic benefits[1]. In order to monitor and develop wind power better,  we should explore the relationship between wind energy potential and wind characteristics. Since wind power is proportional to the square of wind speed, the wind speed and directions results will significantly following wind power. So wind speed and wind directions specifically draw attention to the actual power output (LV Active Power) of a wind turbine[2]. In this study, we focus on the potential impact on Wind Turbines and relationships between the main variables in a wind turbine SCADA dataset: LV ActivePower, Wind Speed, Wind Direction, and Theoretical Power. By understanding these relationships, we aim to gain the relationship between the natural wind conditions and the turbine's power output, and the predicted power output and comparison will be given.

Some similar studies have been conducted before using analytical methods to improve the performance of wind turbine power generation, including using a multi-objective genetic algorithm and Reynolds-averaged-Navier-Stokes (RANS) equations to optimize the shroud and turbine shape as well as flange height [5], simulating and optimizing the power output of two straight-bladed vertical-axis wind turbines using computational fluid dynamics method and the Taguchi method [6], etc. Here, we focus on predicting and optimizing wind turbine energy output based on wind conditions with different data-driven models, which have not been extensively well-explored.

The dataset [4] we chose includes a record of wind turbines' operational data and the collection of wind conditions:

1. Date/Time (for 10 minute intervals).
2. LV ActivePower (kW): The power generated by the turbine for that moment.
3. Wind Speed (m/s): The wind speed at the hub height of the turbine (the wind speed that the turbine uses for electricity generation).
4. Theoretical_Power_Curve (KWh): The theoretical power values that the turbine generates with that wind speed which is given by the turbine manufacturer.
5. Wind Direction (°): The wind direction at the hub height of the turbine (wind turbines turn to this direction automatically [4].




## Exploratory Analysis

__Wind Speed vs. Power Generation Analysis:__

1. Create scatter plots of Wind Speed vs. LV ActivePower to visualize the relationship between wind speed and power output.
2. Use binning or smoothing techniques to examine how power generation responds to varying wind speeds, especially in low, 		moderate, and high wind conditions.

![image](https://github.com/uiceds/project-team-all-right/blob/main/LV%20Active%20Power%20vs.%20Wind%20Speed.png?raw=true){width=96%}
***Figure 1: The scatter plot of Wind Speed vs. LV Active Power, gives us the relationship of how power generation reacts as wind speed increases.***



From Figure 1, at low wind speeds (0 - 5 m/s), the LV Active Power output is minimal. The graph shows a steep increase in power output as the wind speed increases. This indicates that the turbine starts generating power only after reaching a certain threshold wind speed. From around 5 to 10 m/s, there is a strong positive correlation between wind speed and power output. The power output increases almost linearly with the increase in wind speed. This phase suggests that the turbine captures more wind energy as the wind speed increases, leading to higher power generation. At wind speeds above approximately 10 to 12 m/s, the power output reaches a plateau near the turbine’s maximum power capacity of around 3500 kW. Even with increasing wind speeds (beyond 12 m/s), the power output does not increase and remains stable.

__Wind Direction vs. Power Generation Analysis:__

1. Plot Wind Direction against LV ActivePower to investigate if specific wind directions are associated with higher power generation.
2. Explore whether there is an optimal wind direction for energy generation, which could indicate an alignment effect with turbine orientation.

![image](https://github.com/uiceds/project-team-all-right/blob/main/Power%20Generation%20vs.%20Wind%20Direction.png?raw=true){width=96%}
***Figure 2: The scatter plot of Wind Direction vs. LV Active Power gives us information about which wind direction the LV Active Power reaches its maximum generation power.***



![image](https://github.com/uiceds/project-team-all-right/blob/main/Polar%20Plot%20Wind%20Direction%20vs.%20Power%20Generation.png?raw=true){width=96%}
***Figure 3: The polar plot of wind direction vs. LV Active Power, gives us a more precise image from a spatial point of view.***



Based on the data analysis in Figure 2 and Figure 3, we can see there are specific ranges of wind directions where the LV Active Power reaches its maximum values, clustering at higher power output levels around 3500 kW. In the 0° to 60° range and 300° to 360° range, there is a dense concentration of points at higher power outputs, indicating that turbines generate more power when the wind comes from these directions. There is a clear pattern where certain wind directions correlate with higher and more consistent power outputs. These directions are likely more favorable for wind energy capture. For directions closer to 0°-60° and 300°-360°, the turbines consistently operate at higher power levels, suggesting these directions align well with the turbine’s optimal performance characteristics.


__Theoretical vs. Actual Power Comparison:__

1. Compare LV ActivePower with Theoretical Power using scatter plots and regression analysis to determine how closely the actual output follows the theoretical predictions.
2. Identify potential inefficiencies in the turbine operation that may contribute to gaps between actual and theoretical power.

![image](https://github.com/uiceds/project-team-all-right/blob/main/WechatIMG734.png?raw=true){width=96%}
***Figure 4: The scatter plot of Wind Speed vs. LV Active Power and Theoretical Power tells us how closely Active Power and Theoretical Power are related. The R2 value is 0.874 in this graph, which shows that the data are statistically quite similar.***



From Figure 4, we can see the theoretical curve serves as an upper bound, showing the maximum potential for power generation given the wind speed, and the actual data often falls below the theoretical curve, which is the real-world data. This could be due to real-world factors, like turbine efficiency, wind conditions, and operational factors. 


__Time Series and Seasonal Analysis:__

1. Analyze power output trends over time, considering seasonal or diurnal variations.
2. Investigate if certain times of day or seasons show different power generation patterns due to changes in wind conditions.

![image](https://github.com/uiceds/project-team-all-right/blob/main/1.png?raw=true){width=96%}
***Figure 5: The scatter plot of Time vs. Power (Active and Theoretical) tells us whether seasonality is a factor that affects power generation.*** 



There is no noticeable trend over time in Figure 5, indicating that power generation does not significantly vary with specific periods or seasons in the dataset. The consistent clustering of data points throughout the year implies that the main factors affecting power generation are not related to the time of the year, but more likely related to the real environmental conditions, like wind speed and wind direction. 


## Predictive Modeling

The predictive problem involves estimating the LV Active Power of a wind turbine based on features of Wind Speed, Wind Direction, and the Theoretical Power Curve. This study is motivated by optimizing turbine efficiency and understanding the differences between theoretical and actual power output. Four models were implemented in this study: Linear Regression, Decision Tree, K-means, and Random Forest. Each model was evaluated for its predictive performance and ability to capture the relationships between the variables.

For data processing and implementation in the models, the dataset was divided into an 80% training set and a 20% testing set for all four models, ensuring that the models were trained on one portion of the data and evaluated on a separate portion of data to assess their generalization performance. To ensure uniform scaling and improve algorithm performance, the target variable, LV Active Power, was standardized to have a mean of 0 and a standard deviation of 1. This preprocessing step was crucial for models like Linear Regression, which are sensitive to the scale of the input data. Additionally, polynomial features were introduced for Linear Regression and K-means models to capture the non-linear relationship between wind speed and active power output. This step was unnecessary for Decision Tree and Random Forest models, as these algorithms inherently handle non-linear relationships and interactions between features and the target variable.


__Modeling Results__

__K-means:__
K-means clustering was applied to group the dataset into k=3 clusters based on the engineered features. The clustering labels were added to the dataset as a categorical variable, enabling the regression model to account for inner-cluster variations.

![image](https://github.com/uiceds/project-team-all-right/blob/main/128356922358373cbd45ea093da643e9.PNG?raw=true){width=93%}
***Figure 6: Standardized scatter plot of Actual vs. Predicted LV Active Power for K-means model. The red line in the graph is the perfect prediction line for better comparison.***

Predictive Performance(K-means):

MSE (Mean Squared Error): 0.0952

RMSE (Root Mean Squared Error): 0.309

From Figure 6 analysis, the K-means model achieved a Mean Squared Error (MSE) of 0.0952 and a Root Mean Squared Error (RMSE) of 0.309, indicating a relatively low error in predictions. The scatter plot of actual versus predicted LV Active Power reveals a generally strong linear relationship, demonstrating that the model effectively captures the underlying patterns in the data.


__Decision Tree:__
The decision Tree model was chosen because it can handle non-linear relationships and interactions between features. To balance complexity and overfitting, the model was configured with a maximum depth of 10.

![image](https://github.com/uiceds/project-team-all-right/blob/main/d587046465cb19908d8d8d16a01fdcc9.PNG?raw=true){width=93%}
***Figure 7: Standardized scatter plot of Actual vs. Predicted LV Active Power for Decision Tree model.***

Predictive Performance(Decision Tree):

Mean Squared Error (MSE): 0.174

Root Mean Squared Error (RMSE): 0.418

The Decision Tree model achieved a Mean Squared Error (MSE) of 0.174 and a Root Mean Squared Error (RMSE) of 0.418, reflecting moderate predictive accuracy. The scatter plot of actual versus predicted values indicates a general linear trend, suggesting that the model captures the overall relationship between the variables. However, in Figure 7, deviations are more pronounced at the lower and higher ends of LV Active Power, highlighting areas where the model’s predictions are less accurate.

__Linear Regression:__
A multiple linear regression model was used because it is a straightforward method for analyzing relationships between multiple predictors and the target variable. Polynomial terms allow the model to account for non-linear relationships in the data.

![image](https://github.com/uiceds/project-team-all-right/blob/main/%201%20LR.png?raw=true){width=93%}
***Figure 8: Standardized scatter plot of Actual vs. Predicted LV Active Power for Linear Regression model.***

Predictive Performance(Linear Regression): 

Mean Squared Error (MSE): 0.0963

Root Mean Squared Error (RMSE): 0.310

The Linear Regression model achieved a Mean Squared Error (MSE) of 0.0963 and a Root Mean Squared Error (RMSE) of 0.310, indicating good predictive performance. In Figure 8, the actual versus predicted values scatter plot reveals a strong linear trend. This demonstrates that the model effectively captures the primary relationship between the input features and the target variable, LV Active Power. This suggests that the model is well-suited for representing the overall patterns in the data, although it may have limitations in handling more complex, non-linear interactions.


__Random Forest:__
A Random Forest model was selected for its ability to handle non-linear relationships and interactions among features. The model was configured with 100 estimators and a random state of 42 to ensure reproducibility and performance stability.

![image](https://github.com/uiceds/project-team-all-right/blob/main/c7cc145492bd32419b34d6736d0adc92.PNG?raw=true){width=93%}
***Figure 9: Standardized scatter plot of Actual vs. Predicted LV Active Power for Random Forest model.***

Predictive Performance(Random Forest):

Mean Squared Error (MSE): 0.0948

Root Mean Squared Error (RMSE): 0.308

The Random Forest model achieved a Mean Squared Error (MSE) of 0.0948 and a Root Mean Squared Error (RMSE) of 0.308, reflecting high predictive accuracy. In Figure 9, the scatter plot of actual versus predicted values illustrates a strong linear relationship, indicating that the model effectively captures variations in LV Active Power. The model performs exceptionally well for middle-range values, demonstrating its ability to generalize across the dataset, but some deviations are observed at the extreme ends of the power output range.


## Model Comparisons

![image](https://github.com/uiceds/project-team-all-right/blob/main/Comparison%20chart.png?raw=true){width=93%}
***Figure 10: Comparison Chart to compare the four models based on their predictive performance, strengths, and weaknesses.***

Based on the comparison shown in Figure 10, Random Forest emerged as the most effective among the four models, achieving the lowest error metrics and demonstrating the best ability to generalize across the dataset. Its ensemble structure effectively captured complex, non-linear relationships, making it the most accurate and reliable model for predicting LV Active Power, despite minor deviations at extreme values. K-Means Enhanced Linear Regression provided notable improvements over standard Linear Regression by incorporating cluster-specific trends, though its dependency on clustering quality introduced some variability. Linear Regression, while simple and interpretable, struggled with complex interactions, limiting its flexibility. The Decision Tree model captured non-linear relationships but was less accurate and tended to overfit. 

Overall, Random Forest is recommended as the optimal model due to its stability and predictive accuracy. Linear Regression and K-means are interpretable alternatives for simpler and more straightforward tasks.


## Discussion

The research question aimed to determine whether wind speed and wind direction could serve as reliable predictors for accurately estimating LV Active Power and how the predicted power output compares to the theoretical power curve. Based on the data analysis and predictive modeling, this question was effectively answered.

Wind speed emerged as the most critical predictor, showing a strong positive correlation with LV Active Power across all models. In Linear Regression, the coefficient for wind speed was the largest among all predictors, underscoring its dominant role in power generation. Similarly, feature importance analysis in Random Forest and Decision Tree models confirmed wind speed as the most influential variable, further validating its significance. The addition of polynomial terms in Linear Regression improved model accuracy, demonstrating the non-linear relationship between wind speed and power output, consistent with the theoretical cubic scaling of power generation.

Wind direction, while less impactful than wind speed, contributed meaningful insights. Feature importance rankings from Random Forest and Decision Tree models consistently placed wind direction behind wind speed. The analysis revealed that turbines performed optimally when aligned within specific wind direction ranges (e.g., 0°–60° and 300°–360°), indicating the importance of turbine orientation in enhancing efficiency.

These findings supported the hypothesis that wind speed and wind direction are significant predictors of LV Active Power. While the models effectively captured variations in power output, some differences between predicted and theoretical power were observed, likely due to operational inefficiencies and real-world conditions not accounted for in the theoretical model.

To​​ further advance this research, several steps can be taken to build on the current findings. Incorporating additional variables such as temperature, air pressure, turbulence intensity, and turbine operational data could provide a more comprehensive understanding of real-world inefficiencies and improve predictive accuracy.  Implementing real-time data collection would allow for analyzing temporal variations in power output, offering valuable insights into how these variations affect turbine performance. Additionally, operational optimization strategies, such as adjusting turbine orientation or refining maintenance practices, could help minimize discrepancies between actual and theoretical power output, enhancing overall turbine efficiency. While this research successfully addressed the initial question and hypothesis, these steps represent valuable opportunities for further exploration and improvement.











## References {.page_break_before}
1. Yatiyana, E., Rajakaruna, S., & Ghosh, A. (2017, November). Wind speed and direction forecasting for wind power generation using ARIMA model. In 2017 Australasian universities power engineering conference (AUPEC) (pp. 1-6). IEEE.
2. Wang, Z., & Liu, W. (2021). Wind energy potential assessment based on wind speed, its direction and power data. Scientific reports, 11(1), 16879.
3. Daut, I. D. I., Irwanto, M. I. M., Suwarno, S., Irwan, Y. I. Y., Gomesh, N. G. N., & Ahmad, N. A. N. (2011). Potential of wind speed for wind power generation in Perlis, Northern Malaysia. TELKOMNIKA (Telecommunication Computing Electronics and Control), 9(3), 575-582.
4. Erisen, B. (2019, March 7). Wind Turbine Scada dataset. Kaggle. https://www.kaggle.com/datasets/berkerisen/wind-turbine-scada-dataset/data
5. Khamlaj, T. A., & Rumpfkeil, M. P. (2018). Analysis and optimization of ducted wind turbines. Energy, 162, 1234–1252. https://doi.org/10.1016/j.energy.2018.08.106
6. Chen, W.-H., Chen, C.-Y., Huang, C.-Y., & Hwang, C.-J. (2017). Power output analysis and optimization of two straight-bladed vertical-axis wind turbines. Applied Energy, 185, 223–232. https://doi.org/10.1016/j.apenergy.2016.10.076 


<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

