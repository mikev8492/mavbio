---
title: CTiS
publishDate: 2025-10-01 00:00:00
img: /assets/work/ctis_landing.png
img_alt: A bright pink sheet of paper used to wrap flowers curves in front of rich blue background
description: | 
  Cell Therapy Informatics System
tags:
  - Express
  - NodeJS
  - MSSQL
  - SQLite
---

**CTiS** stands for **Cell Therapy Informatics System** and is a data entry application built for GMP cell therapy manufacturing processes. 

#### Background:

Cell Therapy manufacturing processes that utilize a paper batch record system require some form of manual data entry post-process to allow analysis for KPIs and process development/research activities.

While working as a manufacturing associate, I had the opportunity to build a new data entry system for the team. The previous system was a Microsoft Access database that satisfied all the requirements for data entry and storage, but was limited in user access control (for the cross functional teams), scalability, and security. We decided to build a custom web-based data entry system in-house. 

The front end was built using Node.js and Express. The database was migrated from MS Access to a Microsoft SQL server and connected through SSIS. This ensured security as we were able to perform authentication through employee's SSO login credentials. The web interface allowed access by users on any device on the local network, and allowed us to have more control and customizability within the forms. 

#### Overview:
The system is built to manage multiple cell therapy products. Each product has its own forms, product chart and schema in the database. 

![CTiS home page](/assets/work/ctis_home.png)

A list of lots for each product displays with a status indicator for the manufacturing run. The Lot number search field uses a "fuzzy" search algorithm to display a partial match to anything entered by the user. 

![CTiS product page](/assets/work/ctis_product.png)

The data entry forms are customized for each product's unique parameters and process flow. 
Each process day/section can be saved by MFG and locked by Quality Assurance (or any pre-defined user groups) independently, allowing multi-day cultures to be reviewed as they are processed. Each field is formatted to ensure data consistency using double-entry and auto-formatting for time and date fields, and a chart displays cell yield and dose information for process visibility. 
The export button outputs the selected lot's process data as CSV for external data analysis. 

![CTiS Lot data entry form](/assets/work/ctis_lot.png)

##### [Click here for a Demo](https://ctis.onrender.com)

*NOTE: The demo version was rebuilt with SQLite and is configured with a guest (read-only) profile.* 
 
