Periodontitis and the risk of all-cause and cause-specific mortality among US adults with diabetes: A population-based cohort study
==============================

This code is the details of the manuscript "Periodontitis and the risk of all-cause and cause-specific mortality among US adults with diabetes: A population-based cohort study".


## Table of Contents

- [Overview](#overview)
- [System Requirements](#system-requirements)
- [Installation Guide](#installation-guide)
- [Deatails](#details)
- [Contributing](#contributing)
- [License](#license)
 
## Overview

Aim: To evaluate the association between periodontitis, all-cause, and cause-special mortality, and its prognostic utility among adults with diabetes. 
Materials and Methods: Periodontal health records were retrieved from the NHANES database for 4,297 participants aged over 30 years at baseline with diabetes during 1988–1994, 1999–2004, and 2009–2014. Multivariable Cox proportional hazards regression model was applied to calculate hazard ratios (HRs) and 95% confidence intervals (CIs) for moderate/severe periodontitis with all-cause and cause-specific mortality in participants with diabetes. Area under the curve (AUC) assessed predictive value.
Results: During a median follow-up of 9.42 years, 1,701 deaths occurred. After multivariate adjustments, moderate/severe periodontitis was significantly associated with increased risk of all-cause (HR: 1.27; 95% CI: 1.07–1.50; P = 0.005) and cardiovascular disease (CVD)-related mortality (HR: 1.35, 95% CI: 1.03–1.76, P = 0.031) in participants with diabetes. Periodontitis improved prediction of all-cause (AUC: 0.652; 95% CI: 0.627–0.676) and CVD-related mortality (AUC: 0.649; 95% CI: 0.624–0.676) over standard risk factors (All cause: AUC: 0.631; 95% CI: 0.606–0.656. CVD-related: AUC: 0.629; 95% CI: 0.604–0.655).
Conclusions: Moderate/severe periodontitis is associated with an increased risk of all-cause and CVD-related mortality in adults with diabetes. Periodontitis might represent a marker for residual risk.


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


### 4. Tables&Figures

[./code/Step. 4 Analysis.R](https://github.com/leescu/PD-HPL/blob/main/code/Step.%204%20Analysis.R)


## License

[The Apache license 2.0](LICENCE.md)
