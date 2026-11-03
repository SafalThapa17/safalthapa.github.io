---
permalink: /projects/
title: "Projects"
author_profile: true
---

## Master's Thesis

### Using VR and Objective Approach for Assessing Psychiatric Variables 
*M.S. in Data Science and Engineering · The City College of the City University of New York  · 2026 
· Advisors: Professor Dongrong Xu, Professor Zhigang Zhu*

**Objectives:** 
In this thesis, we focused on four main questions. First, whether structural brain network measures from DTI can predict impulsive behavior in a VR shooting task in patients with MDD. Second, whether more detailed network measures, such as nodal betweenness, hub disruption, rich-club coefficient, within-module z-score, and participation coefficient, can explain additional information beyond the global metrics. Third, whether pre-shot motor features are related to clinical severity. And finally, which pre-shot time window works best for predicting clinical outcomes.

**Method:** 
We started with 181 preprocessed diffusion-weighted neuroimaging datasets from clinical recruitment. For participants with duplicate sessions, we retained the session with the lowest head motion, measured by the eddy mean relative RMS displacement. Participants were included in the final sample if they met all of the following criteria: 
(i) a confirmed MDD diagnosis; 
(ii) complete DWI data with a successfully reconstructed
structural connectome; and 
(iii) complete VR task data. The final sample included 78
MDD patients (59 females, 19 males; age range 12–38 years, mean = 19.8, SD (standard deviation) = 6.4; mean HDRS = 17 (Hamilton Depression Rating Scale -17 items), indicating severe depression; mean BIS-11 (Barratt Impulsiveness Scale, Edition 11) score = 94.3, above the high-impulsivity threshold of 72).

**Findings:** Three brain–VR associations remained significant after FDR correction. Right inferior frontal gyrus betweenness centrality showed a positive association with collimation timer performance (β = 2.72, q = 0.002, ΔR² = 21.5%). Characteristic path length and clustering coefficient were also significantly related to collimation timer outcomes (q < 0.01). These effects remained stable in age adjusted analyses. Path length and clustering effects were stronger in adolescent patients (n = 41) compared to adults (n = 37). The frontal betweenness effect was consistent across both age groups. In the expanded nodal analysis, we found 81 significant associations. The strongest effects came from left temporal pole local efficiency and cerebellar degree, both related to collimation timer performance. Within-module Z-score was also related to BIS-11 total (ρ = +0.34, p = 0.002) and motor impulsivity (ρ = +0.32, p = 0.004). We also found that a VR-based cognitive impulsivity composite was positively associated with suicidal ideation (ρ = +0.37, q = 0.024).
Partial least squares showed a significant brain–behavior relationship (r = 0.459, p < 0.001). Ridge regression explained about 24% of the variance in suicidal ideation. The pre-shot window analysis showed a fairly stable pattern across 0.2–0.8 seconds, which supports using the 0.6-second reference window.

[Thesis (PDF)](/files/thesis.pdf)

---

## Class Projects

### FormVISION: Semantic Entity Recognition on Scanned Forms
*Team project · CSCI1910 : Deep Neural Networks & AI Applications · Spring 2026*

Scanned forms present a unique challenge for natural language processing: the meaning of a word often depends not on its text content alone but on its two-dimensional position within the document. This paper presents FormVISION, a systematic study of Semantic Entity Recognition (SER) on the FUNSD benchmark dataset. We progressively evaluate four model families — a rule-based baseline, BERT (text-only), LayoutLMv2, and LayoutLMv3 — across a rigorous experimental framework including a 28-configuration hyperparameter grid search, a 150-run multi-seed ordering ablation, learning curve analysis, and label schema expansion. Our best result, LayoutLMv3 with tuned hyperparameters and shuffled entity ordering, achieves an entity-level F1 of 0.803 — a 43.4-point improvement over the default BERT baseline of 0.369. A key finding is that the effect of input token ordering reverses by model: BERT loses 7.4 F1 points when entity order is shuffled, while LayoutLMv3 gains 2.3 points, demonstrating that explicit spatial features allow multimodal models to use sequence order as data augmentation. Expansion of the OTHER class into four subcategories further reveals that the heterogeneous catch-all label masks distinct detection challenges requiring different input modalities.

[Report](https://github.com/SafalThapa17/formVision/blob/8881070fe0b7374b440d8e795c834119ced0da78/reports/final_report.md) · [Code](https://github.com/SafalThapa17/formVision/tree/8881070fe0b7374b440d8e795c834119ced0da78/notebooks/experiments)


### Inventory Simulation and Statistical Analysis in R
*DSE I1030: Applied Statistics · Fall 2024*

Exploring different strategy for inventory problems with visualization in R language 
Predicting Cardiovascular Disease Using Classification Models
and Ensemble Learning

[Report](https://github.com/SafalThapa17/InventorySimulation-and-Statistical-Analysis/blob/92d847d738c3339e233dc9261a29c663feef930b/Safal_Thapa_Project%201_Part_.pdf)

---
### Predicting Cardiovascular Disease Using Classification Models and Ensemble Learning
*DSE I2100 Applied Machine Learning and Data Mining · Fall 2025 *

Predicting Cardiovascular Disease Using Classification Models and Ensemble Learning

[Report](https://github.com/SafalThapa17/InventorySimulation-and-Statistical-Analysis/blob/92d847d738c3339e233dc9261a29c663feef930b/Safal_Thapa_Project%201_Part_.pdf)

---
## Symposiums and Presentations

### Exploring the Intersection of Data and Art
*Big Data, Spring 25 · The City College of the City University of New York · 2025*

Big Data course class symposium on intersection of Data and Art.

[Slides](https://github.com/SafalThapa17/Big-Data_2025/blob/954eca49b5008539449efd1b6b2a159977f79b77/Symposium/Symposium_Presentation.pdf)
