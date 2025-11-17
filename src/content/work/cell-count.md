---
title: CCV Calculator
publishDate: 2024-05-01 00:00:00
img: /assets/work/calculator_image.jpg
img_alt: Soft pink and baby blue water ripples together in a subtle texture.
description: |
  Cell count, viability, and variance calculator.
tags:
  - Excel
  - VBA
  - ReactJS
  - TypeScript
---

##### [Click here for a Demo](https://ccv-app.vercel.app/)

*NOTE: This demo is a React JS application built to mirror the excel calculator functionality.*

#### Background:
The CCV Calculator is a tool built to assist GMP manufacturing staff perform cell count and viability calculations.

During clean room operations, an automated cell counter (NC-200) was used to measure cell density. Duplicate measurements were performed to account for variance, which required the manufacturing staff to calculate percent difference and totals between replicates by hand.

To streamline the process and reduce calculation errors, I developed an excel tool to automatically calculate cell count, viability, and percent difference between the replicates.

#### Overview:

The calculator is a macro-enabled excel workbook that the manufacturing team could access on the shared drive from a laptop in the clean-room.  

Cell count and viability measurements are entered for each replicate and the tool calculates the average and variance for each set. 

The tool indicates when variance is out of specification based on the color displayed (fail = red, pass = green), so the user knows to repeat measurements.

 After obtaining an acceptable average (less than 10% variance, or the average of all 6 replicates), the user would then print a pdf report to sign and date and submit with the batch record. 


