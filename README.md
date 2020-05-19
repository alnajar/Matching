# Matching
SAS code used for data analysis described in the following publication is provided in this directory. 

Li Y, Schaubel DE and He K. Matching methods for obtaining survival functions to estimate the effect of a time-dependent treatment. Statistics in Biosciences. (2013). 1-22.

Abstract: 
In observational studies of survival time featuring a binary time-dependent treatment, the hazard ratio (an instantaneous measure) is often used to represent the treatment effect. However, investigators are often more interested in the difference in survival functions. We propose semiparametric methods to estimate the causal effect of treatment among the treated with respect to survival probability. The objective is to compare post-treatment survival with the survival function that would have been observed in the absence of treatment.
For each patient, we compute a prognostic score (based on the pre-treatment death hazard) and a propensity score
(based on the treatment hazard). Each treated patient is then matched with an alive, uncensored and not-yet-treated patient with
similar prognostic and/or propensity scores. The experience of each treated and matched patient is weighted using a variant of Inverse Probability of Censoring Weighting to account for the impact of censoring. We propose estimators of the treatment-specific survival functions (and their difference), computed through weighted Nelson-Aalen estimators. Closed-form variance estimators are proposed which take into consideration the potential replication of subjects across matched sets. The proposed methods are evaluated through simulation, then applied to estimate the effect of kidney transplantation on survival among end-stage renal disease patients using data from a national organ failure registry.
