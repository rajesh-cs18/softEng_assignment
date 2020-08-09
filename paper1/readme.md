# PAPER 1 : [Cheating Death: A Statistical Survival Analysis of Publicly Available Python Projects](./paper1/readme.md "View Submission")

[![Generic badge](https://img.shields.io/badge/Conference-MSR_2020-<#fff>.svg)](https://2020.msrconf.org/) [![Generic badge](https://img.shields.io/badge/Track-Minning_Challenge-<#fff>.svg)](https://2020.msrconf.org/track/msr-2020-mining-challenge?track=MSR%20Mining%20Challenge) ![Generic badge](https://img.shields.io/badge/When-Mon_29,_Jun_2020_12:00-<#fff>.svg)

### **AUTHORS :** [Erik Linstead](https://2020.msrconf.org/profile/eriklinstead), [Chelsea Parlett-Pelleriti](https://2020.msrconf.org/profile/chelseaparlettpelleriti) and [Ali Rao Hamza](https://2020.msrconf.org/profile/aliraohamza)

### **ONE-SENTENCE**

>*"Reseacrchers tried to find out and study the behaviour, effect and validation using survival analysis methods on such attributes which lead to the inactivy of publically-available software project."*

### **INTRODUCTION**

In current time, new software development techniques are emerging at very high pace. Many of such projects are made available as **Open Source Software ([OSS](https://en.wikipedia.org/wiki/Open-source_software#:~:text=Open%2Dsource%20software%20(OSS),in%20a%20collaborative%20public%20manner.))** Projects on many [VCS](https://en.wikipedia.org/wiki/Version_control 'Version Control System')s sites such as [GitHub](https://github.com/), [Big Bucket](https://bitbucket.org/) and many other. Then many of such project are reused and improved by users.\
Reseacrchers tried to find out and study the behaviour, effect and validation using survival analysis methods on such attributes which lead to the inactivy of publically-available software project.

### **RESEARCH METHODOLOGY**

For dataset, subset of 3000 popular projects from ***popular-3k-python*** is taken from Software Heritage graph dataset, which includes
> Attributes of interest such as 
>
>+ **Major Releases** whether releases were published by the
project developers
>+ **Host Type** type of hosting service used for the project repository
>+ **Author Count** total unique developers that have committed
a revision to the repository
>+ **multipleRepositories** whether the project is hosted on
multiple version control systems

hosted on GitLab, GitHub, Debian, and PyPI in-between 2015 to 2018.\
They used [survival analysis](https://en.wikipedia.org/wiki/Survival_analysis#:~:text=Survival%20analysis%20is%20a%20branch,and%20failure%20in%20mechanical%20systems.) approach, which is
based on measurements of events that can occur at any time during
a study. The data used for survival analysis includes the time until
an event of interest occurs.

[Kaplan-Meier Survival Curves](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3059453/) were plotted of the chosen attributes against time using and [Cox Proportional-Hazards Model](https://sphweb.bumc.bu.edu/otlt/mph-modules/bs/bs704_survival/BS704_Survival6.html) was used on these to estimate the effect of these attributes on the health of open source projects.

### **RESULTS**

The percentage of projects that do have major releases is
relatively low, the survival rate for such projects was significantly
higher than the projects that did not publish noteworthy revisions.
Also show the effect of using multiple hosting repositories as
well as the type of service used on the projects in the long run.
They estimate that projects with a small core team is around six times more likely to become inactive compared to those that boast a diverse set of core
team developers.

Thank for reading.

[Click to move back](../readme.md)
