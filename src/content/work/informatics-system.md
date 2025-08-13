---
title: CTiS
publishDate: 2019-12-01 00:00:00
img: /assets/stock-2.jpg
img_alt: A bright pink sheet of paper used to wrap flowers curves in front of rich blue background
description: | 
  Cell Therapy Informatics System
tags:
  - Express
  - NodeJS
  - MSSQL
---

Most cell therapy manufacturing processes utilize a paper system and require some form of manual data entry post-process to allow analysis for KPIs and process development/research activities.

While working as a manufacturing associate, I had the opportunity to build a new data entry system for the team. The previous system was a MicrosoftAccess database that satisfied all the requirements for data entry and storage, but was limited in user access (for the cross functional teams) and export options. Microsoft Access has general limitations for scalability and security, so we decided to build out a web-based data entry system. 

To accomplish this, I developed the interface using Node.js and Express. The database was migrated from MS Access to a Microsoft SQL server, and the application was connected through SSIS. This ensured security as we were able to perform authentication through the company's SSO login credentials. The web interface allowed access by users on any device on the local network, and allowed us to perform data sanitization and automate more of the calculations and fields for the users. We then built a KPI dashboard on the homescreen and an API to simplify data export for analysis by other departments. The user signin also allowed for more traceability as we were able to build a changelog for data entry and updates.

#### [CTiS Demo](https://duckduckgo.com)

###### The demo is a complete rebuild of this system formatted for general cell therapy product data fields. To expedite the build, I used Ruby on Rails as a framework with SQLite. 

