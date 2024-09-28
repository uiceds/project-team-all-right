---
title: Wastewater Treatment Plant Energy Consumption Analysis
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2024-09-28'
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
  <meta name="dc.title" content="Wastewater Treatment Plant Energy Consumption Analysis" />
  <meta name="citation_title" content="Wastewater Treatment Plant Energy Consumption Analysis" />
  <meta property="og:title" content="Wastewater Treatment Plant Energy Consumption Analysis" />
  <meta property="twitter:title" content="Wastewater Treatment Plant Energy Consumption Analysis" />
  <meta name="dc.date" content="2024-09-28" />
  <meta name="citation_publication_date" content="2024-09-28" />
  <meta property="article:published_time" content="2024-09-28" />
  <meta name="dc.modified" content="2024-09-28T19:45:41+00:00" />
  <meta property="article:modified_time" content="2024-09-28T19:45:41+00:00" />
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
  <link rel="alternate" type="text/html" href="https://uiceds.github.io/project-team-all-right/v/c6472156ef246ae0173528f7a1fd3805a8d87b70/" />
  <meta name="manubot_html_url_versioned" content="https://uiceds.github.io/project-team-all-right/v/c6472156ef246ae0173528f7a1fd3805a8d87b70/" />
  <meta name="manubot_pdf_url_versioned" content="https://uiceds.github.io/project-team-all-right/v/c6472156ef246ae0173528f7a1fd3805a8d87b70/manuscript.pdf" />
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
([permalink](https://uiceds.github.io/project-team-all-right/v/c6472156ef246ae0173528f7a1fd3805a8d87b70/))
was automatically generated
from [uiceds/project-team-all-right@c647215](https://github.com/uiceds/project-team-all-right/tree/c6472156ef246ae0173528f7a1fd3805a8d87b70)
on September 28, 2024.
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

The dataset for this project is obtained from the Energy Information Administration(EIA) website: U.S. Energy Information Administration - EIA - Independent Statistics and Analysis.

__Data Generation:__

The data gathered from the EIA website offers insights into the historical consumption rates of renewable energy sources, including hydroelectric power, solar energy, and biofuels, across the United States from 2000 to the present. 

__Format and Contents:__

The data is in a CSV file, making it accessible and easy to manipulate using standard data analysis tools. Key columns in the dataset include:
	Year: From 2000 to present.
	Region: The United States.
	Hydroelectric_Power (GWh): Annual consumption of hydroelectric power.
	Solar_Energy (GWh): Annual consumption of solar energy.
	Biofuels (GWh): Annual consumption of biofuels.


## Research Proposal and Objectives
__Proposal Overview:__

The historical data that we have collected from EIA regarding sustainable energy consumption will be utilized in the process of developing predictive models for the purpose of forecasting future patterns of likely sustainable energy consumption distribution. This particular research will primarily focus on three types of sustainable energy sources: hydroelectric power, solar energy, and biofuels. We will create an advanced data science model, using historical data for analysis and identifying the trending patterns (location-wise, seasonal-wise) for future potential clean energy consumption shift forecasting model creation. 

__Objectives:__

Strategic Planning: This study provides a better understanding of future consumption trends, which can help policymakers and companies for future energy production, infrastructure development (energy selection),  and investment in sustainable energy resources(ESG sustainable energy investment). With this model, a solid data-driven decision could be made based on a more comprehensive understanding of future energy consumption patterns. This could potentially reduce the risk of the strategized decision, and a more predictable future results in more responsible decision-making for the energy sector. 

Environmental Impact: This research aims to reduce carbon footprints and contribute to developing more environmentally friendly energy solutions in the future. This can have a positive impact on the environmental problems we are facing. 

In the process, we will:

Make reasonable predictions about future energy consumption based on the data set of historical consumption.
Apply various forecasting models to evaluate which model provides the best fit and most accurate predictions based on historical data by adding different influence factors.
Implement sensitivity analysis among external factors that could influence sustainable energy consumption, such as economic indicators, technological advancements, and policy changes, and determine the weights that each factor contribute. 
We will use Julia for data processing to analyze the dataset and provide valuable insights into the dynamics of sustainable energy usage, supporting the US transition to more sustainable and environmentally friendly energy systems.







## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
