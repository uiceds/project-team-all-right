---
title: 'Analysis and Optimization of Wind Turbine Power Generation Using Supervisory Control and Data Acquisition(SCADA) Data: Exploring the Impact of Wind Speed and Direction on Performance'
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2024-10-28'
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
  <meta name="dc.title" content="Analysis and Optimization of Wind Turbine Power Generation Using Supervisory Control and Data Acquisition(SCADA) Data: Exploring the Impact of Wind Speed and Direction on Performance" />
  <meta name="citation_title" content="Analysis and Optimization of Wind Turbine Power Generation Using Supervisory Control and Data Acquisition(SCADA) Data: Exploring the Impact of Wind Speed and Direction on Performance" />
  <meta property="og:title" content="Analysis and Optimization of Wind Turbine Power Generation Using Supervisory Control and Data Acquisition(SCADA) Data: Exploring the Impact of Wind Speed and Direction on Performance" />
  <meta property="twitter:title" content="Analysis and Optimization of Wind Turbine Power Generation Using Supervisory Control and Data Acquisition(SCADA) Data: Exploring the Impact of Wind Speed and Direction on Performance" />
  <meta name="dc.date" content="2024-10-28" />
  <meta name="citation_publication_date" content="2024-10-28" />
  <meta property="article:published_time" content="2024-10-28" />
  <meta name="dc.modified" content="2024-10-28T04:30:30+00:00" />
  <meta property="article:modified_time" content="2024-10-28T04:30:30+00:00" />
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
  <link rel="alternate" type="text/html" href="https://uiceds.github.io/project-team-all-right/v/c77465238fae25c96693fa9bb5628eb2563ccf94/" />
  <meta name="manubot_html_url_versioned" content="https://uiceds.github.io/project-team-all-right/v/c77465238fae25c96693fa9bb5628eb2563ccf94/" />
  <meta name="manubot_pdf_url_versioned" content="https://uiceds.github.io/project-team-all-right/v/c77465238fae25c96693fa9bb5628eb2563ccf94/manuscript.pdf" />
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
([permalink](https://uiceds.github.io/project-team-all-right/v/c77465238fae25c96693fa9bb5628eb2563ccf94/))
was automatically generated
from [uiceds/project-team-all-right@c774652](https://github.com/uiceds/project-team-all-right/tree/c77465238fae25c96693fa9bb5628eb2563ccf94)
on October 28, 2024.
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


## Description of the Dataset
__Source of Data:__

The data originates from Kaggle, specifically from the dataset titled “Wind Turbine SCADA Dataset” uploaded by the user Berker İsen. This dataset is publicly accessible. The dataset includes SCADA (Supervisory Control and Data Acquisition) data collected from wind turbines, which is commonly used for monitoring and managing wind turbine operations.

__Data Generation:__

In Wind Turbines, SCADA systems measure and save data like wind speed, wind direction, generated power, etc., for 10-minute intervals. This file was taken from a wind turbine's SCADA system that is working and generating power in Turkey.

__Format and Contents:__

The data is in a CSV file, making it accessible and easy to manipulate using standard data analysis tools. Key columns in the dataset include:
	Date/Time (for 10-minute intervals).
	LV ActivePower (kW): The power the turbine generates for that moment.
	Wind Speed (m/s): The wind speed at the turbine's hub height (the wind speed that the turbine uses for electricity generation).
	Theoretical_Power_Curve (KWh): The theoretical power values that the turbine generates with that wind speed are given by the 		manufacturer.
	Wind Direction (°): The wind direction at the hub height of the turbine (wind turbines turn to this direction automatically.



## Research Objectives

__Objectives:__

Wind energy is a critical component in both large utility networks and small microgrids, providing numerous socio-economic benefits[1]. Two components specifically draw attention to wind power generation: wind speed and wind direction[2]. In this study, we focus on the potential impact on Wind Turbines and relationships between the main variables in a wind turbine SCADA dataset: LV ActivePower, Wind Speed, Wind Direction, and Theoretical Power. By understanding these relationships, we aim to gain the relationship between the natural wind conditions and the turbine's power output and identify potential optimization strategies for energy generation.

## Data Analysis

__Wind Speed vs. Power Generation Analysis:__

1. Create scatter plots of Wind Speed vs. LV ActivePower to visualize the relationship between wind speed and power output.
2. Use binning or smoothing techniques to examine how power generation responds to varying wind speeds, especially in low, 		moderate, and high wind conditions.

![image](https://github.com/uiceds/project-team-all-right/blob/main/LV%20Active%20Power%20vs.%20Wind%20Speed.png?raw=true)
***The scatter plot of Wind Speed vs. LV Active Power, gives us the relationship of how power generation reacts as wind speed increases.***



At low wind speeds (0 - 5 m/s), the LV Active Power output is minimal. The graph shows a steep increase in power output as the wind speed increases. This indicates that the turbine starts generating power only after reaching a certain threshold wind speed. From around 5 to 10 m/s, there is a strong positive correlation between wind speed and power output. The power output increases almost linearly with the increase in wind speed. This phase suggests that the turbine captures more wind energy as the wind speed increases, leading to higher power generation. At wind speeds above approximately 10 to 12 m/s, the power output reaches a plateau near the turbine’s maximum power capacity of around 3500 kW. Even with increasing wind speeds (beyond 12 m/s), the power output does not increase and remains stable.

__Wind Direction vs. Power Generation Analysis:__

1. Plot Wind Direction against LV ActivePower to investigate if specific wind directions are associated with higher power generation.
2. Explore whether there is an optimal wind direction for energy generation, which could indicate an alignment effect with turbine orientation.

![image](https://github.com/uiceds/project-team-all-right/blob/main/Power%20Generation%20vs.%20Wind%20Direction.png?raw=true)
***The scatter plot of Wind Direction vs. LV Active Power gives us information about which wind direction the LV Active Power reaches its maximum generation power.***



![image](https://github.com/uiceds/project-team-all-right/blob/main/Polar%20Plot%20Wind%20Direction%20vs.%20Power%20Generation.png?raw=true)
***The polar plot of wind direction vs. LV Active Power, gives us a more precise image from a spatial point of view.***



From the graphs, we can see there are specific ranges of wind directions where the LV Active Power reaches its maximum values, clustering at higher power output levels around 3500 kW. In the 0° to 60° range and 300° to 360° range, there is a dense concentration of points at higher power outputs, indicating that turbines generate more power when the wind comes from these directions. There is a clear pattern where specific wind directions correlate with higher and more consistent power outputs. These directions are likely more favorable for wind energy capture. For directions closer to 0°-60° and 300°-360°, the turbines consistently operate at higher power levels, suggesting these directions align well with the turbine’s optimal performance characteristics.

__Theoretical vs. Actual Power Comparison:__

1. Compare LV ActivePower with Theoretical Power using scatter plots and regression analysis to determine how closely the actual output follows the theoretical predictions.
2. Identify potential inefficiencies in the turbine operation that may contribute to gaps between actual and theoretical power.

![image](https://github.com/uiceds/project-team-all-right/blob/main/WechatIMG734.png?raw=true)
***The scatter plot of Wind Speed vs. LV Active Power and Theoretical Power tells us how closely Active Power and Theoretical Power are related. The R2 value is 0.874 in this graph, which shows that the data are statistically quite similar.***



From the graph, we can see the theoretical curve serves as an upper bound, showing the maximum potential for power generation given the wind speed. The actual data often falls below the theoretical curve, which is the real-world data. This could be due to real-world factors, like turbine efficiency, wind conditions, and operational factors. 

__Time Series and Seasonal Analysis:__

1. Analyze power output trends over time, considering seasonal or diurnal variations.
2. Investigate if certain times of day or seasons show different power generation patterns due to changes in wind conditions.

![image](https://github.com/uiceds/project-team-all-right/blob/main/1.png?raw=true)
***The scatter plot of Time vs. Power (Active and Theoretical) tells us whether seasonality is a factor that affects power generation.*** 



There is no noticeable trend over time, indicating that power generation does not significantly vary with specific periods or seasons in the dataset. The consistent clustering of data points throughout the year implies that the main factors affecting power generation are not related to the time of the year but are more likely related to real environmental conditions, like wind speed and wind direction. 

## Predictive Modeling

Wind Speed shows the strongest correlation with LV Active Power, making it the most influential factor in determining power output. Wind Direction is the next significant factor impacting LV Active Power, indicating its influence on output variability. Based on these findings, developing a predictive model for power output is highly feasible and is expected to yield effective results.

In terms of predictive variables, Wind Speed emerges as a primary predictor due to its strong correlation with LV Active Power, positioning it as a critical driver of power output. Wind Direction, as a secondary predictor, also shows a notable correlation, suggesting it contributes meaningfully to variations in power output.


## Expected Outcomes and Rationale

The analysis is expected to reveal the impact of wind speed and direction on power generation efficiency. We anticipate that higher wind speeds will generally correlate with increased power output up to a certain threshold[3]. Understanding discrepancies between actual and theoretical power could highlight areas where turbine efficiency can be improved. This analysis could help in optimizing turbine operation, leading to better alignment with wind conditions and potentially increasing overall power output.





## References {.page_break_before}
1. Yatiyana, E., Rajakaruna, S., & Ghosh, A. (2017, November). Wind speed and direction forecasting for wind power generation using ARIMA model. In 2017 Australasian universities power engineering conference (AUPEC) (pp. 1-6). IEEE.
2. Wang, Z., & Liu, W. (2021). Wind energy potential assessment based on wind speed, its direction and power data. Scientific reports, 11(1), 16879.
3. Daut, I. D. I., Irwanto, M. I. M., Suwarno, S., Irwan, Y. I. Y., Gomesh, N. G. N., & Ahmad, N. A. N. (2011). Potential of wind speed for wind power generation in Perlis, Northern Malaysia. TELKOMNIKA (Telecommunication Computing Electronics and Control), 9(3), 575-582.

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

