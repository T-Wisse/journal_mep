---
title: "Repeating SATAY for bem3d and bem1dbem3"
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
​
# Title : 12-07-21: DNA digestion and ligation for sequencing
​
## Date
12/07/21 - 
​
## Objective
DNA digestion and ligation for sequencing


## Method

Following the protocol of [benoit](https://sites.google.com/site/satayusers/complete-protocol/dna-sequencing) and notes from [leila](https://leilaicruz.github.io/Experimental-journal-jupyterBOOK/journal/2020-08/2020-08-24-Digestion-circularization-PCR.html) and [more from leila](https://leilaicruz.github.io/Experimental-journal-jupyterBOOK/journal/2020-10/2020-10-21-Digestion-Ligation2Sequence.html?highlight=digest)

DNA concentration of 2ug for digestion

- yTW001 4 - 1 (~135ng/ul) = 15ul of DNA
- yTW001 6 (~128ng/ul) = 15 uL of DNA
- yLIC137 7 (~81.4 ng/ul) = 25 uL of DNA
- yLIC137 8 (~127ng/ul) = 15 uL of DNA

digestion enzymes : DPNII & DpnII buffer (-20C freezer), NlaIII (-80C freezer)  & cutsmart buffer.

Add DNA + 5uL enzyme + 5uL bufferForEnzyme (10x) + H20 = 50uL (so 25 or 15 uL H20)

**12/07/21**

Testing the protocol and our DNA with a single test run using yTW001 4 - 1

Add in a RNA free, non stick eppi:

| Type  | Volume (uL) |
|-|-|
| yTW001 4 -1 DNA | 15ul |
| DpnII/NiaIII | 5uL |
| DpnII buffer/cutsmart (10x)| 5uL |
| H20 | 25ul |

- Put eppi in 37C for 16h

**13/07/21**

- 65°C for 20 min to inactivate reactions
- Run gel of digested sample (!% agarose gel, loaded 1uL DNA, 110V for 30min)
![Digestion was a great succes]()



- add 25 Weiss units T4 Ligase 6 hours at 22°C, in a volume of 400μl.
  - 40uL 10X Buffer Ligase
  - 49uL digested sample
  - 5uL T4 Ligase enzyme
  - 306uL MiliQ
- overnight or longer at -20°C in 0.3 M NaOAc pH5.2, 1 ml 100% EtOH, using 1 μg linear acrylamide (Ambion AM9520) as a carrier: DNA is precipitated
  - ORDER OF ADDITION IS IMPORTANT

**14/07/21**
- centrifuge for 20 min at 16100x g, 4°C. 
- wash pellet with 1 ml 70% EtOH, for 20 min at 16100 x g, 20°C.
- complete removal of the supernatant, pellets are dried for 10 min at 37°C.
- Pellet is resuspended in 105 uL of H2O

- Mix for 1 PCR:

| Amount         | Type          |
|----------------|---------------|
| 1uL            | dNTPs           |
| 5uL            | Primer 48 e fwd |
| 5uL            | Primer 49 e rev |
| 10uL           | TAQ buffer      |
| 4.5uL          | MgCL2           |
| 5uL            | DNA             |
| 1.2uL          | TAQ polymerase  |
| 18.3 uL        | milliQ          |

- For the first PCR, TAQ buffer with MgCL2 included was used, and different primers were used (not extended)
- Both DPNII and NIaIII digested and ligated DNA are used as the DNA 
- 10uL loaded
- Gel ran at 110V for 30min

![For both DPNII and NIaIII lanes only primer dimers are observed.](../Images/210713_digestionSatay_longerExposure_annotated.png)

![For both DPNII and NIaIII the lanes show one clear band and a surrounding smear corresponding to expectation based on gels shown in the benoit protocol.](../Images/210715_PCR_yTW001_4_SATAY_pellet_annotated.png)

**15/07/21**

The first PCR attempt was unsuccesful. The second attempt was succesful. Actual primers to be used in PCR are undetermined.