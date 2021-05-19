---
title: "Satay plasmid transformation in dbem1bem3 and dbem3"
output: pdf_document
documentclass: article
classoption: onecolumn
pdf_document:
latex_engine: pdflatex
toc: true
lof: true
numberSections: true
highlight: tango
sectionsDepth: 3
chapters: True
figPrefix:
  - "Fig."
  - "Figs."
secPrefix:
  - "Section"
  - "Sections"
fontsize: 12pt
geometry: margin=0.5in
autoEqnLabels: true
cref: true
crossref: true
colorlinks: true
---

# Transforming yTW001 and yLIC137 to contain the SATAY plasmid

## Date
21/04/21 -  

## Objective
- Obtain cells with the SATAY plasmid in the yTW001(bem3::NAT bem1::KanMX ade2- ura3-) background and yLIC137 (bem3::NAT ade2- ura3-) by transformation with the plasmid.

## Methods & Results 

### Overview methods
- Transform SATAY plasmid into yTW001
- Check succes of transformation

Protocols: 
    - Yeast Transformation

### Base for selection media


- [] Create 20 agar plates (400ml) of CSM - ura + ade
    - Autoclave 300ml MiliQ+Agar

| Amount         | Type         |
|----------------|--------------|
| 300 ml         | MiliQ        |
| 8 g            | agar         |

    - Add by filter stirilization the rest of the components

| Amount         | Type          |
|----------------|---------------|
| 0.76 g         | YNB           |
| 0,308 g        | AA dropout mix -URA |
| 0.044 g        | adenine       |
| 60mL           | MiliQ         |
| 40 ml          | 20% dextrose  |

Check plates with yWKD017 (+), yWKD001(-), yLIC135(-) ?? check for +ade?

## Transformation with SATAY plasmid
- Following protocol P.24 High Efficiency Transformation of Yeast

- Incubate yTW001 and yLIC137 YPD+ade at 30C for a day
- Measure OD for 100x diluted culture

| Sample | yTW001A | yTW001B | yTW001C | yLIC137_1 | yLIC137_2A |
|-|-|-|-|-|-|
| OD | 0.311 | 0.304 | 0.291 | 0.313 | 0.283 |

- Used YPD+ade stock was contaminated --> Repeat. 

- Incubate yTW001 and yLIC137 in YPD+ade at 30C for a day
OD measurement with Nanodrop at 100x dilution

| Sample | yTW001A | yTW001B | yTW001C | yLIC137_1 | yLIC137_2A |
|-|-|-|-|-|-|
| OD | 0.001 | -0.002 | -0.004 | 0.073 | 0.056 |

- Protocol: dilute to 5*10^6 cells/ml:
- yTW001 strains need to incubate longer.
- yLIC137_1: 7.3 * 10^7 cells/ml -> dilute 15 times
- yLIC137_2: 5.6 * 10^7 cells/ml -> dilute 10 times

| Sample | yLIC137_1 | yLIC137_2A |
|-|-|-|
| Culture (ml) | 0.66 | 1 |
| YPD+ade (ml) | 9.34 | 9 |

- Incubate for ~4 hours until 2*10^7 cells/ml (OD of 2)
- OD measurement with Nanodrop at 10x dilution after 80 minutes:
| Sample | yLIC137_1 | yLIC137_2A |
|-|-|-|
| OD | 0.056 | 0.076 |

- OD after ~4 hours:
| Sample | yLIC137_1 | yLIC137_2A |
|-|-|-|
| OD | 0.133? | 0.170 |



- Transfer to plastic tube
- Centrifuge at 3000g (2500rpm) for 5 minutes
- Pour off medium, resuspend in sterile 10 ml milliQ 

....
- plate 200uL and 110 uL (10 ul sample in 100ul milliQ)
- incubate for 3 days at 30C

Selection plates of yTW001 show strange colonies. They appear very liquid and are not according to expectation. The plates do not smell like yeast, or bacteria. 10 uL on diluted cells was put under the microscope. This showed yeast cells and some unidentified cells. Transformation well be repeated.

## Sanity check
Plate 8 single colonies from selection plates on both -Ade and -Ura plates. 
Initially plates different colonies on -Ade (1-8) and -Ura (9-16), but it should come from the same colony -> repeat
Growth on -Ade should be possible by the rare random recombination of the transposon repairing the ADE2 gene in the plasmid. This should be possible but very unlikely. Therefore we select the colonies which show more than 0 colonies on -Ade, but otherwise as few as possible.
The growth of the same colony in -Ura is then checked. Presence of the plasmid should provide growth on -ura plates, while a lack of the plasmid should result in no growth. Therefore we look for colonies with very slight growth in -ade and large growth in -ura.

## observations 12/05
Media was contaminated. Transformation of yTW001 delayed. New YPD+ade and dextrose was made.


YPD+ade

| Amount         | Type         |
|----------------|--------------|
| 360 ml         | MiliQ        |
| 4 g            | Yeast extract|
| 8 g            | bacto-peptone|
| 0.022 g        | adenine      |

Added after filtering:

| Amount         | Type          |
|----------------|---------------|
| 40 ml          | 20% dextrose  |


20% dextrose
| Amount         | Type          |
|----------------|---------------|
| 100 ml         |      H2O      |
| 40 g           |      dextrose |
| add to 200 ml  |      H2O      |

## 17-05
- Previous media was contaminated. 
- New media was made while taking extra care to work sterile. 
- Previous glucose concentration was under 20% so new 20% dextrose was made. 
- yTW001A,B,C put to incubate in YPD + ade at 30C

## 19-05
- OD of incubated cultures measured at 10:00
- 100x diluted:
| Sample | OD | Concentration of culture
|-|-|-|
| A | 0.049 | 4.9*10^7|
| B | 0.056 | 5.6*10^7 |
| C | 0.061 | 6.1*10^7 |

- Dilute 10x and incubate at 30C
- 10x diluted yTW001A shows OD of 0.375 --> slight underestimation of cell count

- OD of diluted culture measured at 13:15
- 10x diluted 

| Sample | OD | Concentration of culture
|-|-|-|
| A | 0.067 | 6.7*10^6|
| B | 0.058 | 5.8*10^6 |
| C | 0.065 | 6.5*10^6 |

- Incubate further
- OD of diluted culture measured at 14:30