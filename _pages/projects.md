---
permalink: /projects/
title: "Projects"
author_profile: true
---

## Master's Thesis

### Using VR and Objective Approach for Assessing Psychiatric Variables 
*M.S. in Data Science and Engineering · The City College of the City University of New York  · 2026 
· Advisors: Professor Dongrong Xu, Professor Zhigang Zhu*

**Objectives:** In this thesis, we focused on four main questions. First, whether structural
brain network measures from DTI can predict impulsive behavior in a VR shooting task
in patients with MDD. Second, whether more detailed network measures, such as nodal
betweenness, hub disruption, rich-club coefficient, within-module z-score, and
participation coefficient, can explain additional information beyond the global metrics.
Third, whether pre-shot motor features are related to clinical severity. And finally,
which pre-shot time window works best for predicting clinical outcomes.
**Method:** We started with 181 preprocessed diffusion-weighted neuroimaging datasets
from clinical recruitment. For participants with duplicate sessions, we retained the
session with the lowest head motion, measured by the eddy mean relative RMS
displacement.
Participants were included in the final sample if they met all of the following criteria: (i)
a confirmed MDD diagnosis; (ii) complete DWI data with a successfully reconstructed
structural connectome; and (iii) complete VR task data. The final sample included 78
MDD patients (59 females, 19 males; age range 12–38 years, mean = 19.8, SD (standard
deviation) = 6.4; mean HDRS = 17 (Hamilton Depression Rating Scale -17 items),
indicating severe depression; mean BIS-11 (Barratt Impulsiveness Scale, Edition 11)
score = 94.3, above the high-impulsivity threshold of 72).
**Findings:** Three brain–VR associations remained significant after FDR correction. Right
inferior frontal gyrus betweenness centrality showed a positive association with
collimation timer performance (β = 2.72, q = 0.002, ΔR² = 21.5%). Characteristic path
length and clustering coefficient were also significantly related to collimation timer
outcomes (q < 0.01). These effects remained stable in age adjusted analyses. Path length
and clustering effects were stronger in adolescent patients (n = 41) compared to adults
(n = 37). The frontal betweenness effect was consistent across both age groups.
In the expanded nodal analysis, we found 81 significant associations. The strongest
effects came from left temporal pole local efficiency and cerebellar degree, both related
2
to collimation timer performance. Within-module Z-score was also related to BIS-11
total (ρ = +0.34, p = 0.002) and motor impulsivity (ρ = +0.32, p = 0.004). We also
found that a VR-based cognitive impulsivity composite was positively associated with
suicidal ideation (ρ = +0.37, q = 0.024).
Partial least squares showed a significant brain–behavior relationship (r = 0.459, p <
0.001). Ridge regression explained about 24% of the variance in suicidal ideation. The
pre-shot window analysis showed a fairly stable pattern across 0.2–0.8 seconds, which
supports using the 0.6-second reference window.

[Thesis (PDF)](/files/thesis.pdf)

---

## Class Projects

### Speech Recognition for Nepali–English Code-Switching
*Capstone project · [Course] · [Term]*

Many Nepali speakers mix Nepali and English in the same sentence, and most speech tools handle this poorly. I am building a pipeline that detects which language is spoken in each segment before passing audio to Whisper, without retraining the model, and comparing its word error rate against Whisper alone. The project combines two public datasets of about 1,800 labeled clips.

[Code](REPO_LINK)

### Document Understanding with Transformer Models
*Team project · CSC I1910 · [Term]*

We benchmarked BERT, LayoutLMv2 and LayoutLMv3 on the FUNSD dataset for semantic entity recognition in scanned forms. I led hyperparameter tuning and learning-curve experiments, managed the project's git history, and co-wrote the final IEEE-format report and presentation.

[Report](LINK) · [Code](REPO_LINK)

### Memory Deduplication Timing Side-Channel
*OS Security · [Term]*

I built a timing side-channel attack in C against Linux kernel same-page merging (KSM) on Ubuntu (ARM64), and documented the kernel's layers of defense in a written report.

[Report](LINK)

### TrailMate: A Privacy Case Study
*Data Privacy · [Term]*

Designed a fictional trekking app as a thought experiment to examine what personal data such an app collects, the privacy risks involved, and how design choices could reduce them. Presented to the class.

[Slides](LINK)

---

## Symposiums and Presentations

### [Presentation title]
*[Event name] · [University] · [Month Year]*

[One or two sentences: what you presented and to whom.]

[Poster or slides](LINK)
