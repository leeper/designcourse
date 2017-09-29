---
layout: default
title: Problem Set 3
ghurl: https://github.com/leeper/designcourse/tree/gh-pages
---

# Problem Set 3: Data Collection I (Quantitative Data)

## Purpose

The purpose of this problem set is to assess your ability to identify and use existing quantitative data.

## Overview

You will identify 2 concepts that can be translated into observable variables that describe countries. Using those concepts you will identify and discuss operationalizations of those concepts in an existing quantitative dataset, describe the data quantitatively, and then produce a visualization that allows for one or more descriptive inferences about the variables.

## Your Task

 1. Obtain a copy of the Quality of Government Cross-Section data from http://qog.pol.gu.se/data/datadownloads/qogstandarddata and download the "Codebook" that describes the available data.
 
 2. With reference to the available variables, identify and describe two important political science *concepts* that can be measured using the QoG dataset. Define each concept using any appropriate method of concept definition, explicitly identifying constituent attributes.
 
 3. Identify and discuss the operationalization of each concept in the QoG dataset. (Note: some concepts will allow for many possible operationalizations. Choose only one operationalization per concept.) Identify any strengths or weaknesses of the operationalization (in absolute terms or relative to other possible operationalizations), as they relate to your concept definitions and the criteria discussed in the course (precision, accuracy, construct validity, Gerring's criteria, etc.).
 
 4. Provide a quantitative summary of each variable. Try to state this summary in natural English prose in order to *describe* the data. To do this, you will need to load the data into R and save it as a data frame, which looks something like:
 
     ```r
     library("rio")
     govdat <- import("http://www.qogdata.pol.gu.se/data/qog_std_cs_jan16.dta")
     ```
 
 5. Using ggplot2, create three distinct types of visualizations showing different patterns or relationships in your data. For each plot, create a "worse" version and "better" version of the visualization and discuss why the "better" version communicates the pattern or relationship better, either in substantive terms or in purely aesthetic ones.
 
 6. Write up your reflections on the exercise, including identifying the most difficult and most enjoyable aspects.

## Submission Instructions

Your assignment should be no more than 3 pages of double-spaced A4, Times New Roman font size 12 (graphics should be one additional page). Submit the assignment via Moodle by Tuesday, November 21. 

## Feedback

You will receive feedback within two weeks.
