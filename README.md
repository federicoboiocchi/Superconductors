# Superconductors Classification
### A Data-mining approach using: Adaptive Boosting, Bagging, and k-NN  
**Author:** Federico Boiocchi  

---

## Introduction

Superconductors are materials that, when cooled below a certain temperature
(called the *critical temperature*), lose all electrical resistance, meaning electric current can flow through them without any energy loss. This important behavior distinguishes them from standard conductors whose resistance decreases gradually as their temperature is lowered. The superconductivity property turns out to be highly useful in various fields of science from health-care, to energy production and delivery, not to mention its critical role in the high-tech electrical industry. 

---

## Research Interest 

This analysis is based on the Superconductivity dataset (from UCI machine learning depository: <https://archive.ics.uci.edu/dataset/464/superconductivty+data>) and has been conducted with the dual purpose of both introducing two robust classification models, namely **Adaptive Boosting** and **Bagging Trees**, and seeing them applied to a real-world problem.  

For this reason, this report will have both applied parts, in which the interpretation phase will be prominent, and more theoretical ones focused on mathematical details and performance comparison.  

I want to mention from the beginning that these data are the output of a cleaning procedure conducted on a larger dataset created by the *Japan's National Institute for Materials Science*. For this reason, they do not contain any missing value and they will turn out to be low-noise, highly-informative and well-separated data. As a consequence we won't see a huge improvement in performances of Bagging and AdaBoost with respect to standard methods.

Github: https://github.com/federicoboiocchi
Linkedin: https://www.linkedin.com/in/federico-boiocchi-152326249
