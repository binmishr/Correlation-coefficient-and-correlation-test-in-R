# Correlation-coefficient-and-correlation-test-in-R

The details of the codeset and plots are included in the attached Microsoft Word Document (.docx) file in this repository. 
You need to view the file in "Read Mode" to see the contents properly after downloading the same.


Introduction

Correlations between variables play an important role in a descriptive analysis. A correlation measures the relationship between two variables, that is, how they are linked to each other. In this sense, a correlation allows to know which variables evolve in the same direction, which ones evolve in the opposite direction, and which ones are independent.

In this article, I show how to compute correlation coefficients, how to perform correlation tests and how to visualize relationships between variables in R.

Correlation is usually computed on two quantitative variables. See the Chi-square test of independence if you need to study the relationship between two qualitative variables.


Continuous Variables
======================

On the other hand, quantitative continuous variables are variables for which the values are not countable and have an infinite number of possibilities. For example:

    Age
    Weight
    Height

For simplicity, we usually referred to years, kilograms (or pounds) and centimeters (or feet and inches) for age, weight and height respectively. However, a 28-year-old man could actually be 28 years, 7 months, 16 days, 3 hours, 4 minutes, 5 seconds, 31 milliseconds, 9 nanoseconds old.

For all measurements, we usually stop at a standard level of granularity, but nothing (except our measurement tools) prevents us from going deeper, leading to an infinite number of potential values. The fact that the values can take an infinite number of possibilities makes it uncountable.

Correlogram
=============

The correlogram represents the correlations for all pairs of variables. Positive correlations are displayed in blue and negative correlations in red. The intensity of the color is proportional to the correlation coefficient so the stronger the correlation (i.e., the closer to -1 or 1), the darker the boxes. The color legend on the right hand side of the correlogram shows the correlation coefficients and the corresponding colors.

As a reminder, a negative correlation implies that the two variables under consideration vary in opposite directions, that is, if one variable increases the other decreases and vice versa. A positive correlation implies that the two variables under consideration vary in the same direction, that is, if one variable increases the other increases and if one variable decreases the other decreases as well. Furthermore, the stronger the correlation, the stronger the association between the two variables.

The Esquisse document is attached on this repository for your reference.

