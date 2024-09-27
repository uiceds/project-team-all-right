---
title: 'Wastewater Treatment Plant Energy Consumption Analysis '
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2024-09-27'
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
  <meta name="dc.title" content="Wastewater Treatment Plant Energy Consumption Analysis " />
  <meta name="citation_title" content="Wastewater Treatment Plant Energy Consumption Analysis " />
  <meta property="og:title" content="Wastewater Treatment Plant Energy Consumption Analysis " />
  <meta property="twitter:title" content="Wastewater Treatment Plant Energy Consumption Analysis " />
  <meta name="dc.date" content="2024-09-27" />
  <meta name="citation_publication_date" content="2024-09-27" />
  <meta property="article:published_time" content="2024-09-27" />
  <meta name="dc.modified" content="2024-09-27T20:14:34+00:00" />
  <meta property="article:modified_time" content="2024-09-27T20:14:34+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Yuhao" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta name="twitter:creator" content="@johndoe" />
  <meta name="citation_author" content="Trix Li" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_institution" content="Department of Whatever, University of Something" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta name="citation_author" content="YUlin Zhu" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_institution" content="Department of Whatever, University of Something" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta name="citation_author" content="Jingfei Qiao" />
  <meta name="citation_author_institution" content="Department of Civil and Environmental Engineering, University of Whatever" />
  <meta name="citation_author_institution" content="Department of Whatever, University of Something" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <link rel="canonical" href="https://uiceds.github.io/project-team-all-right/" />
  <meta property="og:url" content="https://uiceds.github.io/project-team-all-right/" />
  <meta property="twitter:url" content="https://uiceds.github.io/project-team-all-right/" />
  <meta name="citation_fulltext_html_url" content="https://uiceds.github.io/project-team-all-right/" />
  <meta name="citation_pdf_url" content="https://uiceds.github.io/project-team-all-right/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://uiceds.github.io/project-team-all-right/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://uiceds.github.io/project-team-all-right/v/9926d5853ef47af7668911bd6cd202df3b3ed895/" />
  <meta name="manubot_html_url_versioned" content="https://uiceds.github.io/project-team-all-right/v/9926d5853ef47af7668911bd6cd202df3b3ed895/" />
  <meta name="manubot_pdf_url_versioned" content="https://uiceds.github.io/project-team-all-right/v/9926d5853ef47af7668911bd6cd202df3b3ed895/manuscript.pdf" />
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
([permalink](https://uiceds.github.io/project-team-all-right/v/9926d5853ef47af7668911bd6cd202df3b3ed895/))
was automatically generated
from [uiceds/project-team-all-right@9926d58](https://github.com/uiceds/project-team-all-right/tree/9926d5853ef47af7668911bd6cd202df3b3ed895)
on September 27, 2024.
</em></small>



## Authors



+ **Yuhao**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
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
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [janeroe](https://github.com/janeroe)
    <br>
  <small>
     Department of Something, University of Whatever; Department of Whatever, University of Something
  </small>

+ **YUlin Zhu**
  ^[✉](#correspondence)^<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [janeroe](https://github.com/janeroe)
    <br>
  <small>
     Department of Something, University of Whatever; Department of Whatever, University of Something
  </small>

+ **Jingfei Qiao**
  ^[✉](#correspondence)^<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [janeroe](https://github.com/janeroe)
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


## Abstract {.page_break_before}







## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

