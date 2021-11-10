---
layout: page
title: "Activity Based Travel Models and Feature Selection"
doodle: "/doodle.png"
permalink: /
---

Data science capstone domain of inquiry (DSC 180AB B05)

Developed by Alex Cloninger, Dan Baeder, Steve Hardy, Deloitte Team

---
* TOC
{:toc}

---

# Introduction

This domain will investigate activity based travel demand moels.  This domain also centers on feature extraction and model validation for speeding up such agent based models.

A critical element of a transportation demand model is the capability to estimate mode choice; the travel mode (drive alone, carpool, bike, transit, etc.) that each synthetic person uses to get from activity to activity. Correctly determining the distribution of modes in the model has implications for understanding the impact of any policy, land use, or infrastructure change over time. 

A common approach to mode choice estimation is through use of a complex framework rooted in utility theory.  This setup typically involves a multitude of features and associated coefficients, many of which likely have a negligible impact of mode choice determination but make constructing the model challenging.  We will be investigating machine learning approaches to mode choice modeling that involves identifying only essential features and building a simplified model that can be more easily generalized and deployed.
 
Some questions we wil be answering throughout this domain:
- Can we use a machine learning approach, such as XGBoost or another tree-based method, to
construct a simplified mode choice model by identifying features that are most important to
determining mode choice?
- How can we confirm that a revised model yields appropriate results compared to other
methods?
- Can we generalize the approach to other populations?


## Result replication (introduction to topic)

We will delve into this area via the following papers:
- [Activity-Based Travel Demand Models: A Primer](http://onlinepubs.trb.org/onlinepubs/shrp2/SHRP2_C46.pdf), National Academies of Sciences, Engineering, and Medicine 2014  (selected chapers only).
- [Mode Choice Analysis Using Random Forest Decision Trees](https://www.sciencedirect.com/science/article/pii/S2352146516307347), Sekhar, Ravi, et al., 11th Transportation Planning and Implementation Methodologies for Developing Countries, 2014.
- [An optimized XGBoost based diagnostic system for effective prediction of heart disease](https://www.sciencedirect.com/science/article/pii/S1319157820304936)

and replicate results in preparation for analysis of the travel mode choice data.


# Section Participation

Participation in the weekly discussion section is *mandatory*. Each
week, you are responsible for doing the reading/task assigned in the
[schedule](#schedule). Come to section prepared to ask questions about
and discuss the results of these tasks.

Each week, turn in answers to the weekly questions to Canvas. These
questions are meant to focus your work for the week and help prepare
you for discussion. If you have questions about your work, please ask
them in section or office hours (I will rarely comment on your
submission).

You are responsible for the entire weekly reading/task, even if
portions are not covered in the weekly questions, as these are designed to help you in your replication. The weekly tasks are the building blocks for the project proposals/assignments due at the
end of the quarter.

---

# Schedule

|Week|Topic|
|--|--|
|1|[Introduction]({{ "/weeks/01-Introduction" | absolute_url }})|
|2|[Activity Based Travel Models]({{ "/weeks/02-Mode-Choice-Modeling" | absolute_url }})|
|3|[Travel Mode Choice]({{ "/weeks/03-Data-Preparation" | absolute_url }})|
|4|[Tree Based Methods]({{ "/weeks/04-XGBoost" | absolute_url }})|
|5|[XGBoost]({{ "/weeks/05-Classifier-Construction" | absolute_url }})|
|6|[Hyperparameters]({{ "/weeks/06-Hyperparameter-Tuning" | absolute_url }})|
|7|[Feature Selection]({{ "/weeks/07-Feature-Selection" | absolute_url }})|
|8|[Final Model Building]({{ "/weeks/08-Final-Model-Build" | absolute_url }})|
|9|[Ethics of Mobility Data]({{ "/weeks/09-Ethics-of-Mobility-Data-Collection" | absolute_url }})|
|10|Present Proposals|

---
# Office Hours with Deloitte researchers
Friday 10-11am PT, same zoom link as course

# Course location
See email to section for Zoom link

The Github page for this website that contains all needed code / data not specifically linked on the website is here: 
[https://github.com/ACloninger/capstone-deloitte-travel-models](https://github.com/ACloninger/capstone-deloitte-travel-models)

# Slack location
See email to section for link to join Slack channel






