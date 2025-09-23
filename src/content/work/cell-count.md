---
title: CCV Calculator
publishDate: 2022-10-01 00:00:00
img: /assets/work/calculator_image.jpg
img_alt: Soft pink and baby blue water ripples together in a subtle texture.
video: /assets/work/NC_calculator_demo.mp4
description: |
  Cell count, viability, and variance calculator.
tags:
  - Excel
  - VBA
---


The CCV Calculator is a tool built to assist GMP manufacturing staff perform cell count and viability calculations.

#### Background:

During clean room operations, an automated cell counter (NC-200) was used to measure cell density. Duplicate measurements were performed to account for variance, which required the manufacturing staff to calculate percent difference and totals between replicates by hand. To streamline the process and reduce calculation errors, I developed an excel tool to automatically calculate cell count, viability, and percent difference between the replicates. After building the tool and allowing the team to peform user testing, I wrote and executed a validation report to support GMP use. 

#### Overview:

The calculator is a macro-enabled excel workbook that the manufacturing team could access on the shared drive from a laptop in the clean-room.  

To use the tool, the user first enters the product lot number to autopopulate the form header. Cell count and viability measurements are then entered and the tool auto-calculates the average for each set. The tool indicates when variance is out of specification (based on the color displayed) so the user knows to repeat measurements. After obtaining an acceptable average, the user would then print a pdf report to sign and date and submit with the batch record. 

#### Demo:
