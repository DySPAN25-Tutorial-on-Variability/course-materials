# DySPAN 2025 Tutorial: Measuring Wireless Signal Variability Using Everyday Smartphones


## Introduction

This tutorial introduces participants to practical techniques for measuring and analyzing outdoor signal level variability using commercial off-the-shelf (COTS) 4G and 5G smartphones. Using the measurement dataset of a recent large-scale measurement campaign, participants will learn how Reference Signal Received Power (RSRP) data from Android-based mobile devices can be used to compute location variability, an important metric in empirical propagation modeling.

Participants can explore how signal level variability changes with distance, frequency, and environment type, and how these measurements compare with classical propagation models such as free-space and clutter-based loss models. Through interactive exercises, attendees will learn how to process RSRP data, apply statistical methods to estimate variability, and interpret the results in the context of wireless coverage planning. This tutorial is for those interested in empirical propagation modeling.

All code is provide in Jupyter Notebooks. Please read along with the lessons, run all of the code, and analyze the plots and outputs.  

The data and analysis in this tutorial was developed by M. Hollingsworth and D. Grunwald in "[An Evaluation of Mid-Band Signal Level Variability with 4G and 5G Phones]([https://its.ntia.gov/publications/3367.aspx](https://ieeexplore.ieee.org/document/10905005))," 2025, IEEE RWS.

## To participate in the tutorial

1. **Send your GitHub username to max.hollingsworth@colorado.edu** for access to the course materials and coding environment. Once we receive your email, you will be invited you to the [DySPAN 2025 Tutorial GitHub organization](https://github.com/DySPAN25-Tutorial-on-Variability).

2. Next, accept the invitation to join the GitHub organization. This can be done from your [GitHub organizations tab](https://github.com/settings/organizations) as shown.

   ![alt text](./images/org_invite.png "Example org. invite")

3. Go to [the tutorial webpage](maxstutorial.com) to access your personal JupyterLab instance. Log in with your GitHub account.

4. Run the lessons.

   All course materials are pre-loaded in your JupyterLab instance. Once you've logged into your instance, double click on the `course-materials/` folder on the left-hand side to access the lessons. 

   - [**`course-materials/Lesson1.ipynb`**](Lesson1.ipynb) an introduction to using Jupyter Notebooks.

   - [**`course-materials/Lesson2.ipynb`**](Lesson2.ipynb) on understanding 4G and 5G measurements.

   - [**`course-materials/Lesson3.ipynb`**](Lesson3.ipynb) on cleaning RSRP data.

   - [**`course-materials/Lesson4.ipynb`**](Lesson4.ipynb) on modeling signal level variability.

   - [**`course-materials/data/`**](./data) a directory containing RSRP measurement data.
