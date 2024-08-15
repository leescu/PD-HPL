Association between periodontitis with the all-cause and cause specific mortality among the population with hyperlipidemia
==============================

This code is the details of the manuscript "Association between periodontitis with the all-cause and cause specific mortality among the population with hyperlipidemia".


## Table of Contents

- [Overview](#overview)
- [System Requirements](#system-requirements)
- [Installation Guide](#installation-guide)
- [Deatails](#details)
- [Contributing](#contributing)
- [License](#license)
 
## Overview

Objective: To explore the association between periodontitis and all-cause as well as cause-specific mortality rates in U.S. adults with hyperlipidemia.
Materials and Methods: Participants were extracted from NHANES during 1988-1994, 1999-2004 and 2009-2014 periods. To assess the association between moderate-to-severe periodontitis and mortality rates for both all-cause and cause-specific mortality, hazard ratios (HRs), time ratios (TRs), and their respective 95% confidence intervals (CIs) were calculated using Cox proportional hazards and Weibull accelerated failure time (AFT) models. 
Results: Over a median follow-up duration of 11.83 years, 4623 deaths of 16,848 participants were recorded. Multivariate Cox regression and AFT analyses showed moderate-to-severe periodontitis were associated with an increased risk of all-cause (HR: 1.31, 95% CI: 1.20 - 1.44, P < 0.001; TR: 0.85, 95% CI: 0.80 - 0.90, P < 0.001), cardiovascular disease (CVD)-related (HR: 1.36, 95% CI: 1.14 - 1.63, P = 0.001; TR: 0.83, 95% CI: 0.75 - 0.92, P < 0.001) and cancer-related mortality ( HR: 1.35, 95% CI: 1.12 - 1.63, P = 0.002; TR: 0.82, 95% CI: 0.72 - 0.93, P = 0.002). Meanwhile, there was a significant upward trend in the risk of mortality with increasing severity of periodontitis (P for trend <0.001).


## System Requirements
### Hardware requirements
Requires only a standard computer with enough RAM to support the in-memory operations.

### Software requirements
### OS Requirements
Supported for *windows* and *Linux*. The package has been tested on the following systems:
+ Windows: Win 10
+ Linux: Ubuntu 20.04

### R Dependencies
Mainly depends on the R 4.1.2  . The versions of packages are, specifically:

```
car ≥ 3.1-1
dplyr ≥ 1.1.0
stringr ≥ 1.5.0
cmprsk ≥ 2.2-11
dplyr ≥ 1.1.0
foreign ≥ 0.8-84
ggplot2 ≥ 3.4.1
ggsci ≥ 2.9
ggrepel ≥ 0.9.3
lava ≥ 1.7.2.1
Matching ≥ 4.10-8
mice ≥ 3.15.0
devtools ≥ 2.4.5
pec ≥ 2022.5.4
poLCA ≥ 1.6.0.1
plyr ≥ 1.8.8
prodlim ≥ 2019.11.13
reshape2 ≥ 1.4.4
rms ≥ 6.5-0
riskRegression ≥ 2022.11.28
survey ≥ 4.1.1
scales ≥ 1.2.1
survminer ≥ 0.4.9
survival ≥ 3.5-0
splines ≥ 4.1.2
timeROC ≥ 0.4


```
#### Notes


The dependency package 'nhanesR' needs to be installed (https://github.com/shaoyoucheng/nhanesR).

Data and documentation of the National Health and Nutrition Examination Survey are available for download at [https://www.cdc.gov/nchs/nhanes/index.htm].


## Installation Guide

Installation via cloned repository:

```
$ git clone https://github.com/leescu/PD-HPL.git
$ cd PD-HPL
```


## Details

### 1.Calculation of Exposure and Outcomes

[./code/Step. 1 Exposure&Outcomes.R](https://github.com/leescu/PD-HPL/blob/main/code/Step.%201%20Exposure%26Outcomes.R)

### 2.Calculation of covariates

[./code/Step. 2 Covariates.R](https://github.com/leescu/PD-HPL/blob/main/code/Step.%202%20Covariates.R)

 
### 3.Data clearn

[./code/Step. 3 Arangement.R](https://github.com/leescu/PD-HPL/blob/main/code/Step.%203%20Arangement.R)


### 4. Analysis, Tables&Figures

[./code/Step. 4 Analysis.R](https://github.com/leescu/PD-HPL/blob/main/code/Step.%204%20Analysis.R)


## License

[The Apache license 2.0](LICENCE.md)
