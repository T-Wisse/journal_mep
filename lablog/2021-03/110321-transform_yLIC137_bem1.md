# Transforming yLIC137_2 to contain bem1 del

## Date
11/03/21 - 17/03/21

## Objective
Obtain cells with bem1d in the yLIC137 background by introducing PCR product containing the KanMX cassette on the bem1 loci

## Method

### Created 20 agar plates with YPD + adenine

- Final Volume: 400 ml liquid YPD + ade

300 ml Agar:

| Amount         | Type         |
|----------------|--------------|
| 300 ml         | H2O          |
| 8 g            | agar         |

60 ml YP-D + ade

| Amount         | Type          |
|----------------|---------------|
| 4 g            | Yeast extract |
| 8 g            | bacto-peptone |
| 0.044 g        | adenine       |

400 ml liquid YPD + ade

| Amount         | Type          |
|----------------|---------------|
| 300 ml         | agar + H2O    |
| 60 ml          | YP-D + ade    |
| 40 ml          | 20% dextrose  |

pipet 20 ml per plate (sterile). Store at 4C after solidifying. 1 plated with yLIC133 (WT) and incubated at 30C overnight

### Growth of yLIC137_2 in liquid YPD+ade
2 tubes with 10 ml YPD+6xade + 2% dex (from Leila) and yLIC137_2. Put to incubate at 30C

### Transformation

- Create selection plates: Adding 40 ul G418 and 20 ul clonNAT (antibiotics) to YPD+ade plates. Spread with glass beads, allowed to dry (upside down, a few hours)
- Perform transformation following protocol P.24 High Efficiency Tranformation of Yeast v 1.0

Cell concentration of both liquid yLIC137_2 cultures with nanodrop (step 2):

cells diluted 2x

| Colony         | measured OD   | Actual OD   |
|----------------|  ---------------|-------------|
| A              | 0.198         | 0.396       |
| B              | 0.158         | 0.316       |

Allow to incubate for 4 hours (step 4 of transformation protocol)
cells diluted 10x

| Colony         | measured OD   | Actual OD   |
|----------------|---------------|-------------|
| A              | 0.257         | 2.57        |
| B              | 0.207         | 2.07        |

- plated out volume onto prepared selective plates (A1: 800uL, B1: 1ml, control: 200uL of A1). incubated at 30C for 3 days

### colony PCR
- New selection plates: Adding 50uL G418 and 30uL clonNAT. Spread with glass beads and allowed to dry.
- Selected 7 individual colonies from A1 plate and 1 from B1 plate (marked). Scraped and suspended in 50uL milliQ. Restreaked on newly made selection plates
by stirring tip in epi.

- Performed PCR for all 8 samples using 5uL of suspended cells as template and primers OLIC54 & 55: loaded 10uL per lane. Ran gel at 120V for 30 min.

- A1, B1 (from which colonies were picked) are stored at 4C with parafilm for later use.

## Results
- A1 and B1 both show growth. Positive control plate shows growth. Negative control plate shows some growth at the edges. Probably where concentration of antibiotic was very low. 

(insert images of plates?)

- DNA gel shows DNA bands at 2.5kb and 2.0kb for each colony, at varying concentrations. several bands around 200bp are also observed.

![ DNA gel of PCR of colonies transformed with bem1d construct. Using primers OLIC54 and OLIC55 (flanking BEM1). DNA is present in all lanes with differing concentrations. The full construct is 2507 bp. All lanes show band at length of ~2.5kb. Additionally a band at 2kb is visible, as well as several short bands around 200bp. ](../Images/210315-colonyPCR_yLIC137_bem1dConstruct_annotated.png){#fig:gel_PCR}

All the restreaked colonies combined show only 2 colonies in total after 3 days of growth.

## Conclusion
- The growth of yeast on selection plates suggests our transformation has been sucessful as cells show resistance to the used antibiotics. 

- The presence of 2.5kb bands suggests that that our DNA has been inserted into the genome.
- The location of the insertion is not determined. Requires other primers which have been ordered (15/03/21). 

- Bands at 2kb and around 200bp are possibly non-specific product of the PCR. By first performing a genome purification and then the PCR we may learn more.

- The restreaked colonies showed no growth. Possibly the number of cells in solution was too low. Repeat experiment with new colonies and streak 40uL volume of cell suspension. 

