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
  <meta name="dc.modified" content="2024-10-28T03:47:22+00:00" />
  <meta property="article:modified_time" content="2024-10-28T03:47:22+00:00" />
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
  <link rel="alternate" type="text/html" href="https://uiceds.github.io/project-team-all-right/v/efdcc5586388eb40feddbfc826f8f6cd3a79c05c/" />
  <meta name="manubot_html_url_versioned" content="https://uiceds.github.io/project-team-all-right/v/efdcc5586388eb40feddbfc826f8f6cd3a79c05c/" />
  <meta name="manubot_pdf_url_versioned" content="https://uiceds.github.io/project-team-all-right/v/efdcc5586388eb40feddbfc826f8f6cd3a79c05c/manuscript.pdf" />
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
([permalink](https://uiceds.github.io/project-team-all-right/v/efdcc5586388eb40feddbfc826f8f6cd3a79c05c/))
was automatically generated
from [uiceds/project-team-all-right@efdcc55](https://github.com/uiceds/project-team-all-right/tree/efdcc5586388eb40feddbfc826f8f6cd3a79c05c)
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
	Theoretical_Power_Curve (KWh): The theoretical power values that the turbine generates with that wind speed are given by the manufacturer.
	Wind Direction (°): The wind direction at the hub height of the turbine (wind turbines turn to this direction automatically.



## Research Objectives

__Objectives:__

Wind energy is a critical component in both large utility networks and small microgrids, providing numerous socio-economic benefits[1]. Two components specifically draw attention to wind power generation: wind speed and wind direction[2]. In this study, we focus on the potential impact on Wind Turbines and relationships between the main variables in a wind turbine SCADA dataset: LV ActivePower, Wind Speed, Wind Direction, and Theoretical Power. By understanding these relationships, we aim to gain the relationship between the natural wind conditions and the turbine's power output and identify potential optimization strategies for energy generation.

## Data Analysis

__Wind Speed vs. Power Generation Analysis:__

	Create scatter plots of Wind Speed vs. LV ActivePower to visualize the relationship between wind speed and power output.

	Use binning or smoothing techniques to examine how power generation responds to varying wind speeds, especially in low, 		moderate, and high wind conditions.
 !(https://github.com/uiceds/project-team-all-right/blob/main/LV%20Active%20Power%20vs.%20Wind%20Speed.png)
 









## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

