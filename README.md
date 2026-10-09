## Geongyu Lee · 이건규

**Machine Learning Researcher** · Cross-modal learning · Reliable prediction · Computational Pathology × Multi-Omics · Seoul

**Portfolio: https://geongyu.github.io** ([English](https://geongyu.github.io/) · [한국어](https://geongyu.github.io/ko/) · [日本語](https://geongyu.github.io/ja/))

I am a machine learning researcher in computational pathology and multi-omics for oncology. I work on predicting molecular measurements such as gene expression, receptor status and assay-based recurrence risk groups from routine H&E slides, and on testing whether these predictions are reliable across sites, cohorts and unseen drugs.

I have 5+ years of industry R&D experience. I am an AI Researcher at **OMIXAI** (formerly RadiSen), where I lead multi-omics model R&D that combines proteomics and RNA with H&E for drug-response prediction (in progress). Before that, at **Deep Bio**, I built a WSI pipeline and contributed to pre-deployment model validation and regulatory documentation for a medical-AI product submitted to Korea's MFDS.

---

### Highlights

- **MoSPR** (preprint 2026, co-first author). Predicts gene expression from H&E using morpho-spatial macrostates and low-rank molecular programs. Best of 15 methods on three TCGA cancers (gene-wise PCC, BRCA 0.413). [arXiv](https://arxiv.org/abs/2609.34280) · [code](https://github.com/Radisen-Panthera/MoSPR)
- **Predictability is not substitutability** (BIOINFO/GIW ISCB-Asia 2026, accepted poster, first author). One pre-registered protocol with site-disjoint hold-outs and label-shuffle controls was applied to 5 cancers. Of ~15 endpoints, only HNSC HPV status (AUROC 0.959) met the confirmation criterion.
- **Scientific Reports 2025** (first author). Prediction of 21-gene recurrence-assay risk groups in early-stage breast cancer from H&E alone (n=125, 2 hospitals). Sensitivity L / I / H was 0.86 / 0.75 / 0.53. [paper](https://www.nature.com/articles/s41598-025-16679-x)
- **G2L** (AAAI 2026 Workshop W3PHIAI, oral, co-author). Distillation of giga-scale pathology foundation models into cancer-specific models. [arXiv](https://arxiv.org/abs/2510.11176)
- **KPIs 2024 Challenge** (MICCAI 2024). The Deep Bio team placed 2nd in the whole-slide track (glomerular segmentation). Co-author of the challenge report in *Medical Image Analysis* 2026.
- **OMIXAI**. Proteomics drug-response model evaluated leave-drug-out, so no test compound is seen in training (Pearson ≥ 0.65). Participating researcher in a Korea–Japan Pan-Sarcoma proteogenomics collaboration. Co-led OMIXAI's team entry in the Arc Institute Virtual Cell Challenge.
- Reviewer, ML4H 2026.

---

### Selected publications

| Year | Paper | Venue | Authorship |
|---|---|---|---|
| 2026 | [MoSPR: Histology-to-Gene Expression Prediction with Morpho-Spatial Macrostates and Low-Rank Molecular Programs](https://arxiv.org/abs/2609.34280) · [code](https://github.com/Radisen-Panthera/MoSPR) | Preprint (arXiv 2609.34280) | **Co-first** † |
| 2026 | [KPIs 2024 challenge: Advancing glomerular segmentation from patch- to slide-level](https://doi.org/10.1016/j.media.2026.104234) | Medical Image Analysis 2026 | Co-author (challenge report) |
| 2026 | [G2L: From Giga-Scale to Cancer-Specific Large-Scale Pathology Foundation Models via Knowledge Distillation](https://arxiv.org/abs/2510.11176) | AAAI 2026 Workshop (W3PHIAI), oral | Co-author |
| 2026 | [Spatial proteomics guided by H&E-based AI reveals recurrence-risk niches in triple-negative breast cancer](https://arxiv.org/abs/2608.03145) | Preprint (arXiv 2608.03145) | Co-author |
| 2026 | [Efficient AI-Driven Multi-Section Whole Slide Image Analysis for Biochemical Recurrence Prediction in Prostate Cancer](https://arxiv.org/abs/2603.20273) | Preprint (arXiv 2603.20273) | Co-author |
| 2025 | [Assessing the risk of recurrence in early-stage breast cancer through H&E stained whole slide images](https://www.nature.com/articles/s41598-025-16679-x) | Scientific Reports 2025 | **First** |
| 2025 | [Artificial intelligence–driven digital pathology in urological cancers: current trends and future directions](https://doi.org/10.1016/j.prnil.2025.02.002) | Prostate International 2025 (review) | **Co-first** † |
| 2024 | [MurSS: A Multi-Resolution Selective Segmentation Model for Breast Cancer](https://www.mdpi.com/2306-5354/11/5/463) | Bioengineering 2024 | Co-author |
| 2021 | [Supervised Contrastive Embedding for Medical Image Segmentation](https://ieeexplore.ieee.org/document/9564042) | IEEE Access 2021 | Co-author |

<sub>† equal contribution (co-first). Full list on [Google Scholar](https://scholar.google.com/citations?user=43BuluYAAAAJ). Conference talks and posters are on the [portfolio](https://geongyu.github.io/#conferences).</sub>

---

### Stack

- **Deep learning**: PyTorch · HuggingFace Transformers · PEFT / LoRA · Accelerate · DDP / FSDP
- **Pathology**: OpenSlide · QuPath · CLAM / weakly-supervised MIL · UNI · CONCH · Virchow · WSI tiling pipelines
- **Bio / omics**: scanpy · AnnData · proteomic representation learning · single-cell perturbation · ADMET modeling
- **MLOps**: Docker · Slurm · W&B · MLflow · FastAPI · Git

### Education

- **M.S. Data Science**, Seoul National University of Science and Technology (SeoulTech), 2019 – 2021
- **B.S. Information Security**, Daejeon University, 2012 – 2019

### Contact

[Portfolio](https://geongyu.github.io) · [Google Scholar](https://scholar.google.com/citations?user=43BuluYAAAAJ)
