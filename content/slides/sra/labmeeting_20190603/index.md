---
title: "SRA Update\n(Lab Meeting)"
date: "2019-06-03"
url: "/slides/sra/labmeeting_20190603/"
image: "/slides/sra/labmeeting_20190603/cover.jpg"
description: ""
ratio: "16:9"
themes:
- apron
- adirondack
- descartes
---
class: title, smokescreen, shelf, no-footer
background-image: url(cover.png)

# SRA Update (PacBio)
### June 3, 2019

---

class: col-2

# Adult vs Larval Testis
<!-- TODO: update counts -->

*Adult*
* **50** testes
* **3** Size Fractions
* PacBio RSII
* **209,637** CCS
* **4,532** Genes Covered
    - **46** CCS / Coverged Gene
* **8,053** Isoforms Covered
    - **26** CCS / Coverged Isoform

*Larval*
* **40** testes
* **2** Size Fractions
* PacBio Sequel
* **1,219,163** CCS
* **10,042** Genes Covered
    - **121** CCS / Coverged Gene
* **36,642** Isoforms Covered
    - **33** CCS / Coverged Isoform

.footer[(CCS) Consensus Reads]

---

class: col-2

# Summary: Gene Classification

*Adult*

| category        | # genes |
|-----------------|---------|
| Annotated Genes | 4,477   |
| Novel Genes     | 55      |


*Larval*

| category        | # genes |
|-----------------|---------|
| Annotated Genes | 9,166   |
| Novel Genes     | 876     |


---

class: col-2

# Summary: Splice Junction Classification

*Adult*

| category            | # SJs  |
|---------------------|--------|
| Known canonical     | 13,013 |
| Known Non-canonical | 8      |
| Novel canonical     | 454    |
| Novel Non-canonical | 229    |


*Larval*

| category            | # SJs  |
|---------------------|--------|
| Known canonical     | 24,857 |
| Known Non-canonical | 19     |
| Novel canonical     | 3,216  |
| Novel Non-canonical | 1,714  |


.footer[(SJs) Splice Junctions]

---

class: col-3, compact

# Summary: Transcript Classification <span style="font-size: 50%;">(Based on SJ Comparisons)</span>

![sqanti](sqanti.jpg)


*Adult*

| category         | # SJs |
|------------------|-------|
| FSM              | 5,225 |
| ISM              | 1,355 |
| NIC              | 640   |
| NNC              | 561   |
| Genic<br>Genomic | 162   |
| Fusion           | 51    |
| Antisense        | 22    |
| Intergenic       | 20    |
| Genic<br>Intron  | 17    |


*Larval*

| category         | # SJs  |
|------------------|--------|
| FSM              | 13,359 |
| ISM              | 12,625 |
| NIC              | 4,098  |
| NNC              | 3,373  |
| Genic<br>Genomic | 1,863  |
| Fusion           | 407    |
| Antisense        | 404    |
| Intergenic       | 293    |
| Genic<br>Intron  | 220    |


.footer[<span style="font-size: 60% !important" >(FSM) Full Splice Match; (ISM) Incomplete Splice Match; (NIC) Novel in Catalog; (NNC) Novel Not in Catalog -- Manuel et al. 2018. *Genome Research*.</span>] 

---

class: col-2, compact

# Summary: Distribution of Isoforms Per Gene

*Adult*

![Adult](adult_isoforms_per_gene.png# w-90pct)


*Larval*

![Larval](larval_isoforms_per_gene.png# w-90pct)

---

class: col-2, compact

# Summary: Distribution of TS Length

*Adult*

![Adult](adult_ts_length.png# w-90pct)


*Larval*

![Larval](larval_ts_length.png# w-90pct)

.footer[<span style="font-size: 50% !important" >(FSM) Full Splice Match; (ISM) Incomplete Splice Match; (NIC) Novel in Catalog; (NNC) Novel Not in Catalog</span>] 
---

class: col-2, compact

# Summary: Splice Junction Classification

*Adult*

![Adult](adult_splice_junctions.png# w-90pct)


*Larval*

![Larval](larval_splice_junctions.png# w-90pct)

---

class: col-2, compact

# Summary: Coding Genes by TS Class <span style="font-size: 50%;">(GMST)</span>

*Adult*

![Adult](adult_coding.png# w-90pct)


*Larval*

![Larval](larval_coding.png# w-90pct)

---

class: col-2, compact

# Quality Control: Template Switching

*Adult*

![Adult](adult_template_switch.png# w-90pct)


*Larval*

![Larval](larval_template_switch.png# w-90pct)

---

class: img-caption

# 2R:89,111 -- 129,538
![2R](2R_new1.png)

---

class: img-caption

# 3L:25,047,822 -- 25,095,604
![3L](3L_new1.png)

---

class: img-caption

# 3R:28,771,037 -- 28,773,095
![3R](3R_new1.png)
