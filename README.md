## Geongyu Lee · 이건규

**Machine Learning Researcher** · Cross-modal learning · Reliable prediction · Computational Pathology × Multi-Omics · Seoul

**Portfolio: https://geongyu.github.io** ([English](https://geongyu.github.io/) · [한국어](https://geongyu.github.io/ko/) · [日本語](https://geongyu.github.io/ja/))

Machine learning researcher working on cross-modal learning from histology to molecular data and on predictions that stay reliable under distribution shift, applied to oncology.

I build models that read molecular state (gene expression, receptor status, assay-based recurrence risk) from routine H&E slides, and I test when those predictions hold up across hospitals, cohorts and compounds. 5+ years of industry R&D. Currently AI Researcher at **OMIXAI** (fmr. RadiSen), leading multi-omics model R&D that integrates proteomics and RNA with H&E for drug-response prediction (in progress). Previously AI Researcher at **Deep Bio**, where I built a WSI pipeline and contributed to pre-deployment model validation and regulatory documentation for a medical-AI product submitted to Korea's MFDS.

---

### Highlights

- **MoSPR** (preprint 2026, co-first author): H&E → gene expression via morpho-spatial macrostates and low-rank molecular programs; best of 15 methods on three TCGA cancers (gene-wise PCC, BRCA 0.413). [arXiv](https://arxiv.org/abs/2609.34280) · [code](https://github.com/Radisen-Panthera/MoSPR)
- **Predictability is not substitutability** (BIOINFO/GIW ISCB-Asia 2026, accepted poster, first author): one pre-registered protocol with site-disjoint hold-outs and label-shuffle controls across 5 cancers; of ~15 endpoints only HNSC HPV status (AUROC 0.959) met the confirmation criterion.
- **Scientific Reports 2025** (first author): H&E-only prediction of 21-gene recurrence-assay risk groups in early-stage breast cancer, n=125 from 2 hospitals; sensitivity L / I / H 0.86 / 0.75 / 0.53. [paper](https://www.nature.com/articles/s41598-025-16679-x)
- **G2L** (AAAI 2026 Workshop W3PHIAI, oral; 3rd of 6 authors): distilling giga-scale pathology foundation models into cancer-specific ones. [arXiv](https://arxiv.org/abs/2510.11176)
- **KPIs 2024 Challenge** (MICCAI 2024): 2nd place, whole-slide track, glomerular segmentation (Deep Bio team); challenge report in *Medical Image Analysis* 2026.
- **OMIXAI**: proteomics drug-response prediction evaluated leave-drug-out, so every test compound is unseen in training (Pearson ≥ 0.65); Pan-Sarcoma proteogenomics collaboration (Korea–Japan, participating researcher); co-led OMIXAI's team entry in the Arc Institute Virtual Cell Challenge.
- **Service**: reviewer, ML4H 2026.

---

### Selected publications

| Year | Paper | Venue | Author position |
|---|---|---|---|
| 2026 | [MoSPR: Histology-to-Gene Expression Prediction with Morpho-Spatial Macrostates and Low-Rank Molecular Programs](https://arxiv.org/abs/2609.34280) · [code](https://github.com/Radisen-Panthera/MoSPR) | Preprint (arXiv 2609.34280) | **Co-first** (†, 2nd of 4) |
| 2026 | [KPIs 2024 challenge: Advancing glomerular segmentation from patch- to slide-level](https://doi.org/10.1016/j.media.2026.104234) | Medical Image Analysis 2026 | 18th of 47 (challenge report) |
| 2026 | [G2L: From Giga-Scale to Cancer-Specific Large-Scale Pathology Foundation Models via Knowledge Distillation](https://arxiv.org/abs/2510.11176) | AAAI 2026 Workshop (W3PHIAI), oral | 3rd of 6 |
| 2026 | [Spatial proteomics guided by H&E-based AI reveals recurrence-risk niches in triple-negative breast cancer](https://arxiv.org/abs/2608.03145) | Preprint (arXiv 2608.03145) | 7th of 30 |
| 2026 | [Efficient AI-Driven Multi-Section Whole Slide Image Analysis for Biochemical Recurrence Prediction in Prostate Cancer](https://arxiv.org/abs/2603.20273) | Preprint (arXiv 2603.20273) | 6th of 8 |
| 2025 | [Assessing the risk of recurrence in early-stage breast cancer through H&E stained whole slide images](https://www.nature.com/articles/s41598-025-16679-x) | Scientific Reports 2025 | **First** (1st of 7) |
| 2025 | [Artificial intelligence–driven digital pathology in urological cancers: current trends and future directions](https://doi.org/10.1016/j.prnil.2025.02.002) | Prostate International 2025 (review) | **Co-first** (†, 2nd of 5) |
| 2024 | [MurSS: A Multi-Resolution Selective Segmentation Model for Breast Cancer](https://www.mdpi.com/2306-5354/11/5/463) | Bioengineering 2024 | 2nd of 7 |
| 2021 | [Supervised Contrastive Embedding for Medical Image Segmentation](https://ieeexplore.ieee.org/document/9564042) | IEEE Access 2021 | 3rd of 4 |

<sub>† equal contribution (co-first). Full list on [Google Scholar](https://scholar.google.com/citations?user=43BuluYAAAAJ); conference talks and posters on the [portfolio](https://geongyu.github.io/#conferences).</sub>

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
