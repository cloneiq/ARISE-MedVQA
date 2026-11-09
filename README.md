<p align="center">
  <img src="images/arise-medvqa-sig-cover.png" alt="ARISE-MedVQA Banner" width="90%"/>
</p>
<p align="center">
  <b>A curated academic resource hub for ARISE-MedVQA</b><br>
  From Passive Answering to Active Inquiry · Evidence-Driven Reasoning · Medical Visual Question Answering
</p>


ARISE-MedVQA is a curated literature resource repository for Medical Visual Question Answering (Med-VQA), covering surveys, research directions, datasets, benchmarks, evaluation metrics, representative methods, and multimodal medical agent studies. The repository is not a single model implementation. Instead, it provides a structured and continuously updated entry point for researchers to understand the evolution, core resources, evaluation frameworks, and emerging trends of Med-VQA. Centered on the shift from passive answer prediction to active, evidence-seeking, risk-aware clinical inquiry, ARISE-MedVQA organizes key papers, datasets, benchmarks, evaluation protocols, and technical methods to support literature review, dataset selection, method comparison, experimental design, survey writing, and future research on interactive and clinically grounded medical AI.

This project is suitable for the following research and teaching scenarios:

- Researchers working on Medical Visual Question Answering, medical multimodal large models, and medical AI agents;
- Graduate students who need a quick and structured overview of Med-VQA datasets, methods, benchmarks, and research trends;
- Developers working on medical image question answering, report generation, interactive diagnostic support, or knowledge-enhanced medical reasoning;
- Authors preparing Med-VQA surveys, research proposals, grant applications, thesis topics, or benchmark studies;
- Teams interested in building medical multimodal datasets, evaluation frameworks, or active diagnostic interaction systems.

# [Browse the Literature by Category](catalog/README.md)

Each paper has one primary collection, determined by its main contribution. Cross-cutting themes connect related work across collections.

| Collection                                                   | Papers | What you will find                                           |
| :----------------------------------------------------------- | -----: | :----------------------------------------------------------- |
| [**Reviews & Surveys**](catalog/Survey/README.md)            |     23 | Research syntheses, taxonomies, evidence gaps, and future directions |
| [**Datasets & Data Resource**](catalog/Dataset/README.md)    |     27 | Data resources, task construction, annotation, and quality control |
| [**Benchmarks & Evaluation**](catalog/Benchmark/README.md)   |     37 | Evaluation tasks, protocols, metrics, and capability assessment |
| [**Methods & Algorithms**](catalog/Method/README.md)         |    203 | Task-specific architectures, learning mechanisms, and original algorithms |
| [**Foundation Models & Backbones**](catalog/Foundation/README.md) |     64 | Pretraining, transferable representations, and reusable model components |

# [Browse the Literature by Year](years/README.md)

| [2027](years/2027.md) | [2026](years/2026.md) | [2025](years/2025.md)  | [2024](#years/2024.md) |
| --------------------- | --------------------- | ---------------------- | ---------------------- |
| [2023](years/2023.md) | [2022](years/2022.md) | [2021](#years/2021.md) | [2020](years/2020.md)  |
| [2019](years/2019.md) | [2018](years/2018.md) |                        |                        |

<a id="year-2027"></a>

# Table of Contents

- [1. Surveys & Reviews](#section-1)
- [2. Datasets & Data Resources](#section-2)
  - [2.1. General Medical VQA Datasets](#section-2.1)
  - [2.2. Image–Text Pretraining & Instruction Data](#section-2.2)
  - [2.3. Radiology & Volumetric Imaging](#section-2.3)
  - [2.4. Pathology & Whole-Slide Imaging](#section-2.4)
  - [2.5. Endoscopy, Surgery & Medical Video](#section-2.5)
  - [2.6. Other Specialties, Education & Dialogue](#section-2.6)
- [3. Benchmarks & Evaluation](#section-3)
  - [3.1. Benchmark Resources & Shared Tasks](#section-3.1)
  - [3.2. Capability & Comparative Studies](#section-3.2)
  - [3.3. Reliability & Evaluation Protocols](#section-3.3)
- [4. Foundation Models & Reusable Backbones](#section-4)
  - [4.1. Reusable Visual & Vision-Language Encoders](#section-4.1)
  - [4.2. Generalist Biomedical Vision-Language Models](#section-4.2)
  - [4.3. Specialty & Grounded Vision-Language Models](#section-4.3)
- [5. Methods & Algorithms](#section-5)
  - [5.1. Architectures & Multimodal Fusion](#section-5.1)
  - [5.2. Representation Learning & Cross-modal Alignment](#section-5.2)
  - [5.3. Knowledge-enhanced & Retrieval-augmented Methods](#section-5.3)
  - [5.4. Prompt Learning & Efficient Adaptation](#section-5.4)
  - [5.5. Reasoning & Answer Generation](#section-5.5)
  - [5.6. Reliability, Generalization & Debiasing](#section-5.6)
  - [5.7. Agentic & Tool-augmented Systems](#section-5.7)

<a id="section-1"></a>

# 1. Surveys & Reviews

| Date    | Title                                                        | DOI                                                      |
| ------- | ------------------------------------------------------------ | -------------------------------------------------------- |
| 2026-07 | [MedVQA-2026-051](./Paper_Notes/Survey/2026/MedVQA-2026-051_SV_TSMVLVLMMVQAS.md) · Task-specific models vs. large vision-language models in medical visual question answering: A survey | [DOI](https://doi.org/10.1016/j.eswa.2026.132008)        |
| 2026-05 | [MedVQA-2026-029](./Paper_Notes/Survey/2026/MedVQA-2026-029_SV_FMICR.md) · Foundation Model for Medical Imaging: A Comprehensive Review | [DOI](https://doi.org/10.1109/tai.2025.3618796)          |
| 2026-03 | [MedVQA-2026-022](./Paper_Notes/Survey/2026/MedVQA-2026-022_SV_VLFDAASH.md) · Vision–language foundation model driven agentic AI systems for healthcare | [DOI](https://doi.org/10.1007/s00371-026-04437-7)        |
| 2026-02 | [MedVQA-2026-015](./Paper_Notes/Survey/2026/MedVQA-2026-015_SV_TSFMPSMVL.md) · From task-specific to foundation models: A paradigm shift in medical vision-language analysis | [DOI](https://doi.org/10.1016/j.cosrev.2025.100831)      |
| 2026-01 | [MedVQA-2024-059](./Paper_Notes/Survey/2026/MedVQA-2024-059_SV_FIC.md) · Frontiers in Intelligent Colonoscopy | [DOI](https://doi.org/10.1007/s11633-025-1597-6)         |
| 2026-01 | [MedVQA-2026-007](./Paper_Notes/Survey/2026/MedVQA-2026-007_SV_KDTSLMICOPRFD.md) · Knowledge distillation and teacher–student learning in medical imaging: Comprehensive overview, pivotal role, and future directions | [DOI](https://doi.org/10.1016/j.media.2025.103819)       |
| 2026-01 | [MedVQA-2026-008](./Paper_Notes/Survey/2026/MedVQA-2026-008_SV_KFDLMVLMR.md) · Knowledge fusion in deep learning-based medical vision-language models: A review | [DOI](https://doi.org/10.1016/j.inffus.2025.103455)      |
| 2025-08 | [MedVQA-2025-072](./Paper_Notes/Survey/2025/MedVQA-2025-072_SV_VLFMMISRMDAA.md) · Visual-language foundation models in medical imaging: A systematic review and meta-analysis of diagnostic and analytical applications | [DOI](https://doi.org/10.1016/j.cmpb.2025.108870)        |
| 2025-08 | [MedVQA-2025-077](./Paper_Notes/Survey/2026/MedVQA-2025-077_SV_VQAIAAO.md) · From visual question answering to intelligent AI agents in ophthalmology | [DOI](https://doi.org/10.1136/bjo-2024-326097)           |
| 2025-07 | [MedVQA-2025-003](./Paper_Notes/Survey/2025/MedVQA-2025-003_SV_WTADSMHLLLVLM.md) · Can We Trust AI Doctors? A Survey of Medical Hallucination in Large Language and Large Vision-Language Models | [DOI](https://doi.org/10.18653/v1/2025.findings-acl.350) |
| 2025-05 | [MedVQA-2025-043](./Paper_Notes/Survey/2025/MedVQA-2025-043_SV_CSLLMMLLMM.md) · A comprehensive survey of large language models and multimodal large language models in medicine | [DOI](https://doi.org/10.1016/j.inffus.2024.102888)      |
| 2025-05 | [MedVQA-2025-044](./Paper_Notes/Survey/2025/MedVQA-2025-044_SV_CMIS.md) · CLIP in medical imaging: A survey | [DOI](https://doi.org/10.1016/j.media.2025.103551)       |
| 2025-04 | [MedVQA-2025-031](./Paper_Notes/Survey/2025/MedVQA-2025-031_SV_LLMISTSRFT.md) · Large Language Model for Medical Images: A Survey of Taxonomy, Systematic Review, and Future Trends | [DOI](https://doi.org/10.26599/bdma.2024.9020090)        |
| 2025-03 | [MedVQA-2025-027](./Paper_Notes/Survey/2025/MedVQA-2025-027_SV_GMMVQAS.md) · Generative Models in Medical Visual Question Answering: A Survey | [DOI](https://doi.org/10.3390/app15062983)               |
| 2025-02 | [MedVQA-2025-023](./Paper_Notes/Survey/2025/MedVQA-2025-023_SV_ILMVRRS.md) · Integrating language into medical visual recognition and reasoning: A survey | [DOI](https://doi.org/10.1016/j.media.2025.103514)       |
| 2025    | [MedVQA-2025-010](./Paper_Notes/Survey/2025/MedVQA-2025-010_SV_VQARSCR.md) · Visual Question Answering in Robotic Surgery: A Comprehensive Review | [DOI](https://doi.org/10.1109/access.2024.3525145)       |
| 2024-10 | [MedVQA-2024-018](./Paper_Notes/Survey/2024/MedVQA-2024-018_SV_VLMMRGVQAR.md) · Vision-language models for medical report generation and visual question answering: a review | [DOI](https://doi.org/10.3389/frai.2024.1430984)         |
| 2024-03 | [MedVQA-2024-021](./Paper_Notes/Survey/2024/MedVQA-2024-021_SV_DCBMCRBQA.md) · Developing ChatGPT for biology and medicine: a complete review of biomedical question answering | [DOI](https://doi.org/10.52601/bpr.2024.240004)          |
| 2023-12 | [MedVQA-2023-050](./Paper_Notes/Survey/2023/MedVQA-2023-050_SV_SMMQA.md) · Survey of Multimodal Medical Question Answering | [DOI](https://doi.org/10.3390/biomedinformatics4010004)  |
| 2023-10 | [MedVQA-2023-038](./Paper_Notes/Survey/2023/MedVQA-2023-038_SV_SRMDLBIT.md) · A scoping review on multimodal deep learning in biomedical images and texts | [DOI](https://doi.org/10.1016/j.jbi.2023.104482)         |
| 2023-09 | [MedVQA-2021-012](./Paper_Notes/Survey/2023/MedVQA-2021-012_SV_MVQAS.md) · Medical visual question answering: A survey | [DOI](https://doi.org/10.1016/j.artmed.2023.102611)      |
| 2023-04 | [MedVQA-2023-016](./Paper_Notes/Survey/2023/MedVQA-2023-016_SV_CIMVDTC.md) · A comprehensive interpretation for medical VQA: Datasets, techniques, and challenges | [DOI](https://doi.org/10.3233/jifs-222569)               |
| 2023    | [MedVQA-2023-001](./Paper_Notes/Survey/2023/MedVQA-2023-001_SV_CBTMMVQA.md) · A Critical Analysis of Benchmarks, Techniques, and Models in Medical Visual Question Answering | [DOI](https://doi.org/10.1109/access.2023.3335216)       |

<a id="datasets-open-access"></a>

<a id="section-2"></a>

# 2. Datasets & Data Resources

<a id="section-2.1"></a>

## 2.1. General Medical VQA Datasets

| Date    | Title                                                        | DOI                                                   |
| ------- | ------------------------------------------------------------ | ----------------------------------------------------- |
| 2024-12 | [MedVQA-2024-074](./Paper_Notes/Dataset/2024/MedVQA-2024-074_DS_PMC-VQA.md) · Development of a large-scale medical visual question-answering dataset | [DOI](https://doi.org/10.1038/s43856-024-00709-2)     |
| 2022-07 | [MedVQA-2022-006](./Paper_Notes/Dataset/2022/MedVQA-2022-006_DS_OVQA.md) · OVQA A Clinically Generated Visual Question Answering Dataset | [DOI](https://doi.org/10.1145/3477495.3531724)        |
| 2021-04 | [MedVQA-2021-002](./Paper_Notes/Dataset/2021/MedVQA-2021-002_DS_SLAKE.md) · Slake: A Semantically-Labeled Knowledge-Enhanced Dataset For Medical Visual Question Answering | [DOI](https://doi.org/10.1109/isbi48211.2021.9434010) |

<a id="section-2.2"></a>

## 2.2. Image–Text Pretraining & Instruction Data

| Date    | Title                                                        | DOI                                                    |
| ------- | ------------------------------------------------------------ | ------------------------------------------------------ |
| 2026-04 | [MedVQA-2024-073](./Paper_Notes/Dataset/2025/MedVQA-2024-073_DS_MedMax.md) · MedMax: Mixed-Modal Instruction Tuning for Training Biomedical Assistants | [DOI](https://doi.org/10.52202/085713-3588)            |
| 2025-06 | [MedVQA-2025-055](./Paper_Notes/Dataset/2025/MedVQA-2025-055_DS_BIOMEDICA.md) · BIOMEDICA: An Open Biomedical Image-Caption Archive, Dataset, and Vision-Language Models Derived from Scientific Literature | [DOI](https://doi.org/10.1109/cvpr52734.2025.01837)    |
| 2024-11 | [MedVQA-2024-010](./Paper_Notes/Dataset/2024/MedVQA-2024-010_DS_PubMedVision.md) · Towards Injecting Medical Visual Knowledge into Multimodal LLMs at Scale | [DOI](https://doi.org/10.18653/v1/2024.emnlp-main.418) |

<a id="section-2.3"></a>

## 2.3. Radiology & Volumetric Imaging

| Date    | Title                                                        | DOI                                                          |
| ------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2026-09 | [MedVQA-2026-059](./Paper_Notes/Dataset/2026/MedVQA-2026-059_DS_SpineXR-VQA.md) · SpineXR-VQA: A Clinically-Validated Visual Question Answering Dataset for Spine X-Rays | [DOI](https://doi.org/10.1145/3820903)                       |
| 2026-06 | [MedVQA-2026-042](./Paper_Notes/Dataset/2026/MedVQA-2026-042_DS_GIV-CXR.md) · GIV-CXR: Densely Grounded, Visually Interpretable Chest X-ray Question Answering Dataset | [CVPR](https://openaccess.thecvf.com/content/CVPR2026W/Med-Reasoner/html/Bavana_GIV-CXR_Densely_Grounded_Visually_Interpretable_Chest_X-ray_Question_Answering_Dataset_CVPRW_2026_paper.html) |
| 2026-06 | [MedVQA-2026-045](./Paper_Notes/Dataset/2026/MedVQA-2026-045_DS_MIMIC-CXR-VQA.md) · MIMIC-CXR-VQA: A Large-Scale LLM-Annotated Dataset and Comparative Benchmark for Medical Visual Question Answering | [CVPR](https://openaccess.thecvf.com/content/CVPR2026W/CV4Clinic2026/html/Aas-Alas_MIMIC-CXR-VQA_A_Large-Scale_LLM-Annotated_Dataset_and_Comparative_Benchmark_for_Medical_CVPRW_2026_paper.html) |
| 2026-05 | [MedVQA-2025-121](./Paper_Notes/Dataset/2026/MedVQA-2025-121_DS_RadImageNet-VQA.md) · RadImageNet-VQA: A Large-Scale CT and MRI Dataset for Radiologic Visual Question Answering | [DOI](https://proceedings.mlr.press/v315/butsanets26a.html)  |
| 2026    | [MedVQA-2026-027](./Paper_Notes/Dataset/2026/MedVQA-2026-027_DS_MIMIC-Ext-CXR-QBA.md) · A Structured, Tagged, and Localized Visual Question Answering Dataset with Full Sentence Answers and Scene Graphs for Chest X-ray Images | [DOI](https://proceedings.iclr.cc/paper_files/paper/2026/hash/6de71272e0be559af3f76b884e94794b-Abstract-Conference.html) |
| 2025-11 | [MedVQA-2025-104](./Paper_Notes/Dataset/2025/MedVQA-2025-104_DS_VinDr-CXR-VQA.md) · VinDr-CXR-VQA: A Visual Question Answering Dataset for Explainable Chest X-Ray Analysis with Multi-Task Learning | [DOI](https://doi.org/10.48550/arXiv.2511.00504)             |
| 2025-10 | [MedVQA-2025-063](./Paper_Notes/Dataset/2025/MedVQA-2025-063_DS_GEMeX-RMCoT.md) · GEMeX-RMCoT: An Enhanced Med-VQA Dataset for Region-Aware Multimodal Chain-of-Thought Reasoning | [DOI](https://doi.org/10.1145/3746027.3758277)               |
| 2025-10 | [MedVQA-2025-093](./Paper_Notes/Dataset/2025/MedVQA-2025-093_DS_RadGenome-Chest-CT.md) · Development of a large-scale grounded vision language dataset for chest CT analysis | [DOI](https://doi.org/10.1038/s41597-025-05922-9)            |
| 2023-10 | [MedVQA-2023-027](./Paper_Notes/Dataset/2023/MedVQA-2023-027_DS_RIS-VQA.md) · Localized Questions in Medical Visual Question Answering | [DOI](https://doi.org/10.1007/978-3-031-43895-0_34)          |
| 2018-11 | [MedVQA-2018-002](./Paper_Notes/Dataset/2018/MedVQA-2018-002_DS_VQA-RAD.md) · A dataset of clinically generated visual questions and answers about radiology images | [DOI](https://doi.org/10.1038/sdata.2018.251)                |

<a id="section-2.4"></a>

## 2.4. Pathology & Whole-Slide Imaging

| Date    | Title                                                        | DOI接                                                 |
| ------- | ------------------------------------------------------------ | ----------------------------------------------------- |
| 2024-07 | [MedVQA-2024-041](./Paper_Notes/Dataset/2024/MedVQA-2024-041_DS_TM-PATHVQA.md) · TM-PATHVQA: 90000+ Textless Multilingual Questions for Medical Visual Question Answering | [DOI](https://doi.org/10.21437/Interspeech.2024-1036) |
| 2021-08 | [MedVQA-2021-001](./Paper_Notes/Dataset/2021/MedVQA-2021-001_DS_PathVQA.md) · Towards Visual Question Answering on Pathology Images | [DOI](https://doi.org/10.18653/v1/2021.acl-short.90)  |

<a id="section-2.5"></a>

## 2.5. Endoscopy, Surgery & Medical Video

| Date    | Title                                                        | DOI                                                |
| ------- | ------------------------------------------------------------ | -------------------------------------------------- |
| 2025-10 | [MedVQA-2025-059](./Paper_Notes/Dataset/2026/MedVQA-2025-059_DS_Kvasir-VQA-x1.md) · Kvasir-VQA-x1:A Multimodal Dataset for Medical Reasoning and Robust MedVQA in Gastrointestinal Endoscopy | [DOI](https://doi.org/10.1007/978-3-032-08009-7_6) |
| 2024-10 | [MedVQA-2024-064](./Paper_Notes/Dataset/2024/MedVQA-2024-064_DS_Kvasir-VQA.md) · Kvasir-VQA: A Text-Image Pair GI Tract Dataset | [DOI](https://doi.org/10.1145/3689096.3689458)     |
| 2023-03 | [MedVQA-2023-013](./Paper_Notes/Dataset/2023/MedVQA-2023-013_DS_MedVidQA.md) · A dataset for medical instructional video classification and question answering | [DOI](https://doi.org/10.1038/s41597-023-02036-y)  |

<a id="section-2.6"></a>

## 2.6. Other Specialties, Education & Dialogue

| Date    | Title                                                        | DOI                                                 |
| ------- | ------------------------------------------------------------ | --------------------------------------------------- |
| 2026    | [MedVQA-2026-003](./Paper_Notes/Dataset/2026/MedVQA-2026-003_DS_MaxVQA.md) · MaxVQA: A Large-Scale Multi-Source Dataset for Explanatory Visual Question Answering in Mammography | [DOI](https://doi.org/10.1109/jbhi.2026.3736729)    |
| 2025-12 | [MedVQA-2025-122](./Paper_Notes/Dataset/2025/MedVQA-2025-122_DS_DermaVQA-DAS.md) · DermaVQA-DAS: Dermatology Assessment Schema (DAS) & Datasets for Closed-Ended Question Answering & Segmentation in Patient-Generated Dermatology Images | [DOI](https://doi.org/10.48550/arXiv.2512.24340)    |
| 2025-08 | [MedVQA-2025-078](./Paper_Notes/Dataset/2025/MedVQA-2025-078_DS_WoundcareVQA.md) · WoundcareVQA: A multilingual visual question answering benchmark dataset for wound care | [DOI](https://doi.org/10.1016/j.jbi.2025.104888)    |
| 2025-06 | [MedVQA-2025-061](./Paper_Notes/Dataset/2025/MedVQA-2025-061_DS_MMMED.md) · A Multilingual Multimodal Medical Examination Dataset for Visual Question Answering in Healthcare | [DOI](https://doi.org/10.1109/cbms65348.2025.00093) |
| 2024-10 | [MedVQA-2024-057](./Paper_Notes/Dataset/2024/MedVQA-2024-057_DS_DermaVQA.md) · DermaVQA: A Multilingual Visual Question Answering Dataset for Dermatology | [DOI](https://doi.org/10.1007/978-3-031-72086-4_20) |
| 2020-07 | [MedVQA-2020-002](./Paper_Notes/Dataset/2020/MedVQA-2020-002_DS_RadVisDial.md) · Towards Visual Dialog for Radiology | [DOI](https://doi.org/10.18653/v1/2020.bionlp-1.6)  |

<a id="17-benchmark-pending"></a>

<a id="section-3"></a>

# 3. Benchmarks & Evaluation

<a id="section-3.1"></a>

## 3.1. Benchmark Resources & Shared Tasks

| Date    | Title                                                        | DOI                                                          |
| ------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2026-09 | [MedVQA-2026-035](./Paper_Notes/Benchmark/2027/MedVQA-2026-035_BM_CT-SpatialVQA.md) · Lost in Volume: The CT-SpatialVQA Benchmark for Evaluating Semantic-Spatial Understanding of 3D Medical Vision–Language Models | [DOI](https://doi.org/10.1007/978-3-032-38470-6_16)          |
| 2026-09 | [MedVQA-2026-065](./Paper_Notes/Benchmark/2026/MedVQA-2026-065_BM_RoboSurg-VQA.md) · RoboSurg-VQA: A Multimodal Visual Question Answering Benchmark Derived from Surgical Segmentation Data | [DOI](https://doi.org/10.3390/make8100300)                   |
| 2026-07 | [MedVQA-2026-053](./Paper_Notes/Benchmark/2026/MedVQA-2026-053_BM_OmniPathoVQA.md) · OmniPathoVQA: Benchmarking pathology vision–language models with Encyclopedia-scale knowledge | [DOI](https://doi.org/10.1016/j.media.2026.104196)           |
| 2026-06 | [MedVQA-2025-108](./Paper_Notes/Benchmark/2026/MedVQA-2025-108_BM_Med-CMR.md) · Med-CMR: A Fine-Grained Benchmark Integrating Visual Evidence and Clinical Logic for Medical Complex Multimodal Reasoning | [CVPR](https://openaccess.thecvf.com/content/CVPR2026/html/Gong_Med-CMR_A_Fine-Grained_Benchmark_Integrating_Visual_Evidence_and_Clinical_Logic_CVPR_2026_paper.html) |
| 2026-04 | [MedVQA-2025-058](./Paper_Notes/Benchmark/2025/MedVQA-2025-058_BM_3D-RAD.md) · 3D-RAD: A Comprehensive 3D Radiology Med-VQA Dataset with Multi-Temporal Analysis and Diverse Diagnostic Tasks | [DOI](https://doi.org/10.52202/085713-5656)                  |
| 2026-03 | [MedVQA-2025-074](./Paper_Notes/Benchmark/2026/MedVQA-2025-074_BM_MultiMedBench.md) · MultiMedBench: A Scenario-Aware Benchmark for Evaluating Knowledge Editing in Medical VQA | [DOI](https://doi.org/10.1609/aaai.v40i40.40679)             |
| 2026-03 | [MedVQA-2026-020](./Paper_Notes/Benchmark/2026/MedVQA-2026-020_BM_SurgPub-Video.md) · SurgPub-Video: A Comprehensive Surgical Video Framework for Enhanced Surgical Intelligence in Vision-Language Model | [DOI](https://doi.org/10.1609/aaai.v40i8.37593)              |
| 2025-12 | [MedVQA-2025-054](./Paper_Notes/Benchmark/2026/MedVQA-2025-054_BM_ReXVQA.md) · ReXVQA: A Large-scale Visual Question Answering Benchmark for Generalist Chest X-ray Understanding | [DOI](https://doi.org/10.1142/9789819824755_0018)            |
| 2025-11 | [MedVQA-2025-106](./Paper_Notes/Benchmark/2025/MedVQA-2025-106_BM_MammoVQA.md) · A Benchmark for Breast Cancer Screening and Diagnosis in Mammogram Visual Question Answering | [DOI](https://doi.org/10.1038/s41467-025-66507-z)            |
| 2025-10 | [MedVQA-2024-067](./Paper_Notes/Benchmark/2025/MedVQA-2024-067_BM_GEMeX.md) · GEMeX: A Large-Scale, Groundable, and Explainable Medical VQA Benchmark for Chest X-Ray Diagnosis | [DOI](https://doi.org/10.1109/iccv51701.2025.01979)          |
| 2025-09 | [MedVQA-2025-026](./Paper_Notes/Benchmark/2026/MedVQA-2025-026_BM_FunBench.md) · FunBench: Benchmarking Fundus Reading Skills of MLLMs | [DOI](https://doi.org/10.1007/978-3-032-04978-0_27)          |
| 2025-09 | [MedVQA-2025-042](./Paper_Notes/Benchmark/2025/MedVQA-2025-042_BM_HEAL-MedVQA.md) · Localizing Before Answering: A Benchmark for Grounded Medical Visual Question Answering | [DOI](https://doi.org/10.24963/ijcai.2025/853)               |
| 2025-07 | [MedVQA-2025-008](./Paper_Notes/Benchmark/2025/MedVQA-2025-008_BM_MMXU.md) · MMXU: A Multi-Modal and Multi-X-ray Understanding Dataset for Disease Progression | [DOI](https://doi.org/10.18653/v1/2025.findings-acl.508)     |
| 2025-05 | [MedVQA-2025-047](./Paper_Notes/Benchmark/2025/MedVQA-2025-047_BM_MedFrameQA.md) · MedFrameQA: A Multi-Image Medical VQA Benchmark for Clinical Reasoning | [DOI](https://doi.org/10.18653/2026.emnlp-main.2482)         |
| 2025    | [MedVQA-2025-004](./Paper_Notes/Benchmark/2025/MedVQA-2025-004_BM_EndoBench.md) · EndoBench: A Comprehensive Evaluation of Multi-Modal Large Language Models for Endoscopy Analysis | [DOI](https://doi.org/10.52202/085713-0076)                  |
| 2024-12 | [MedVQA-2024-033](./Paper_Notes/Benchmark/2024/MedVQA-2024-033_BM_CARES.md) · CARES: A Comprehensive Benchmark of Trustworthiness in Medical Vision Language Models | [DOI](https://doi.org/10.52202/079017-4455)                  |
| 2024-12 | [MedVQA-2024-044](./Paper_Notes/Benchmark/2024/MedVQA-2024-044_BM_GMAI-MMBench.md) · GMAI-MMBench: A Comprehensive Multimodal Evaluation Benchmark Towards General Medical AI | [DOI](https://doi.org/10.52202/079017-2992)                  |
| 2024-06 | [MedVQA-2024-014](./Paper_Notes/Benchmark/2024/MedVQA-2024-014_BM_OmniMedVQA.md) · OmniMedVQA: A New Large-Scale Comprehensive Evaluation Benchmark for Medical LVLM | [DOI](https://doi.org/10.1109/cvpr52733.2024.02093)          |
| 2024-03 | [MedVQA-2024-022](./Paper_Notes/Benchmark/2024/MedVQA-2024-022_BM_M3D-Bench.md) · M3D: Advancing 3D Medical Image Analysis with Multi-Modal Large Language Models | [DOI](https://doi.org/10.48550/arXiv.2404.00578)             |
| 2024    | [MedVQA-2024-001](./Paper_Notes/Benchmark/2024/MedVQA-2024-001_BM_FEDMEKI.md) · FEDMEKI: A Benchmark for Scaling Medical Foundation Models via Federated Knowledge Injection | [DOI](https://doi.org/10.52202/079017-0033)                  |
| 2023-12 | [MedVQA-2023-044](./Paper_Notes/Benchmark/2023/MedVQA-2023-044_BM_EHRXQA.md) · EHRXQA: A Multi-Modal Question Answering Dataset for Electronic Health Records with Chest X-ray Images | [DOI](https://doi.org/10.52202/075280-0170)                  |
| 2023-10 | [MedVQA-2023-041](./Paper_Notes/Benchmark/2023/MedVQA-2023-041_BM_MedVQA-GI.md) · Overview of ImageCLEFmedical 2023 – Medical Visual Question Answering for Gastrointestinal Tract | [DOI](https://ceur-ws.org/Vol-3497/paper-107.pdf)            |
| 2021-08 | [MedVQA-2021-007](./Paper_Notes/Benchmark/2021/MedVQA-2021-007_BM_ImageCLEF-VQA-Med-2021.md) · Overview of the VQA-Med Task at ImageCLEF 2021: Visual Question Answering and Generation in the Medical Domain | [DOI](https://ceur-ws.org/Vol-2936/paper-87.pdf)             |
| 2020-10 | [MedVQA-2020-005](./Paper_Notes/Benchmark/2020/MedVQA-2020-005_BM_ImageCLEF-VQA-Med-2020.md) · Overview of the VQA-Med Task at ImageCLEF 2020: Visual Question Answering and Generation in the Medical Domain | [DOI](https://ceur-ws.org/Vol-2696/paper_106.pdf)            |
| 2019-07 | [MedVQA-2019-001](./Paper_Notes/Benchmark/2019/MedVQA-2019-001_BM_ImageCLEF-VQA-Med-2019.md) · VQA-Med: Overview of the Medical Visual Question Answering Task at ImageCLEF 2019 | [DOI](https://ceur-ws.org/Vol-2380/paper_272.pdf)            |
| 2018-07 | [MedVQA-2018-001](./Paper_Notes/Benchmark/2018/MedVQA-2018-001_BM_ImageCLEF-VQA-Med-2018.md) · Overview of ImageCLEF 2018 Medical Domain Visual Question Answering Task | [DOI](https://ceur-ws.org/Vol-2125/paper_212.pdf)            |

<a id="section-3.2"></a>

## 3.2. Capability & Comparative Studies

| Date    | Title                                                        | DOI                                                      |
| ------- | ------------------------------------------------------------ | -------------------------------------------------------- |
| 2026-08 | [MedVQA-2026-066](./Paper_Notes/Benchmark/2026/MedVQA-2026-066_BM_CAF-RAG.md) · When does retrieval help medical question answering? A question-type sensitivity analysis and failure taxonomy for text-based (image-free) medical RAG, with an interpretable clinical filter (CAF-RAG) | [DOI](https://doi.org/10.1016/j.imu.2026.101810)         |
| 2026-02 | [MedVQA-2026-014](./Paper_Notes/Benchmark/2026/MedVQA-2026-014_BM_OphthalWeChat.md) · Benchmarking large multimodal models for ophthalmic visual question answering with OphthalWeChat | [DOI](https://doi.org/10.1016/j.aopr.2025.10.006)        |
| 2025-12 | [MedVQA-2025-110](./Paper_Notes/Benchmark/2026/MedVQA-2025-110_BM_LoRA-vs-AdaLoRA.md) · Optimizing multimodal models for medical visual question answering: A comparative study of LoRA and AdaLoRA on VQA-RAD and SLAKE-VQA | [DOI](https://doi.org/10.1016/j.compbiomed.2025.111397)  |
| 2025-12 | [MedVQA-2025-111](./Paper_Notes/Benchmark/2025/MedVQA-2025-111_BM_RoM-VQA.md) · Advancing Reliable Medical VQA: Evaluation and Enhancement of Model Robustness | [DOI](https://doi.org/10.1109/bibm66473.2025.11356296)   |
| 2025-07 | [MedVQA-2025-012](./Paper_Notes/Benchmark/2025/MedVQA-2025-012_BM_ProbMed.md) · Worse than Random? An Embarrassingly Simple Probing Evaluation of Large Multimodal Models in Medical VQA | [DOI](https://doi.org/10.18653/v1/2025.findings-acl.981) |
| 2024-05 | [MedVQA-2024-032](./Paper_Notes/Benchmark/2024/MedVQA-2024-032_BM_Ophthalmic-GPT-4V.md) · Unveiling the clinical incapabilities: a benchmarking study of GPT-4V(ision) for ophthalmic multimodal image analysis | [DOI](https://doi.org/10.1136/bjo-2023-325054)           |

<a id="section-3.3"></a>

## 3.3. Reliability & Evaluation Protocols

| Date    | Title                                                        | DOI                                                          |
| ------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2026-06 | [MedVQA-2026-047](./Paper_Notes/Benchmark/2026/MedVQA-2026-047_BM_Schema-Metadata.md) · Schema Affects Evaluation Conclusions: Metadata Context in Medical VLM Benchmarks | [DOI](https://openaccess.thecvf.com/content/CVPR2026W/DataCV/html/Jarquin_Schema_Affects_Evaluation_Conclusions_Metadata_Context_in_Medical_VLM_Benchmarks_CVPRW_2026_paper.html) |
| 2025-09 | [MedVQA-2025-084](./Paper_Notes/Benchmark/2026/MedVQA-2025-084_BM_MS-FBI.md) · Confidence Calibration for Multimodal LLMs: An Empirical Study Through Medical VQA | [DOI](https://doi.org/10.1007/978-3-032-04978-0_9)           |
| 2025-05 | [MedVQA-2024-054](./Paper_Notes/Benchmark/2025/MedVQA-2024-054_BM_MediConfusion.md) · MediConfusion: Can you trust your AI radiologist? Probing the reliability of multimodal medical foundation models. | [DOI](https://proceedings.iclr.cc/paper_files/paper/2025/hash/b37c2e26b75ee02fcabd65a2a0367136-Abstract-Conference.html) |
| 2024-08 | [MedVQA-2024-047](./Paper_Notes/Benchmark/2024/MedVQA-2024-047_BM_BESTMVQA.md) · BESTMVQA: A Benchmark Evaluation System for Medical Visual Question Answering | [DOI](https://doi.org/10.1007/978-3-031-70378-2_27)          |
| 2023-07 | [MedVQA-2023-026](./Paper_Notes/Benchmark/2023/MedVQA-2023-026_BM_Adaptive-VTT-DME.md) · A reinforcement learning approach for VQA validation: An application to diabetic macular edema grading | [DOI](https://doi.org/10.1016/j.media.2023.102822)           |

<a id="section-4"></a>

# 4. Foundation Models & Reusable Backbones

<a id="section-4.1"></a>

## 4.1. Reusable Visual & Vision-Language Encoders

| Date    | Title                                                        | DOI                                                      |
| ------- | ------------------------------------------------------------ | -------------------------------------------------------- |
| 2026-01 | [MedVQA-2026-006](./Paper_Notes/Foundation/2026/MedVQA-2026-006_FM_CMES2LIP.md) · Convolutional masked encoder and contrastive learning for small-scale medical language-image pre-training | [DOI](https://doi.org/10.1016/j.bspc.2025.108308)        |
| 2025-12 | [MedVQA-2025-113](./Paper_Notes/Foundation/2025/MedVQA-2025-113_FM_Med-GLIP.md) · Med-GLIP: Advancing Medical Language-Image Pre-Training with Large-Scale Grounded Dataset | [DOI](https://doi.org/10.1109/bibm66473.2025.11357141)   |
| 2025-12 | [MedVQA-2025-118](./Paper_Notes/Foundation/2025/MedVQA-2025-118_FM_MBVLP.md) · MLP-Based Vision Language Pre-Training for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/bibm66473.2025.11356107)   |
| 2025-10 | [MedVQA-2025-099](./Paper_Notes/Foundation/2025/MedVQA-2025-099_FM_MVMAE.md) · Medical Vision-Language Pre-training with Multimodal Variational Masked Autoencoder for Robust Medical VQA | [DOI](https://doi.org/10.1145/3746027.3755273)           |
| 2025-09 | [MedVQA-2025-081](./Paper_Notes/Foundation/2026/MedVQA-2025-081_FM_GPFM.md) · A generalizable pathology foundation model using a unified knowledge distillation pretraining framework | [DOI](https://doi.org/10.1038/s41551-025-01488-4)        |
| 2025-09 | [MedVQA-2025-082](./Paper_Notes/Foundation/2025/MedVQA-2025-082_FM_MedKI.md) · MedKI: Knowledge Dual Injections for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/icip55913.2025.11084480)   |
| 2025-06 | [MedVQA-2025-050](./Paper_Notes/Foundation/2025/MedVQA-2025-050_FM_AMiF.md) · Alignment, Mining and Fusion: Representation Alignment with Hard Negative Mining and Selective Knowledge Fusion for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/cvpr52734.2025.02758)      |
| 2025-06 | [MedVQA-2025-053](./Paper_Notes/Foundation/2025/MedVQA-2025-053_FM_MVCM.md) · MVCM: Enhancing Multi-View and Cross-Modality Alignment for Medical Visual Question Answering and Medical Image-Text Retrieval | [DOI](https://doi.org/10.1109/cvprw67362.2025.00023)     |
| 2025-06 | [MedVQA-2025-067](./Paper_Notes/Foundation/2025/MedVQA-2025-067_FM_USCL.md) · Unimodality-Supervised Contrastive Learning and Inference Enhancement Method for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/ijcnn64981.2025.11228617)  |
| 2025-02 | [MedVQA-2025-022](./Paper_Notes/Foundation/2025/MedVQA-2025-022_FM_3D-MRI-VLM.md) · Leveraging a Vision-Language Model with Natural Text Supervision for MRI Retrieval, Captioning, Classification, and Visual Question Answering | [DOI](https://doi.org/10.1101/2025.02.15.638446)         |
| 2025-01 | [MedVQA-2022-022](./Paper_Notes/Foundation/2025/MedVQA-2022-022_FM_UnICLAM.md) · UnICLAM: Contrastive representation learning with adversarial masking for unified and interpretable Medical Vision Question Answering | [DOI](https://doi.org/10.1016/j.media.2025.103464)       |
| 2025-01 | [MedVQA-2025-014](./Paper_Notes/Foundation/2025/MedVQA-2025-014_FM_BiomedCLIP.md) · A Multimodal Biomedical Foundation Model Trained from Fifteen Million Image–Text Pairs | [DOI](https://doi.org/10.1056/aioa2400640)               |
| 2025-01 | [MedVQA-2025-017](./Paper_Notes/Foundation/2025/MedVQA-2025-017_FM_MUSK.md) · A vision–language foundation model for precision oncology | [DOI](https://doi.org/10.1038/s41586-024-08378-w)        |
| 2024-11 | [MedVQA-2024-066](./Paper_Notes/Foundation/2024/MedVQA-2024-066_FM_CMMO.md) · Cross-Modal self-supervised vision language pre-training with multiple objectives for medical visual question answering | [DOI](https://doi.org/10.1016/j.jbi.2024.104748)         |
| 2024-10 | [MedVQA-2024-056](./Paper_Notes/Foundation/2024/MedVQA-2024-056_FM_DFMD.md) · Deep Fuzzy Multiteacher Distillation Network for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/tfuzz.2024.3402086)        |
| 2024-04 | [MedVQA-2024-025](./Paper_Notes/Foundation/2024/MedVQA-2024-025_FM_CMCD.md) · Medical Vision-Language Representation Learning with Cross-Modal Multi-Teacher Contrastive Distillation | [DOI](https://doi.org/10.1109/icassp48485.2024.10447344) |
| 2024-03 | [MedVQA-2024-017](./Paper_Notes/Foundation/2024/MedVQA-2024-017_FM_MITER.md) · MITER: Medical Image–TExt joint adaptive pretRaining with multi-level contrastive learning | [DOI](https://doi.org/10.1016/j.eswa.2023.121526)        |
| 2024-02 | [MedVQA-2024-016](./Paper_Notes/Foundation/2024/MedVQA-2024-016_FM_Diffusion-Visual-Encoder.md) · Diffusion-based Visual Representation Learning for Medical Question Answering | [DOI](https://proceedings.mlr.press/v222/bian24a.html)   |
| 2024-01 | [MedVQA-2024-012](./Paper_Notes/Foundation/2024/MedVQA-2024-012_FM_M3AE.md) · Mapping medical image-text to a joint space via masked modeling | [DOI](https://doi.org/10.1016/j.media.2023.103018)       |
| 2024    | [MedVQA-2023-049](./Paper_Notes/Foundation/2024/MedVQA-2023-049_FM_UniDCP.md) · UniDCP: Unifying Multiple Medical Vision-Language Tasks via Dynamic Cross-Modal Learnable Prompts | [DOI](https://doi.org/10.1109/tmm.2024.3397191)          |
| 2023-12 | [MedVQA-2023-046](./Paper_Notes/Foundation/2023/MedVQA-2023-046_FM_WSRP.md) · A Weak Supervision-based Robust Pretraining Method for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/bibm58861.2023.10385332)   |
| 2023-10 | [MedVQA-2023-011](./Paper_Notes/Foundation/2023/MedVQA-2023-011_FM_PMC-CLIP.md) · PMC-CLIP: Contrastive Language-Image Pre-training Using Biomedical Documents | [DOI](https://doi.org/10.1007/978-3-031-43993-3_51)      |
| 2023-10 | [MedVQA-2023-030](./Paper_Notes/Foundation/2023/MedVQA-2023-030_FM_MUMC.md) · Masked Vision and Language Pre-training with Unimodal and Multimodal Contrastive Losses for Medical Visual Question Answering | [DOI](https://doi.org/10.1007/978-3-031-43907-0_36)      |
| 2023-05 | [MedVQA-2023-004](./Paper_Notes/Foundation/2023/MedVQA-2023-004_FM_PubMedCLIP.md) · PubMedCLIP: How Much Does CLIP Benefit Visual Question Answering in the Medical Domain? | [DOI](https://doi.org/10.18653/v1/2023.findings-eacl.88) |
| 2023-05 | [MedVQA-2023-019](./Paper_Notes/Foundation/2023/MedVQA-2023-019_FM_MM-VQA.md) · Contrastive training of a multimodal encoder for medical visual question answering | [DOI](https://doi.org/10.1016/j.iswa.2023.200221)        |
| 2023-04 | [MedVQA-2023-018](./Paper_Notes/Foundation/2023/MedVQA-2023-018_FM_M2I2.md) · Self-Supervised Vision-Language Pretraining for Medial Visual Question Answering | [DOI](https://doi.org/10.1109/isbi53787.2023.10230743)   |
| 2022-12 | [MedVQA-2022-001](./Paper_Notes/Foundation/2022/MedVQA-2022-001_FM_MedCLIP.md) · MedCLIP: Contrastive Learning from Unpaired Medical Images and Text | [DOI](https://doi.org/10.18653/v1/2022.emnlp-main.256)   |
| 2022-10 | [MedVQA-2022-014](./Paper_Notes/Foundation/2022/MedVQA-2022-014_FM_ARL.md) · Align, Reason and Learn: Enhancing Medical Vision-and-Language Pre-training with Knowledge | [DOI](https://doi.org/10.1145/3503161.3547948)           |
| 2022-09 | [MedVQA-2022-010](./Paper_Notes/Foundation/2022/MedVQA-2022-010_FM_M3AE.md) · Multi-modal Masked Autoencoders for Medical Vision-and-Language Pre-training | [DOI](https://doi.org/10.1007/978-3-031-16443-9_65)      |
| 2021-09 | [MedVQA-2021-008](./Paper_Notes/Foundation/2021/MedVQA-2021-008_FM_CPRD.md) · Contrastive Pre-training and Representation Distillation for Medical Visual Question Answering Based on Radiology Images | [DOI](https://doi.org/10.1007/978-3-030-87196-3_20)      |
| 2021-04 | [MedVQA-2021-004](./Paper_Notes/Foundation/2021/MedVQA-2021-004_FM_MMBERT.md) · MMBERT: Multimodal BERT Pretraining for Improved Medical VQA | [DOI](https://doi.org/10.1109/isbi48211.2021.9434063)    |

<a id="section-4.2"></a>

## 4.2. Generalist Biomedical Vision-Language Models

| Date    | Title                                                        | DOI                                                        |
| ------- | ------------------------------------------------------------ | ---------------------------------------------------------- |
| 2026-06 | [MedVQA-2026-043](./Paper_Notes/Foundation/2026/MedVQA-2026-043_FM_Med-R1.md) · Med-R1: Reinforcement Learning for Generalizable Medical Reasoning in Vision-Language Models | [DOI](https://doi.org/10.1109/tmi.2026.3661001)            |
| 2026-05 | [MedVQA-2026-034](./Paper_Notes/Foundation/2026/MedVQA-2026-034_FM_LLaMA32-Med.md) · LLaMA32-Med: Parameter-Efficient Adaptation of Multimodal LLMs for Medical Visual Question Answering | [DOI](https://proceedings.mlr.press/v315/dong26a.html)     |
| 2025-12 | [MedVQA-2025-119](./Paper_Notes/Foundation/2025/MedVQA-2025-119_FM_MSFormer.md) · Multi-Scale Visual Prompting for Robust Visual Question Answering in Medical Imaging | [DOI](https://doi.org/10.1109/bibm66473.2025.11356041)     |
| 2025-10 | [MedVQA-2025-020](./Paper_Notes/Foundation/2025/MedVQA-2025-020_FM_HealthGPT.md) · HealthGPT: A Medical Large Vision-Language Model for Unifying Comprehension and Generation via Heterogeneous Knowledge Adaptation | [DOI](https://proceedings.mlr.press/v267/lin25n.html)      |
| 2025-09 | [MedVQA-2025-089](./Paper_Notes/Foundation/2026/MedVQA-2025-089_FM_Med-MIM.md) · Medical Large Vision Language Models with Multi-image Visual Ability | [DOI](https://doi.org/10.1007/978-3-032-04971-1_38)        |
| 2025-08 | [MedVQA-2025-075](./Paper_Notes/Foundation/2025/MedVQA-2025-075_FM_Cliva-Med.md) · Cliva-Med: A Lightweight Vision-Language Model for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/prai67447.2025.11412636)     |
| 2025-07 | [MedVQA-2025-068](./Paper_Notes/Foundation/2025/MedVQA-2025-068_FM_SigPhi-Med.md) · SigPhi-Med: A lightweight vision-language assistant for biomedicine | [DOI](https://doi.org/10.1016/j.jbi.2025.104849)           |
| 2025-06 | [MedVQA-2025-057](./Paper_Notes/Foundation/2025/MedVQA-2025-057_FM_VILA-M3.md) · VILA-M3: Enhancing Vision-Language Models with Medical Expert Knowledge | [DOI](https://doi.org/10.1109/cvpr52734.2025.01378)        |
| 2025-06 | [MedVQA-2025-064](./Paper_Notes/Foundation/2025/MedVQA-2025-064_FM_MedVL-DPDE.md) · Effective Medical Visual Question Answering Using Dynamic Prompting and Decoding Knowledge Editing | [DOI](https://doi.org/10.1007/s41019-025-00291-0)          |
| 2024-11 | [MedVQA-2024-004](./Paper_Notes/Foundation/2024/MedVQA-2024-004_FM_Med-MoE.md) · Med-MoE: Mixture of Domain-Specific Experts for Lightweight Medical Vision-Language Models | [DOI](https://doi.org/10.18653/v1/2024.findings-emnlp.221) |
| 2024-09 | [MedVQA-2024-053](./Paper_Notes/Foundation/2024/MedVQA-2024-053_FM_MISS.md) · MISS: A Generative Pre-training and Fine-Tuning Approach for Med-VQA | [DOI](https://doi.org/10.1007/978-3-031-72353-7_22)        |
| 2024-08 | [MedVQA-2023-023](./Paper_Notes/Foundation/2024/MedVQA-2023-023_FM_BiomedGPT.md) · A generalist vision–language foundation model for diverse biomedical tasks | [DOI](https://doi.org/10.1038/s41591-024-03185-2)          |
| 2024-08 | [MedVQA-2024-006](./Paper_Notes/Foundation/2024/MedVQA-2024-006_FM_MLeVLM.md) · MLeVLM: Improve Multi-level Progressive Capabilities based on Multimodal Large Language Model for Medical Visual Question Answering | [DOI](https://doi.org/10.18653/v1/2024.findings-acl.296)   |
| 2024-08 | [MedVQA-2024-008](./Paper_Notes/Foundation/2024/MedVQA-2024-008_FM_MMCAP.md) · Multi-modal Concept Alignment Pre-training for Generative Medical Visual Question Answering | [DOI](https://doi.org/10.18653/v1/2024.findings-acl.319)   |
| 2024-06 | [MedVQA-2024-002](./Paper_Notes/Foundation/2024/MedVQA-2024-002_FM_Domain-Adapted-VLM.md) · Fusion of Domain-Adapted Vision and Language Models for Medical Visual Question Answering | [DOI](https://doi.org/10.18653/v1/2024.clinicalnlp-1.21)   |
| 2024-02 | [MedVQA-2023-033](./Paper_Notes/Foundation/2024/MedVQA-2023-033_FM_Med-PaLM-M.md) · Towards Generalist Biomedical AI | [DOI](https://doi.org/10.1056/aioa2300138)                 |
| 2023-12 | [MedVQA-2023-034](./Paper_Notes/Foundation/2023/MedVQA-2023-034_FM_Med-Flamingo.md) · Med-Flamingo: a Multimodal Medical Few-shot Learner | [DOI](https://proceedings.mlr.press/v225/moor23a.html)     |
| 2023-10 | [MedVQA-2023-040](./Paper_Notes/Foundation/2023/MedVQA-2023-040_FM_PTUnifier.md) · Towards Unifying Medical Vision-and-Language Pre-training via Soft Prompts | [DOI](https://doi.org/10.1109/iccv51070.2023.02139)        |
| 2023    | [MedVQA-2023-024](./Paper_Notes/Foundation/2023/MedVQA-2023-024_FM_LLaVA-Med.md) · LLaVA-Med: Training a Large Language-and-Vision Assistant for Biomedicine in One Day | [DOI](https://doi.org/10.52202/075280-1240)                |

<a id="section-4.3"></a>

## 4.3. Specialty & Grounded Vision-Language Models

| Date    | Title                                                        | DOI                                                          |
| ------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2026-05 | [MedVQA-2023-045](./Paper_Notes/Foundation/2026/MedVQA-2023-045_FM_RaDialog.md) · RaDialog: Large Vision-Language Models for X-Ray Reporting and Dialog-Driven Assistance | [DOI](https://proceedings.mlr.press/v301/pellegrini26a.html) |
| 2026-02 | [MedVQA-2026-016](./Paper_Notes/Foundation/2026/MedVQA-2026-016_FM_GK-MVLP.md) · Grounded knowledge-enhanced medical vision–language pre-training for chest X-ray | [DOI](https://doi.org/10.1016/j.bspc.2025.108416)            |
| 2025-10 | [MedVQA-2025-091](./Paper_Notes/Foundation/2025/MedVQA-2025-091_FM_M4CXR.md) · M4CXR: Exploring Multitask Potentials of Multimodal Large Language Models for Chest X-Ray Interpretation | [DOI](https://doi.org/10.1109/tnnls.2025.3587687)            |
| 2025-08 | [MedVQA-2025-018](./Paper_Notes/Foundation/2026/MedVQA-2025-018_FM_EndoChat.md) · EndoChat: Grounded multimodal large language model for endoscopic surgery | [DOI](https://doi.org/10.1016/j.media.2025.103789)           |
| 2025-06 | [MedVQA-2025-039](./Paper_Notes/Foundation/2025/MedVQA-2025-039_FM_SilVar-Med.md) · SilVar-Med: A Speech-Driven Visual Language Model for Explainable Abnormality Detection in Medical Imaging | [DOI](https://doi.org/10.1109/cvprw67362.2025.00281)         |
| 2025-06 | [MedVQA-2025-051](./Paper_Notes/Foundation/2025/MedVQA-2025-051_FM_MIMO.md) · MIMO: A medical vision language model with visual referring multimodal input and pixel grounding multimodal output | [DOI](https://doi.org/10.1109/cvpr52734.2025.02303)          |
| 2025-06 | [MedVQA-2025-056](./Paper_Notes/Foundation/2025/MedVQA-2025-056_FM_SlideChat.md) · SlideChat: A Large Vision-Language Assistant for Whole-Slide Pathology Image Understanding | [DOI](https://doi.org/10.1109/cvpr52734.2025.00484)          |
| 2025-04 | [MedVQA-2025-011](./Paper_Notes/Foundation/2025/MedVQA-2025-011_FM_VividMed.md) · VividMed: Vision Language Model with Versatile Visual Grounding for Medicine | [DOI](https://doi.org/10.18653/v1/2025.naacl-long.89)        |
| 2025-04 | [MedVQA-2025-037](./Paper_Notes/Foundation/2025/MedVQA-2025-037_FM_MedPLIB.md) · Towards a Multimodal Large Language Model with Pixel-Level Insight for Biomedicine | [DOI](https://doi.org/10.1609/aaai.v39i4.32394)              |
| 2025-04 | [MedVQA-2025-038](./Paper_Notes/Foundation/2025/MedVQA-2025-038_FM_MedXChat.md) · Medxchat: A Unified Multimodal Large Language Model Framework Towards CXRS Understanding and Generation | [DOI](https://doi.org/10.1109/isbi60581.2025.10981215)       |
| 2024-10 | [MedVQA-2024-058](./Paper_Notes/Foundation/2024/MedVQA-2024-058_FM_QFT.md) · Design as Desired: Utilizing Visual Question Answering for Multimodal Pre-training | [DOI](https://doi.org/10.1007/978-3-031-72083-3_56)          |
| 2024-07 | [MedVQA-2024-038](./Paper_Notes/Foundation/2024/MedVQA-2024-038_FM_ChatFFA.md) · ChatFFA: An ophthalmic chat system for unified vision-language understanding and question answering for fundus fluorescein angiography | [DOI](https://doi.org/10.1016/j.isci.2024.110021)            |
| 2024-06 | [MedVQA-2023-047](./Paper_Notes/Foundation/2024/MedVQA-2023-047_FM_Quilt-LLaVA.md) · Quilt-LLaVA: Visual Instruction Tuning by Extracting Localized Narratives from Open-Source Histopathology Videos | [DOI](https://doi.org/10.1109/cvpr52733.2024.01252)          |
| 2024-06 | [MedVQA-2024-034](./Paper_Notes/Foundation/2024/MedVQA-2024-034_FM_PathChat.md) · A multimodal generative AI copilot for human pathology | [DOI](https://doi.org/10.1038/s41586-024-07618-3)            |

<a id="methods-selected"></a>

<a id="section-5"></a>

# 5. Methods & Systems

<a id="section-5.1"></a>

## 5.1. Architectures & Multimodal Fusion

| Date    | Title                                                        | DOI                                                          |
| ------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2026-09 | [MedVQA-2026-063](./Paper_Notes/Method/2027/MedVQA-2026-063_MD_Proto-CAP.md) · Proto-CAP: Prototype Memory Fusion and Curriculum-Adaptive Loss for Pediatric Myopia Visual Question Answering | [DOI](https://doi.org/10.1007/978-3-032-38059-3_43)          |
| 2026-07 | [MedVQA-2026-050](./Paper_Notes/Method/2026/MedVQA-2026-050_MD_PMAM-DGFM.md) · Parallel Multi-Attention and Gated Fusion for Visual Question Localized Answering in Surgical Scenes | [DOI](https://doi.org/10.1109/jbhi.2025.3648589)             |
| 2026-06 | [MedVQA-2026-040](./Paper_Notes/Method/2026/MedVQA-2026-040_MD_ACL-MVQA.md) · Attention Consistent Longitudinal Medical Visual Question Answering Guided by Vision Foundation Models | [DOI](https://openaccess.thecvf.com/content/CVPR2026W/PHAROS-AIF-MIH/html/Wu_Attention_Consistent_Longitudinal_Medical_Visual_Question_Answering_Guided_by_Vision_CVPRW_2026_paper.html) |
| 2026-06 | [MedVQA-2026-044](./Paper_Notes/Method/2026/MedVQA-2026-044_MD_MedFG-VQA.md) · MedFG-VQA: Low-Frequency Memory and Graph Attention for Lightweight Medical VQA | [DOI](https://openaccess.thecvf.com/content/CVPR2026/html/Gu_MedFG-VQA_Low-Frequency_Memory_and_Graph_Attention_for_Lightweight_Medical_VQA_CVPR_2026_paper.html) |
| 2026    | [MedVQA-2026-004](./Paper_Notes/Method/2026/MedVQA-2026-004_MD_MedFuseT.md) · MedFuseT: A Transformer-Based Model for Advancing Medical Visual Question Answering | [DOI](https://doi.org/10.1109/access.2026.3661875)           |
| 2025-09 | [MedVQA-2025-080](./Paper_Notes/Method/2025/MedVQA-2025-080_MD_IdeficMed.md) · Visual question answering for medical diagnosis | [DOI](https://doi.org/10.1016/j.iswa.2025.200545)            |
| 2025-07 | [MedVQA-2025-069](./Paper_Notes/Method/2025/MedVQA-2025-069_MD_BPCFI.md) · Body Part-Aware Cross-Modal Feature Interaction Learning for Medical Vision Question Answering | [DOI](https://doi.org/10.1007/978-981-96-9794-6_2)           |
| 2025-06 | [MedVQA-2024-063](./Paper_Notes/Method/2025/MedVQA-2024-063_MD_OMniBAN.md) · Efficient Bilinear Attention-based Fusion for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/ijcnn64981.2025.11228425)      |
| 2025-06 | [MedVQA-2025-066](./Paper_Notes/Method/2025/MedVQA-2025-066_MD_EMVQAMFFSAS.md) · Enhanced Medical Visual Question Answering Using Multi-Feature Fusion and Similarity-Based Answer Selection | [DOI](https://doi.org/10.1109/ijcnn64981.2025.11228331)      |
| 2025-05 | [MedVQA-2025-048](./Paper_Notes/Method/2025/MedVQA-2025-048_MD_MVQAMSFFQFE.md) · A medical visual question-answering model based on multi-scale feature fusion and question Feature enhancement | [DOI](https://doi.org/10.1007/s00530-025-01848-9)            |
| 2025-04 | [MedVQA-2025-033](./Paper_Notes/Method/2025/MedVQA-2025-033_MD_DSAF.md) · DSAF: A Dual-Stage Attention Based Multimodal Fusion Framework for Medical Visual Question Answering | [DOI](https://doi.org/10.1007/s42979-025-03868-8)            |
| 2025-03 | [MedVQA-2025-028](./Paper_Notes/Method/2025/MedVQA-2025-028_MD_LGPFN.md) · A Language-Guided Progressive Fusion Network with semantic density alignment for Medical Visual Question Answering | [DOI](https://doi.org/10.1016/j.jbi.2025.104811)             |
| 2025-01 | [MedVQA-2025-016](./Paper_Notes/Method/2025/MedVQA-2025-016_MD_VG-CALF.md) · VG-CALF: A vision-guided cross-attention and late-fusion network for radiology images in Medical Visual Question Answering | [DOI](https://doi.org/10.1016/j.neucom.2024.128730)          |
| 2024-12 | [MedVQA-2024-070](./Paper_Notes/Method/2024/MedVQA-2024-070_MD_CGACLOGVQA.md) · Cross-Guided Attention and Combined Loss for Optimizing Gastrointestinal Visual Question Answering | [DOI](https://doi.org/10.1109/bibm62325.2024.10821854)       |
| 2024-12 | [MedVQA-2024-071](./Paper_Notes/Method/2024/MedVQA-2024-071_MD_LCMBMVQA.md) · Leveraging Convolutional Models as Backbone for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/bibm62325.2024.10821918)       |
| 2024-11 | [MedVQA-2024-065](./Paper_Notes/Method/2025/MedVQA-2024-065_MD_CFMVQAALM.md) · Contextual Feature-Based Medical Visual Question Answering Aided by Learnable Matrix | [DOI](https://doi.org/10.1007/978-981-97-8505-6_1)           |
| 2024-08 | [MedVQA-2024-046](./Paper_Notes/Method/2024/MedVQA-2024-046_MD_MFAMVQA.md) · Multimodal fusion: advancing medical visual question-answering | [DOI](https://doi.org/10.1007/s00521-024-10318-8)            |
| 2024-07 | [MedVQA-2024-042](./Paper_Notes/Method/2024/MedVQA-2024-042_MD_IMIVQAMMRGL.md) · Interpretable medical image Visual Question Answering via multi-modal relationship graph learning | [DOI](https://doi.org/10.1016/j.media.2024.103279)           |
| 2024-06 | [MedVQA-2024-036](./Paper_Notes/Method/2025/MedVQA-2024-036_MD_VQASIRIHDVTFE.md) · Visual Question Answer System for Skeletal Image Using Radiology Images in the Healthcare Domain Based on Visual and Textual Feature Extraction Techniques | [DOI](https://doi.org/10.1007/s40745-024-00553-0)            |
| 2024-04 | [MedVQA-2024-023](./Paper_Notes/Method/2025/MedVQA-2024-023_MD_VQABSICBAMPOD.md) · Visual question answering on blood smear images using convolutional block attention module powered object detection | [DOI](https://doi.org/10.1007/s00371-024-03359-6)            |
| 2024-02 | [MedVQA-2022-013](./Paper_Notes/Method/2024/MedVQA-2022-013_MD_DALNet-WSE.md) · A Dual-Attention Learning Network With Word and Sentence Embedding for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/tmi.2023.3322868)              |
| 2024    | [MedVQA-2024-011](./Paper_Notes/Method/2024/MedVQA-2024-011_MD_TMIVMBCC.md) · Transforming Medical Imaging: A VQA Model for Microscopic Blood Cell Classification | [DOI](https://doi.org/10.1109/access.2024.3496655)           |
| 2023-10 | [MedVQA-2023-028](./Paper_Notes/Method/2023/MedVQA-2023-028_MD_CAT-ViL.md) · CAT-ViL: Co-attention Gated Vision-Language Embedding for Visual Question Localized-Answering in Robotic Surgery | [DOI](https://doi.org/10.1007/978-3-031-43996-4_38)          |
| 2023-10 | [MedVQA-2023-042](./Paper_Notes/Method/2023/MedVQA-2023-042_MD_FGCVQA.md) · FGCVQA: Fine-Grained Cross-Attention for Medical VQA | [DOI](https://doi.org/10.1109/icip49359.2023.10222540)       |
| 2023-10 | [MedVQA-2023-043](./Paper_Notes/Method/2023/MedVQA-2023-043_MD_MMHSA.md) · Multi-modal multi-head self-attention for medical VQA | [DOI](https://doi.org/10.1007/s11042-023-17162-3)            |
| 2023-09 | [MedVQA-2023-037](./Paper_Notes/Method/2023/MedVQA-2023-037_MD_ACMA-MAM.md) · Asymmetric cross-modal attention network with multimodal augmented mixup for medical visual question answering | [DOI](https://doi.org/10.1016/j.artmed.2023.102667)          |
| 2023-08 | [MedVQA-2023-036](./Paper_Notes/Method/2023/MedVQA-2023-036_MD_SInAM.md) · Medical visual question answering with symmetric interaction attention and cross-modal gating | [DOI](https://doi.org/10.1016/j.bspc.2023.105049)            |
| 2023-05 | [MedVQA-2023-021](./Paper_Notes/Method/2023/MedVQA-2023-021_MD_Surgical-VQLA.md) · Surgical-VQLA:Transformer with Gated Vision-Language Embedding for Visual Question Localized-Answering in Robotic Surgery | [DOI](https://doi.org/10.1109/icra48891.2023.10160403)       |
| 2023-04 | [MedVQA-2023-015](./Paper_Notes/Method/2023/MedVQA-2023-015_MD_TraP-VQA.md) · Vision-Language Transformer for Interpretable Pathology Visual Question Answering | [DOI](https://doi.org/10.1109/jbhi.2022.3163751)             |
| 2023-04 | [MedVQA-2023-017](./Paper_Notes/Method/2023/MedVQA-2023-017_MD_MF2-MVQA.md) · MF<sup>2</sup>-MVQA: A Multi-Stage Feature Fusion Method for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/isbi53787.2023.10230530)       |
| 2023-03 | [MedVQA-2023-007](./Paper_Notes/Method/2023/MedVQA-2023-007_MD_QFPN.md) · Question-guided feature pyramid network for medical visual question answering | [DOI](https://doi.org/10.1016/j.eswa.2022.119148)            |
| 2023-03 | [MedVQA-2023-010](./Paper_Notes/Method/2023/MedVQA-2023-010_MD_MaMVQA.md) · Parallel multi-head attention and term-weighted question embedding for medical visual question answering | [DOI](https://doi.org/10.1007/s11042-023-14981-2)            |
| 2023-03 | [MedVQA-2023-012](./Paper_Notes/Method/2023/MedVQA-2023-012_MD_VLVQAMI.md) · Vision–Language Model for Visual Question Answering in Medical Imagery | [DOI](https://doi.org/10.3390/bioengineering10030380)        |
| 2023-03 | [MedVQA-2023-014](./Paper_Notes/Method/2023/MedVQA-2023-014_MD_VB-MVQA.md) · Pre-trained multilevel fuse network based on vision-conditioned reasoning and bilinear attentions for medical image visual question answering | [DOI](https://doi.org/10.1007/s11227-023-05195-2)            |
| 2022-12 | [MedVQA-2022-020](./Paper_Notes/Method/2022/MedVQA-2022-020_MD_M-Mixup.md) · How Well Apply Multimodal Mixup and Simple MLPs Backbone to Medical Visual Question Answering? | [DOI](https://doi.org/10.1109/bibm55620.2022.9995347)        |
| 2022-11 | [MedVQA-2022-018](./Paper_Notes/Method/2022/MedVQA-2022-018_MD_AMAM.md) · AMAM: An Attention-based Multimodal Alignment Model for Medical Visual Question Answering | [DOI](https://doi.org/10.1016/j.knosys.2022.109763)          |
| 2022-11 | [MedVQA-2022-019](./Paper_Notes/Method/2022/MedVQA-2022-019_MD_M2FNet.md) · M2FNet: Multi-granularity Feature Fusion Network for Medical Visual Question Answering | [DOI](https://doi.org/10.1007/978-3-031-20865-2_11)          |
| 2022-10 | [MedVQA-2022-015](./Paper_Notes/Method/2022/MedVQA-2022-015_MD_Caption-Aware-VQA.md) · Caption-Aware Medical VQA via Semantic Focusing and Progressive Cross-Modality Comprehension | [DOI](https://doi.org/10.1145/3503161.3548122)               |
| 2022-09 | [MedVQA-2022-004](./Paper_Notes/Method/2022/MedVQA-2022-004_MD_Surgical-VQA.md) · Surgical-VQA: Visual Question Answering in Surgical Scenes Using Transformer | [DOI](https://doi.org/10.1007/978-3-031-16449-1_4)           |
| 2022-08 | [MedVQA-2022-008](./Paper_Notes/Method/2022/MedVQA-2022-008_MD_MQAT.md) · A Transformer-based Medical Visual Question Answering Model | [DOI](https://doi.org/10.1109/icpr56361.2022.9956469)        |
| 2022-07 | [MedVQA-2022-007](./Paper_Notes/Method/2022/MedVQA-2022-007_MD_CFF-SA.md) · Medical visual question answering via corresponding feature fusion combined with semantic attention | [DOI](https://doi.org/10.3934/mbe.2022478)                   |
| 2022-06 | [MedVQA-2022-005](./Paper_Notes/Method/2022/MedVQA-2022-005_MD_QTR-SSC.md) · Medical visual question answering based on question-type reasoning and semantic space constraint | [DOI](https://doi.org/10.1016/j.artmed.2022.102346)          |
| 2022-05 | [MedVQA-2022-003](./Paper_Notes/Method/2022/MedVQA-2022-003_MD_FITS.md) · Type-Aware Medical Visual Question Answering | [DOI](https://doi.org/10.1109/icassp43922.2022.9747087)      |
| 2022-04 | [MedVQA-2022-002](./Paper_Notes/Method/2022/MedVQA-2022-002_MD_BPI-MVQA.md) · BPI-MVQA: a bi-branch model for medical visual question answering | [DOI](https://doi.org/10.1186/s12880-022-00800-x)            |
| 2021-10 | [MedVQA-2021-009](./Paper_Notes/Method/2021/MedVQA-2021-009_MD_VQAMDDLACS.md) · Visual question answering in the medical domain based on deep learning approaches: A comprehensive study | [DOI](https://doi.org/10.1016/j.patrec.2021.07.002)          |
| 2021-10 | [MedVQA-2021-010](./Paper_Notes/Method/2021/MedVQA-2021-010_MD_MedFuseNet.md) · MedFuseNet: An attention-based multimodal deep learning model for visual question answering in the medical domain | [DOI](https://doi.org/10.1038/s41598-021-98390-1)            |
| 2021-10 | [MedVQA-2021-011](./Paper_Notes/Method/2021/MedVQA-2021-011_MD_MVQAS.md) · MVQAS A Medical Visual Question Answering System | [DOI](https://doi.org/10.1145/3459637.3481971)               |
| 2021-02 | [MedVQA-2021-003](./Paper_Notes/Method/2021/MedVQA-2021-003_MD_HQS-VQA.md) · Hierarchical deep multi-modal network for medical visual question answering | [DOI](https://doi.org/10.1016/j.eswa.2020.113993)            |
| 2020-03 | [MedVQA-2020-003](./Paper_Notes/Method/2020/MedVQA-2020-003_MD_QC-MLB.md) · A Question-Centric Model for Visual Question Answering in Medical Imaging | [DOI](https://doi.org/10.1109/tmi.2020.2978284)              |

<a id="section-5.2"></a>

## 5.2. Representation Learning & Cross-modal Alignment

| Date    | Title                                                        | DOI                                                      |
| ------- | ------------------------------------------------------------ | -------------------------------------------------------- |
| 2026-07 | [MedVQA-2026-001](./Paper_Notes/Method/2026/MedVQA-2026-001_MD_DEPO.md) · Beyond Surface Features: Advancing Medical Vision-Language Alignment via Dynamic Evidence-Guided Preference Optimization | [DOI](https://doi.org/10.18653/v1/2026.acl-long.1200)    |
| 2026-05 | [MedVQA-2026-030](./Paper_Notes/Method/2026/MedVQA-2026-030_MD_Med-MGIA.md) · Dual-Guided Multi-Granularity Implicit Alignment Network for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/icassp55912.2026.11461438) |
| 2026-03 | [MedVQA-2026-017](./Paper_Notes/Method/2026/MedVQA-2026-017_MD_CKRA.md) · Beyond Static Knowledge: Dynamic Context-Aware Cross-Modal Contrastive Learning for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/tmi.2025.3617289)          |
| 2026-01 | [MedVQA-2026-009](./Paper_Notes/Method/2026/MedVQA-2026-009_MD_CoMed-TR.md) · Large-small model collaboration for medical visual question answering with task aware mixture of experts and relation knowledge distillation | [DOI](https://doi.org/10.1016/j.imavis.2025.105820)      |
| 2026-01 | [MedVQA-2026-011](./Paper_Notes/Method/2026/MedVQA-2026-011_MD_MPA-VQA.md) · Segmentation-enhanced Medical Visual Question Answering with mask-prompt alignment using contrastive learning and multitask object grounding | [DOI](https://doi.org/10.1016/j.engappai.2025.112866)    |
| 2025-09 | [MedVQA-2025-083](./Paper_Notes/Method/2026/MedVQA-2025-083_MD_BaMCo.md) · BaMCo: Balanced Multimodal Contrastive Learning for Knowledge-Driven Medical VQA | [DOI](https://doi.org/10.1007/978-3-032-04981-0_8)       |
| 2025-09 | [MedVQA-2025-088](./Paper_Notes/Method/2026/MedVQA-2025-088_MD_BioD2C.md) · BioD2C: A Dual-Level Semantic Consistency Constraint Framework for Biomedical VQA | [DOI](https://doi.org/10.1007/978-3-032-05127-1_9)       |
| 2025    | [MedVQA-2025-002](./Paper_Notes/Method/2025/MedVQA-2025-002_MD_BTIA-ADNet.md) · Answer Distillation Network With Bi-Text-Image Attention for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/access.2025.3532308)       |
| 2024-09 | [MedVQA-2024-049](./Paper_Notes/Method/2024/MedVQA-2024-049_MD_LCFGRCLDMVQA.md) · Leveraging Coarse-to-Fine Grained Representations in Contrastive Learning for Differential Medical Visual Question Answering | [DOI](https://doi.org/10.1007/978-3-031-72086-4_39)      |
| 2024-09 | [MedVQA-2024-050](./Paper_Notes/Method/2024/MedVQA-2024-050_MD_MMQL.md) · MMQL: Multi-Question Learning for Medical Visual Question Answering | [DOI](https://doi.org/10.1007/978-3-031-72086-4_45)      |
| 2024-09 | [MedVQA-2024-052](./Paper_Notes/Method/2024/MedVQA-2024-052_MD_ReAl.md) · Spot the Difference: Difference Visual Question Answering with Residual Alignment | [DOI](https://doi.org/10.1007/978-3-031-72086-4_61)      |
| 2024-06 | [MedVQA-2024-037](./Paper_Notes/Method/2024/MedVQA-2024-037_MD_FECAFNet.md) · Overcoming Data Limitations and Cross-Modal Interaction Challenges in Medical Visual Question Answering | [DOI](https://doi.org/10.1109/ijcnn60899.2024.10651345)  |
| 2024-05 | [MedVQA-2024-028](./Paper_Notes/Method/2024/MedVQA-2024-028_MD_OTAS.md) · Alignment before Awareness: Towards Visual Question Localized-Answering in Robotic Surgery via Optimal Transport and Answer Semantics | [DOI](https://doi.org/10.63317/4jh5knz54ake)             |
| 2024-02 | [MedVQA-2023-003](./Paper_Notes/Method/2023/MedVQA-2023-003_MD_PLMVQA.md) · PLMVQA: Applying Pseudo Labels for Medical Visual Question Answering with Limited Data | [DOI](https://doi.org/10.1007/978-3-031-47425-5_32)      |
| 2023-05 | [MedVQA-2023-020](./Paper_Notes/Method/2023/MedVQA-2023-020_MD_CPCR.md) · Medical Visual Question Answering via Conditional Reasoning and Contrastive Learning | [DOI](https://doi.org/10.1109/tmi.2022.3232411)          |
| 2022-12 | [MedVQA-2022-021](./Paper_Notes/Method/2022/MedVQA-2022-021_MD_MHKD-MVQA.md) · MHKD-MVQA: Multimodal Hierarchical Knowledge Distillation for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/bibm55620.2022.9995473)    |
| 2022-08 | [MedVQA-2022-009](./Paper_Notes/Method/2022/MedVQA-2022-009_MD_BiRL.md) · A Bi-level representation learning model for medical visual question answering | [DOI](https://doi.org/10.1016/j.jbi.2022.104183)         |
| 2021-09 | [MedVQA-2021-005](./Paper_Notes/Method/2021/MedVQA-2021-005_MD_CMSA-MTPT.md) · Cross-Modal Self-Attention with Multi-Task Pre-Training for Medical Visual Question Answering | [DOI](https://doi.org/10.1145/3460426.3463584)           |

<a id="section-5.3"></a>

## 5.3. Knowledge-enhanced & Retrieval-augmented Methods

| Date    | Title                                                        | DOI                                                          |
| ------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2026-09 | [MedVQA-2026-061](./Paper_Notes/Method/2027/MedVQA-2026-061_MD_MEC.md) · MEC: Medical Evidence Capsules for Retrieval-Augmented Generation in Medical Multimodal Question Answering | [DOI](https://doi.org/10.1007/978-3-032-38059-3_29)          |
| 2026-07 | [MedVQA-2026-005](./Paper_Notes/Method/2026/MedVQA-2026-005_MD_MedKInstruct.md) · MedKInstruct: A Multimodal Knowledge Graph Based Framework for Multi-Hop and Hard-Negative Instruction Data Synthesis in MedVQA | [DOI](https://doi.org/10.18653/v1/2026.findings-acl.1391)    |
| 2026-07 | [MedVQA-2026-025](./Paper_Notes/Method/2026/MedVQA-2026-025_MD_KG-CMI.md) · KG-CMI: Knowledge Graph Enhanced Cross-Mamba Interaction for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/tii.2026.3676874)              |
| 2026-07 | [MedVQA-2026-049](./Paper_Notes/Method/2026/MedVQA-2026-049_MD_DoKE.md) · DoKE: Domain knowledge–enhanced multimodal large language model–based framework for chest X–ray follow–up medical visual question answering | [DOI](https://doi.org/10.1016/j.bspc.2026.109908)            |
| 2026-07 | [MedVQA-2026-054](./Paper_Notes/Method/2026/MedVQA-2026-054_MD_KEVQA-CLIP.md) · A knowledge enhanced framework for interpretable medical visual question and answering via large foundation model | [DOI](https://doi.org/10.1007/s00530-026-02470-z)            |
| 2026-06 | [MedVQA-2026-046](./Paper_Notes/Method/2026/MedVQA-2026-046_MD_MR-RAG.md) · MR-RAG: Multimodal Relevance-Aware Retrieval-Augmented Generation for Medical Visual Question Answering | [DOI](https://openaccess.thecvf.com/content/CVPR2026/html/Li_MR-RAG_Multimodal_Relevance-Aware_Retrieval-Augmented_Generation_for_Medical_Visual_Question_Answering_CVPR_2026_paper.html) |
| 2026-06 | [MedVQA-2026-048](./Paper_Notes/Method/2026/MedVQA-2026-048_MD_EC-RAG.md) · EC-RAG: Evidence-Centric Retrieval-Augmented Generation for Medical Visual Question Answering | [DOI](https://doi.org/10.1145/3805622.3810670)               |
| 2026-05 | [MedVQA-2026-032](./Paper_Notes/Method/2026/MedVQA-2026-032_MD_MCRAG.md) · Making Medical Vision-Language Models Think Causally Across Modalities with Retrieval-Augmented Cross-Modal Reasoning | [DOI](https://doi.org/10.1109/icassp55912.2026.11462104)     |
| 2026-04 | [MedVQA-2026-024](./Paper_Notes/Method/2026/MedVQA-2026-024_MD_MAP-GR.md) · MAP-GR: medical aware prompt and graph-guided reasoning for enhanced medical visual question answering | [DOI](https://doi.org/10.1016/j.neucom.2026.132645)          |
| 2026-03 | [MedVQA-2026-018](./Paper_Notes/Method/2026/MedVQA-2026-018_MD_KGLMQA.md) · KGLMQA: enhancing medical visual question answering with knowledge graphs and LLMs | [DOI](https://doi.org/10.7717/peerj-cs.3679)                 |
| 2025-12 | [MedVQA-2025-109](./Paper_Notes/Method/2025/MedVQA-2025-109_MD_EnVR-LPKG.md) · Enhancing Visual Reasoning With LLM-Powered Knowledge Graphs for Visual Question Localized-Answering in Robotic Surgery | [DOI](https://doi.org/10.1109/jbhi.2025.3538324)             |
| 2025-09 | [MedVQA-2025-065](./Paper_Notes/Method/2026/MedVQA-2025-065_MD_MOTOR.md) · MOTOR: Multimodal Optimal Transport via Grounded Retrieval in Medical Visual Question Answering | [DOI](https://doi.org/10.1007/978-3-032-04978-0_44)          |
| 2025-08 | [MedVQA-2025-071](./Paper_Notes/Method/2025/MedVQA-2025-071_MD_FGRW.md) · Fine-grained knowledge fusion for retrieval-augmented medical visual question answering | [DOI](https://doi.org/10.1016/j.inffus.2025.103059)          |
| 2025-06 | [MedVQA-2025-052](./Paper_Notes/Method/2025/MedVQA-2025-052_MD_MKGF.md) · MKGF: A multi-modal knowledge graph based RAG framework to enhance LVLMs for Medical visual question answering | [DOI](https://doi.org/10.1016/j.neucom.2025.129999)          |
| 2025-04 | [MedVQA-2025-040](./Paper_Notes/Method/2025/MedVQA-2025-040_MD_MENDER.md) · Cross-Modal Knowledge Diffusion-Based Generation for Difference-Aware Medical VQA | [DOI](https://doi.org/10.1109/tip.2025.3558446)              |
| 2025-03 | [MedVQA-2025-024](./Paper_Notes/Method/2025/MedVQA-2025-024_MD_IMSMDMDQA.md) · Integration of Multi-Source Medical Data for Medical Diagnosis Question Answering | [DOI](https://doi.org/10.1109/tmi.2024.3496862)              |
| 2025-02 | [MedVQA-2024-068](./Paper_Notes/Method/2025/MedVQA-2024-068_MD_Path-RAG.md) · Path-RAG: Knowledge-Guided Key Region Retrieval for Open-ended Pathology Visual Question Answering | [DOI](https://proceedings.mlr.press/v259/naeem25a.html)      |
| 2025    | [MedVQA-2025-006](./Paper_Notes/Method/2025/MedVQA-2025-006_MD_MKG-Diff-VQA.md) · Medical Knowledge-Based Differential Image Visual Question Answering | [DOI](https://doi.org/10.1109/access.2025.3565695)           |
| 2024-09 | [MedVQA-2024-051](./Paper_Notes/Method/2024/MedVQA-2024-051_MD_RS-RAG.md) · Region-Specific Retrieval Augmentation for Longitudinal Visual Question Answering: A Mix-and-Match Paradigm | [DOI](https://doi.org/10.1007/978-3-031-72086-4_55)          |
| 2024-05 | [MedVQA-2024-031](./Paper_Notes/Method/2024/MedVQA-2024-031_MD_SSG-VQA.md) · Advancing surgical VQA with scene graph knowledge | [DOI](https://doi.org/10.1007/s11548-024-03141-y)            |
| 2023-10 | [MedVQA-2023-008](./Paper_Notes/Method/2023/MedVQA-2023-008_MD_RAMM.md) · RAMM: Retrieval-augmented Biomedical Visual Question Answering with Multi-modal Pre-training | [DOI](https://doi.org/10.1145/3581783.3611830)               |
| 2023-08 | [MedVQA-2023-031](./Paper_Notes/Method/2023/MedVQA-2023-031_MD_EKAID.md) · Expert Knowledge-Aware Image Difference Graph Representation Learning for Difference-Aware Medical Visual Question Answering | [DOI](https://doi.org/10.1145/3580305.3599819)               |
| 2023-07 | [MedVQA-2023-005](./Paper_Notes/Method/2023/MedVQA-2023-005_MD_MPR.md) · Retrieving Multimodal Prompts for Generative Visual Question Answering | [DOI](https://doi.org/10.18653/v1/2023.findings-acl.158)     |
| 2023-07 | [MedVQA-2023-029](./Paper_Notes/Method/2024/MedVQA-2023-029_MD_K-PathVQA.md) · K-PathVQA: Knowledge-Aware Multimodal Representation for Pathology Visual Question Answering | [DOI](https://doi.org/10.1109/jbhi.2023.3294249)             |
| 2023-03 | [MedVQA-2023-006](./Paper_Notes/Method/2023/MedVQA-2023-006_MD_MKBN.md) · Medical knowledge-based network for Patient-oriented Visual Question Answering | [DOI](https://doi.org/10.1016/j.ipm.2022.103241)             |

<a id="section-5.4"></a>

## 5.4. Prompt Learning & Efficient Adaptation

| Date    | Title                                                        | DOI                                                      |
| ------- | ------------------------------------------------------------ | -------------------------------------------------------- |
| 2026-09 | [MedVQA-2026-060](./Paper_Notes/Method/2027/MedVQA-2026-060_MD_M3D-QAdapter.md) · M3D-QAdapter: 3D Medical VQA with Lesion-Level Finding-Segmentation Alignment and Query-Driven Adaptive Token Reduction | [DOI](https://doi.org/10.1007/978-3-032-38062-3_34)      |
| 2026-07 | [MedVQA-2025-021](./Paper_Notes/Method/2026/MedVQA-2025-021_MD_PitVQA-PlusPlus.md) · PitVQA++: Vector Matrix-Low-Rank Adaptation for Open-Ended Visual Question Answering in Pituitary Surgery | [DOI](https://doi.org/10.1109/tmi.2026.3681175)          |
| 2026-04 | [MedVQA-2026-026](./Paper_Notes/Method/2026/MedVQA-2026-026_MD_D2MNet.md) · D2MNet: Difference-Aware Decoupling and Multi-Prompt Learning for Medical Difference Visual Question Answering | [DOI](https://doi.org/10.3390/jimaging12040162)          |
| 2025-12 | [MedVQA-2025-112](./Paper_Notes/Method/2025/MedVQA-2025-112_MD_A2M-Diff.md) · Anatomy-Aware Adaptation of Pre-Trained Models for Medical Difference Visual Question Answering | [DOI](https://doi.org/10.1109/bibm66473.2025.11356508)   |
| 2025-12 | [MedVQA-2025-116](./Paper_Notes/Method/2025/MedVQA-2025-116_MD_MLWA-MVQA.md) · Meta-Learning with Attention Network for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/bibm66473.2025.11356912)   |
| 2025-11 | [MedVQA-2025-013](./Paper_Notes/Method/2025/MedVQA-2025-013_MD_X-FLoRA.md) · X-FLoRA: Cross-modal Federated Learning with Modality-expert LoRA for Medical VQA | [DOI](https://doi.org/10.18653/v1/2025.emnlp-main.422)   |
| 2025-11 | [MedVQA-2025-101](./Paper_Notes/Method/2025/MedVQA-2025-101_MD_DQAP.md) · Bridging the Semantic Gap in Medical Visual Question Answering With Prompt Learning | [DOI](https://doi.org/10.1109/tmi.2025.3580561)          |
| 2025-11 | [MedVQA-2025-105](./Paper_Notes/Method/2025/MedVQA-2025-105_MD_CARM.md) · Caption-augmented reasoning model with Hierarchical rank LoRA finetuing for medical visual question Answering | [DOI](https://doi.org/10.1016/j.jbi.2025.104964)         |
| 2025-09 | [MedVQA-2025-086](./Paper_Notes/Method/2026/MedVQA-2025-086_MD_Localization-Lens.md) · Localization Lens for Improving Medical Vision-Language Models | [DOI](https://doi.org/10.1007/978-3-032-05114-1_33)      |
| 2025-06 | [MedVQA-2024-060](./Paper_Notes/Method/2025/MedVQA-2024-060_MD_R-LLaVA.md) · R-LLaVA: Improving Med-VQA Understanding through Visual Region of Interest | [DOI](https://doi.org/10.1109/ijcnn64981.2025.11227685)  |
| 2025-05 | [MedVQA-2025-049](./Paper_Notes/Method/2025/MedVQA-2025-049_MD_MedBLIP.md) · MedBLIP: A multimodal method of medical question-answering based on fine-tuning large language model | [DOI](https://doi.org/10.1016/j.compmedimag.2025.102581) |
| 2025-04 | [MedVQA-2024-020](./Paper_Notes/Method/2025/MedVQA-2024-020_MD_MedPromptX.md) · MedPromptX: Grounded Multimodal Prompting for Chest X-Ray Diagnosis | [DOI](https://doi.org/10.1007/978-3-031-84525-3_18)      |
| 2025-04 | [MedVQA-2025-036](./Paper_Notes/Method/2025/MedVQA-2025-036_MD_FAVP.md) · Fine-grained Adaptive Visual Prompt for Generative Medical Visual Question Answering | [DOI](https://doi.org/10.1609/aaai.v39i9.33047)          |
| 2025-03 | [MedVQA-2025-025](./Paper_Notes/Method/2025/MedVQA-2025-025_MD_MiniMedGPT.md) · MiniMedGPT: Efficient Large Vision–Language Model for medical Visual Question Answering | [DOI](https://doi.org/10.1016/j.patrec.2025.01.001)      |
| 2025-02 | [MedVQA-2024-045](./Paper_Notes/Method/2025/MedVQA-2024-045_MD_LocAtt.md) · Targeted Visual Prompting for Medical Visual Question Answering | [DOI](https://doi.org/10.1007/978-3-031-82007-6_7)       |
| 2024-11 | [MedVQA-2024-009](./Paper_Notes/Method/2024/MedVQA-2024-009_MD_STLLaVA-Med.md) · Self-Training Large Language and Vision Assistant for Medical Question Answering | [DOI](https://doi.org/10.18653/v1/2024.emnlp-main.1119)  |
| 2024-10 | [MedVQA-2024-062](./Paper_Notes/Method/2024/MedVQA-2024-062_MD_EFLCFTMVLM.md) · Efficiency in Focus: LayerNorm as a Catalyst for Fine-tuning Medical Visual Language Models | [DOI](https://doi.org/10.1145/3664647.3680834)           |
| 2024-09 | [MedVQA-2024-048](./Paper_Notes/Method/2024/MedVQA-2024-048_MD_CH-ICL.md) · Candidate-Heuristic In-Context Learning: A new framework for enhancing medical visual question answering with LLMs | [DOI](https://doi.org/10.1016/j.ipm.2024.103805)         |
| 2024-08 | [MedVQA-2024-043](./Paper_Notes/Method/2024/MedVQA-2024-043_MD_VQA-Adapter.md) · Parameter-Efficient Transfer Learning for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/tetci.2023.3311333)        |
| 2024-06 | [MedVQA-2024-026](./Paper_Notes/Method/2024/MedVQA-2024-026_MD_LaPA.md) · LaPA: Latent Prompt Assist Model for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/cvprw63382.2024.00502)     |
| 2024-04 | [MedVQA-2024-015](./Paper_Notes/Method/2024/MedVQA-2024-015_MD_PMCLIP.md) · Prompt-Based Personalized Federated Learning for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/icassp48485.2024.10445933) |
| 2024-04 | [MedVQA-2024-027](./Paper_Notes/Method/2024/MedVQA-2024-027_MD_DMPL.md) · Dual modality prompt learning for visual question-grounded answering in robotic surgery | [DOI](https://doi.org/10.1186/s42492-024-00160-z)        |
| 2023-10 | [MedVQA-2023-009](./Paper_Notes/Method/2023/MedVQA-2023-009_MD_OEMVQAPTLM.md) · Open-Ended Medical Visual Question Answering Through Prefix Tuning of Language Models | [DOI](https://doi.org/10.1007/978-3-031-43904-9_70)      |
| 2021-09 | [MedVQA-2021-006](./Paper_Notes/Method/2021/MedVQA-2021-006_MD_MMQ.md) · Multiple Meta-model Quantifying for Medical Visual Question Answering | [DOI](https://doi.org/10.1007/978-3-030-87240-3_7)       |
| 2020-11 | [MedVQA-2020-006](./Paper_Notes/Method/2020/MedVQA-2020-006_MD_KEML.md) · Learning from the Guidance: Knowledge Embedded Meta-learning for Medical Visual Question Answering | [DOI](https://doi.org/10.1007/978-3-030-63820-7_22)      |
| 2019-10 | [MedVQA-2019-002](./Paper_Notes/Method/2019/MedVQA-2019-002_MD_MEVF.md) · Overcoming Data Limitation in Medical Visual Question Answering | [DOI](https://doi.org/10.1007/978-3-030-32251-9_57)      |

<a id="section-5.5"></a>

## 5.5. Reasoning & Answer Generation

| Date    | Title                                                        | DOI                                                          |
| ------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2026-09 | [MedVQA-2026-039](./Paper_Notes/Method/2027/MedVQA-2026-039_MD_EchoVQA.md) · EchoVQA: Enabling Conversational Assistance for Point-of-Care Cardiac Ultrasound | [DOI](https://doi.org/10.1007/978-3-032-38059-3_14)          |
| 2026-09 | [MedVQA-2026-052](./Paper_Notes/Method/2027/MedVQA-2026-052_MD_IRIS.md) · IRIS: An Intelligent Vision-Language System for Ocular Surface Diseases via Topic Tree and Scene-Driven VQA Generation | [DOI](https://doi.org/10.1007/978-3-032-38059-3_22)          |
| 2026-09 | [MedVQA-2026-064](./Paper_Notes/Method/2027/MedVQA-2026-064_MD_TGST.md) · Reformulating Chest X-Ray Report Generation as Fine-Grained Visual Question Answering with Structured Clinical Report Templates | [DOI](https://doi.org/10.1007/978-3-032-38059-3_48)          |
| 2026-08 | [MedVQA-2026-056](./Paper_Notes/Method/2026/MedVQA-2026-056_MD_DAMON.md) · DAMON: Difference-Aware Medical Visual Question Answering via Multimodal Large Language Model | [DOI](https://doi.org/10.1109/jbhi.2026.3663420)             |
| 2026-07 | [MedVQA-2025-060](./Paper_Notes/Method/2026/MedVQA-2025-060_MD_AYTRCRMVQA.md) · Act as you think: Reinforcing Consistent Reasoning in Medical Visual Question Answering | [DOI](https://doi.org/10.18653/v1/2026.acl-long.81)          |
| 2026-07 | [MedVQA-2026-002](./Paper_Notes/Method/2026/MedVQA-2026-002_MD_Evo-PI.md) · Evo-PI: Aligning Medical Reasoning via Evolving Principle-Guided Supervision | [DOI](https://doi.org/10.18653/v1/2026.acl-long.1469)        |
| 2026-03 | [MedVQA-2025-107](./Paper_Notes/Method/2026/MedVQA-2025-107_MD_MedEyes.md) · MedEyes: Learning Dynamic Visual Focus for Medical Progressive Diagnosis | [DOI](https://doi.org/10.1609/aaai.v40i16.38401)             |
| 2026-03 | [MedVQA-2026-019](./Paper_Notes/Method/2026/MedVQA-2026-019_MD_CMID.md) · CMID: Towards Medical Visual Question Answering via Contrastive Mutual Information Decoding | [DOI](https://doi.org/10.1609/aaai.v40i41.40835)             |
| 2026-01 | [MedVQA-2026-010](./Paper_Notes/Method/2026/MedVQA-2026-010_MD_DiffuVQA.md) · Redefining medical visual question answering using conditional generative diffusion models | [DOI](https://doi.org/10.1016/j.bspc.2025.108222)            |
| 2025-12 | [MedVQA-2025-114](./Paper_Notes/Method/2025/MedVQA-2025-114_MD_Med-SER.md) · Med-SER: Enhancing Reasoning Interpretability in Medical Visual Question Answering via Structured Chain-of-Thought | [DOI](https://doi.org/10.1109/bibm66473.2025.11356359)       |
| 2025-12 | [MedVQA-2025-115](./Paper_Notes/Method/2025/MedVQA-2025-115_MD_MedKCoT.md) · MedKCoT: A Knowledge-Guided Multi-Modal Chain-of-Thought Generation Framework for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/bibm66473.2025.11356053)       |
| 2025-12 | [MedVQA-2025-120](./Paper_Notes/Method/2025/MedVQA-2025-120_MD_SRFE.md) · Reflect Then Reason: Iterative Reflection with Soft Reasoning Feature Enhancement for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/bibm66473.2025.11356577)       |
| 2025-11 | [MedVQA-2025-046](./Paper_Notes/Method/2025/MedVQA-2025-046_MD_ASEMVQA.md) · Answer Semantics-enhanced Medical Visual Question Answering | [DOI](https://doi.org/10.1007/s11633-025-1564-2)             |
| 2025-11 | [MedVQA-2025-103](./Paper_Notes/Method/2025/MedVQA-2025-103_MD_Med-SCoT.md) · Med-SCoT: Structured chain-of-thought reasoning and evaluation for enhancing interpretability in medical visual question answering | [DOI](https://doi.org/10.1016/j.compmedimag.2025.102659)     |
| 2025-10 | [MedVQA-2025-092](./Paper_Notes/Method/2025/MedVQA-2025-092_MD_CGoT.md) · Visual and Domain Knowledge for Professional-Level Graph-of-Thought Medical Reasoning | [DOI](https://proceedings.mlr.press/v267/bao25b.html)        |
| 2025-10 | [MedVQA-2025-094](./Paper_Notes/Method/2025/MedVQA-2025-094_MD_IE-VQA.md) · Inference enhanced model with answer refinement for medical visual question answering | [DOI](https://doi.org/10.1007/s00530-025-01997-x)            |
| 2025-10 | [MedVQA-2025-096](./Paper_Notes/Method/2025/MedVQA-2025-096_MD_SurGen-Net.md) · SurGen-Net: A Generative Approach for Surgical VQA with Structured Text Generation | [DOI](https://doi.org/10.1109/iccvw69036.2025.00139)         |
| 2025-08 | [MedVQA-2025-070](./Paper_Notes/Method/2025/MedVQA-2025-070_MD_Med-CoE.md) · Explainable medical visual question answering via chain of evidence | [DOI](https://doi.org/10.1016/j.knosys.2025.113672)          |
| 2025-04 | [MedVQA-2025-007](./Paper_Notes/Method/2025/MedVQA-2025-007_MD_MedThink.md) · MedThink: A Rationale-Guided Framework for Explaining Medical Visual Question Answering | [DOI](https://doi.org/10.18653/v1/2025.findings-naacl.415)   |
| 2025-04 | [MedVQA-2025-032](./Paper_Notes/Method/2025/MedVQA-2025-032_MD_MEDSQ.md) · MEDSQ: Towards personalized medical education via multi-form interaction guidance | [DOI](https://doi.org/10.1016/j.eswa.2024.126138)            |
| 2025-02 | [MedVQA-2025-019](./Paper_Notes/Method/2025/MedVQA-2025-019_MD_CoCoMeD.md) · Consistency Conditioned Memory Augmented Dynamic Diagnosis Model for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/jbhi.2024.3492141)             |
| 2025    | [MedVQA-2025-009](./Paper_Notes/Method/2025/MedVQA-2025-009_MD_MultI-MVQA.md) · MultI-MVQA: A multitask framework for interpretable medical visual question answering | [DOI](https://doi.org/10.1016/j.procs.2025.09.307)           |
| 2024-12 | [MedVQA-2024-035](./Paper_Notes/Method/2024/MedVQA-2024-035_MD_Tri-VQA.md) · Tri-VQA: Triangular Reasoning Medical Visual Question Answering for Multi-Attribute Analysis | [DOI](https://doi.org/10.1109/bibm62325.2024.10822825)       |
| 2024-11 | [MedVQA-2024-005](./Paper_Notes/Method/2024/MedVQA-2024-005_MD_MedCoT.md) · MedCoT: Medical Chain of Thought via Hierarchical Expert | [DOI](https://doi.org/10.18653/v1/2024.emnlp-main.962)       |
| 2024-10 | [MedVQA-2024-030](./Paper_Notes/Method/2024/MedVQA-2024-030_MD_PitVQA.md) · PitVQA: Image-Grounded Text Embedding LLM for Visual Question Answering in Pituitary Surgery | [DOI](https://doi.org/10.1007/978-3-031-72089-5_46)          |
| 2024-10 | [MedVQA-2024-040](./Paper_Notes/Method/2025/MedVQA-2024-040_MD_WSI-VQA.md) · WSI-VQA: Interpreting Whole Slide Images by Generative Visual Question Answering | [DOI](https://doi.org/10.1007/978-3-031-72764-1_23)          |
| 2024-07 | [MedVQA-2024-039](./Paper_Notes/Method/2024/MedVQA-2024-039_MD_Uni-Med.md) · Detecting Any Instruction-to-Answer Interaction Relationship: Universal Instruction-to-Answer Navigator for Med-VQA | [DOI](https://proceedings.mlr.press/v235/wu24ac.html)        |
| 2023-12 | [MedVQA-2023-048](./Paper_Notes/Method/2023/MedVQA-2023-048_MD_MLRRAMVQA.md) · Multi-level Relational Reasoning and Attention Network for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/hpcc-dss-smartcity-dependsys60770.2023.00094) |
| 2023-10 | [MedVQA-2023-039](./Paper_Notes/Method/2023/MedVQA-2023-039_MD_SurgicalGPT.md) · SurgicalGPT: End-to-End Language-Vision GPT for Visual Question Answering in Surgery | [DOI](https://doi.org/10.1007/978-3-031-43996-4_27)          |
| 2023-06 | [MedVQA-2023-025](./Paper_Notes/Method/2023/MedVQA-2023-025_MD_Q2ATransformer.md) · Q2ATransformer: Improving Medical VQA via an Answer Querying Decoder | [DOI](https://doi.org/10.1007/978-3-031-34048-2_34)          |
| 2022-09 | [MedVQA-2022-011](./Paper_Notes/Method/2022/MedVQA-2022-011_MD_SQuINT.md) · Consistency-Preserving Visual Question Answering in Medical Imaging | [DOI](https://doi.org/10.1007/978-3-031-16452-1_37)          |
| 2022-09 | [MedVQA-2022-012](./Paper_Notes/Method/2022/MedVQA-2022-012_MD_RepsNet.md) · RepsNet: Combining Vision with Language for Automated Medical Reports | [DOI](https://doi.org/10.1007/978-3-031-16443-9_68)          |
| 2020-10 | [MedVQA-2020-004](./Paper_Notes/Method/2020/MedVQA-2020-004_MD_QCR-TCR.md) · Medical Visual Question Answering via Conditional Reasoning | [DOI](https://doi.org/10.1145/3394171.3413761)               |
| 2020    | [MedVQA-2020-001](./Paper_Notes/Method/2020/MedVQA-2020-001_MD_CGMVQA.md) · CGMVQA: A New Classification and Generative Model for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/access.2020.2980024)           |

<a id="section-5.6"></a>

## 5.6. Reliability, Generalization & Debiasing

| Date    | Title                                                        | DOI                                                          |
| ------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2026-09 | [MedVQA-2026-021](./Paper_Notes/Method/2027/MedVQA-2026-021_MD_CEBaG.md) · Deterministic Hallucination Detection in Medical VQA via Confidence-Evidence Bayesian Gain | [DOI](https://doi.org/10.1007/978-3-032-38059-3_13)          |
| 2026-09 | [MedVQA-2026-023](./Paper_Notes/Method/2027/MedVQA-2026-023_MD_LCT.md) · Learning to Trim: End-to-End Causal Graph Pruning with Dynamic Anatomical Feature Banks for Medical VQA | [DOI](https://doi.org/10.1007/978-3-032-38059-3_25)          |
| 2026-09 | [MedVQA-2026-038](./Paper_Notes/Method/2027/MedVQA-2026-038_MD_VIHD.md) · VIHD: Visual Intervention-Based Hallucination Detection for Medical Visual Question Answering | [DOI](https://doi.org/10.1007/978-3-032-38059-3_61)          |
| 2026-09 | [MedVQA-2026-058](./Paper_Notes/Method/2027/MedVQA-2026-058_MD_CARE.md) · CARE: Confidence-Aware Reasoning for Reliable Medical VQA | [DOI](https://doi.org/10.1007/978-3-032-38059-3_7)           |
| 2026-09 | [MedVQA-2026-062](./Paper_Notes/Method/2027/MedVQA-2026-062_MD_Med-CAP.md) · Med-CAP: Counterfactual Evidence and Adaptive Prior Suppression for Robust Medical Visual Question Answering | [DOI](https://doi.org/10.1007/978-3-032-38059-3_30)          |
| 2026-07 | [MedVQA-2026-055](./Paper_Notes/Method/2026/MedVQA-2026-055_MD_DE-CaGI.md) · Causal gradient intervention for debiased and evidence-grounded medical visual question answering | [DOI](https://doi.org/10.1016/j.media.2026.104226)           |
| 2026-06 | [MedVQA-2026-041](./Paper_Notes/Method/2026/MedVQA-2026-041_MD_DuCoR.md) · Dual-Level Confidence based Implicit Self-Refinement for Medical Visual Question Answering | [DOI](https://openaccess.thecvf.com/content/CVPR2026/html/Pan_Dual-Level_Confidence_based_Implicit_Self-Refinement_for_Medical_Visual_Question_Answering_CVPR_2026_paper.html) |
| 2026-05 | [MedVQA-2026-028](./Paper_Notes/Method/2026/MedVQA-2026-028_MD_AMPN.md) · Anomaly-aware mutual promotion network for medical visual question answering | [DOI](https://doi.org/10.1016/j.knosys.2026.115688)          |
| 2026-05 | [MedVQA-2026-031](./Paper_Notes/Method/2026/MedVQA-2026-031_MD_EMPO.md) · Entropy-Aware Multimodal Preference Optimization for Factuality Alignment in Medical Visual Question Answering | [DOI](https://doi.org/10.1109/icassp55912.2026.11460518)     |
| 2026-05 | [MedVQA-2026-037](./Paper_Notes/Method/2026/MedVQA-2026-037_MD_SG-UD.md) · Scene graph-guided uncertainty decomposition improves confidence calibration in surgical visual question answering | [DOI](https://doi.org/10.3389/fmed.2026.1849346)             |
| 2026-01 | [MedVQA-2026-013](./Paper_Notes/Method/2026/MedVQA-2026-013_MD_AMVQAMLSLWRPE.md) · Augmenting medical visual question answering with mixup, label smoothing, and layer-wise relevance propagation eXplainable Artificial Intelligence | [DOI](https://doi.org/10.7717/peerj-cs.3407)                 |
| 2025-12 | [MedVQA-2025-117](./Paper_Notes/Method/2025/MedVQA-2025-117_MD_DeCI.md) · Mitigating Language Bias in Medical VQA via Causally-Inspired Intervention | [DOI](https://doi.org/10.1109/bibm66473.2025.11356787)       |
| 2025-11 | [MedVQA-2025-102](./Paper_Notes/Method/2025/MedVQA-2025-102_MD_LMT-PlusPlus.md) · LMT++: Adaptively Collaborating LLMs With Multi-Specialized Teachers for Continual VQA in Robotic Surgical Videos | [DOI](https://doi.org/10.1109/tmi.2025.3581108)              |
| 2025-10 | [MedVQA-2025-097](./Paper_Notes/Method/2025/MedVQA-2025-097_MD_ECSA.md) · ECSA: Mitigating Catastrophic Forgetting and Few-Shot Generalization in Medical Visual Question Answering | [DOI](https://doi.org/10.3390/tomography11100115)            |
| 2025-10 | [MedVQA-2025-098](./Paper_Notes/Method/2026/MedVQA-2025-098_MD_CIMB-MVQA.md) · CIMB-MVQA: Causal intervention on modality-specific biases for medical visual question answering | [DOI](https://doi.org/10.1016/j.media.2025.103850)           |
| 2025-10 | [MedVQA-2025-100](./Paper_Notes/Method/2025/MedVQA-2025-100_MD_OmniDoctor.md) · OmniDoctor: Towards LLM-centric Lifelong Learning for New Emerging Medical VQA Tasks | [DOI](https://doi.org/10.1145/3746027.3755745)               |
| 2025-09 | [MedVQA-2025-030](./Paper_Notes/Method/2026/MedVQA-2025-030_MD_VASE.md) · Vision-Amplified Semantic Entropy for Hallucination Detection in Medical Visual Question Answering | [DOI](https://doi.org/10.1007/978-3-032-04971-1_63)          |
| 2025-09 | [MedVQA-2025-062](./Paper_Notes/Method/2025/MedVQA-2025-062_MD_CEDO.md) · Cause-Effect Driven Optimization for Robust Medical Visual Question Answering with Language Biases | [DOI](https://doi.org/10.24963/ijcai.2025/280)               |
| 2025-09 | [MedVQA-2025-076](./Paper_Notes/Method/2026/MedVQA-2025-076_MD_RoMed.md) · Knowing or Guessing? Robust Medical Visual Question Answering via Joint Consistency and Contrastive Learning | [DOI](https://doi.org/10.1007/978-3-032-05141-7_32)          |
| 2025-09 | [MedVQA-2025-079](./Paper_Notes/Method/2025/MedVQA-2025-079_MD_Cycle-VQA.md) · Cycle-VQA: A Cycle-Consistent Framework for Robust Medical Visual Question Answering | [DOI](https://doi.org/10.1016/j.patcog.2025.111609)          |
| 2025-09 | [MedVQA-2025-085](./Paper_Notes/Method/2026/MedVQA-2025-085_MD_DeCoCT.md) · Eliminating Language Bias for Medical Visual Question Answering with Counterfactual Contrastive Training | [DOI](https://doi.org/10.1007/978-3-032-04978-0_19)          |
| 2025-09 | [MedVQA-2025-087](./Paper_Notes/Method/2026/MedVQA-2025-087_MD_Med-BiasX.md) · Med-BiasX: Robust Medical Visual Question Answering with Language Biases | [DOI](https://doi.org/10.1007/978-3-032-05185-1_36)          |
| 2025-08 | [MedVQA-2025-045](./Paper_Notes/Method/2025/MedVQA-2025-045_MD_SCMLIMVQA.md) · Structure Causal Models and LLMs Integration in Medical Visual Question Answering | [DOI](https://doi.org/10.1109/tmi.2025.3564320)              |
| 2025-06 | [MedVQA-2025-029](./Paper_Notes/Method/2025/MedVQA-2025-029_MD_DiN.md) · DiN: Diffusion Model for Robust Medical VQA with Semantic Noisy Labels | [DOI](https://doi.org/10.1109/cvpr52734.2025.01337)          |
| 2025-04 | [MedVQA-2024-024](./Paper_Notes/Method/2025/MedVQA-2024-024_MD_VQA-UAD.md) · Language Models Meet Anomaly Detection for Better Interpretability and Generalizability | [DOI](https://doi.org/10.1007/978-3-031-84525-3_10)          |
| 2025-04 | [MedVQA-2025-034](./Paper_Notes/Method/2024/MedVQA-2025-034_MD_CNSPMLPMVQA.md) · Constructing Negative Sample Pairs to Mitigate Language Priors in Medical Visual Question Answering | [DOI](https://doi.org/10.1145/3715931.3715951)               |
| 2025-04 | [MedVQA-2025-041](./Paper_Notes/Method/2025/MedVQA-2025-041_MD_GVII.md) · A Global Visual Information Intervention Model for Medical Visual Question Answering | [DOI](https://doi.org/10.1016/j.compbiomed.2025.110195)      |
| 2025-01 | [MedVQA-2025-015](./Paper_Notes/Method/2025/MedVQA-2025-015_MD_Surgical-VQLA-PlusPlus.md) · Surgical-VQLA++: Adversarial contrastive learning for calibrated robust visual question-localized answering in robotic surgery | [DOI](https://doi.org/10.1016/j.inffus.2024.102602)          |
| 2024-12 | [MedVQA-2024-069](./Paper_Notes/Method/2024/MedVQA-2024-069_MD_CCIS-MVQA.md) · Counterfactual Causal-Effect Intervention for Interpretable Medical Visual Question Answering | [DOI](https://doi.org/10.1109/tmi.2024.3425533)              |
| 2024-12 | [MedVQA-2024-072](./Paper_Notes/Method/2024/MedVQA-2024-072_MD_OTMHSPMVQA.md) · Optimizing Transformer and MLP with Hidden States Perturbation for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/bibm62325.2024.10821987)       |
| 2024-10 | [MedVQA-2024-061](./Paper_Notes/Method/2024/MedVQA-2024-061_MD_MedCFVQA.md) · A Causal Approach to Mitigate Modality Preference Bias in Medical Visual Question Answering | [DOI](https://doi.org/10.1145/3689096.3689459)               |
| 2024-05 | [MedVQA-2024-029](./Paper_Notes/Method/2024/MedVQA-2024-029_MD_LLM-CL-VQA.md) · LLM-Assisted Multi-Teacher Continual Learning for Visual Question Answering in Robotic Surgery | [DOI](https://doi.org/10.1109/icra57147.2024.10610603)       |
| 2024-04 | [MedVQA-2024-019](./Paper_Notes/Method/2024/MedVQA-2024-019_MD_EGMVQATGGP.md) · Enhancing Generalization in Medical Visual Question Answering Tasks Via Gradient-Guided Model Perturbation | [DOI](https://doi.org/10.1109/icassp48485.2024.10446378)     |
| 2024-01 | [MedVQA-2024-013](./Paper_Notes/Method/2024/MedVQA-2024-013_MD_CMNIEN.md) · Cross-Modal Noise Information Elimination Network for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/nnice61279.2024.10498179)      |
| 2023-12 | [MedVQA-2023-002](./Paper_Notes/Method/2023/MedVQA-2023-002_MD_CopVQA.md) · Causal Reasoning through Two Cognition Layers for Improving Generalization in Visual Question Answering | [DOI](https://doi.org/10.18653/v1/2023.emnlp-main.573)       |
| 2023-10 | [MedVQA-2023-032](./Paper_Notes/Method/2023/MedVQA-2023-032_MD_CS-VQLA.md) · Revisiting Distillation for Continual Learning on Visual Question Localized-Answering in Robotic Surgery | [DOI](https://doi.org/10.1007/978-3-031-43996-4_7)           |
| 2023-10 | [MedVQA-2023-035](./Paper_Notes/Method/2023/MedVQA-2023-035_MD_DeBCF.md) · Debiasing Medical Visual Question Answering via Counterfactual Training | [DOI](https://doi.org/10.1007/978-3-031-43895-0_36)          |
| 2022-10 | [MedVQA-2022-016](./Paper_Notes/Method/2022/MedVQA-2022-016_MD_Anomaly-Matters.md) · Anomaly Matters: An Anomaly-Oriented Model for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/tmi.2022.3185113)              |
| 2022-10 | [MedVQA-2022-017](./Paper_Notes/Method/2022/MedVQA-2022-017_MD_VQAMix.md) · VQAMix: Conditional Triplet Mixup for Medical Visual Question Answering | [DOI](https://doi.org/10.1109/tmi.2022.3185008)              |

<a id="section-5.7"></a>

## 5.7. Agentic & Tool-augmented Systems

| Date    | Title                                                        | DOI                                                         |
| ------- | ------------------------------------------------------------ | ----------------------------------------------------------- |
| 2026-08 | [MedVQA-2026-057](./Paper_Notes/Method/2026/MedVQA-2026-057_MD_NCRAgent.md) · NCRAgent: A Neuro-Inspired Multiagent Framework for Transparent and Explainable Medical VQA | [DOI](https://doi.org/10.1109/tai.2026.3668173)             |
| 2026-05 | [MedVQA-2026-033](./Paper_Notes/Method/2026/MedVQA-2026-033_MD_SRD.md) · Multi-Agent Diagnostic Collaboration and Segmentation-Aware Residual Decoding for Hallucination-Resistant Medical VQA | [DOI](https://doi.org/10.1109/icassp55912.2026.11464397)    |
| 2026-01 | [MedVQA-2026-012](./Paper_Notes/Method/2026/MedVQA-2026-012_MD_SMR-agents.md) · SMR-agents: Synergistic medical reasoning agents for zero-shot medical visual question answering with MLLMs | [DOI](https://doi.org/10.1016/j.ipm.2025.104297)            |
| 2025-12 | [MedVQA-2025-073](./Paper_Notes/Method/2025/MedVQA-2025-073_MD_MACRRVQA.md) · A Multi-Agent System for Complex Reasoning in Radiology Visual Question Answering | [DOI](https://doi.org/10.1109/jcdl67857.2025.00025)         |
| 2025-11 | [MedVQA-2025-001](./Paper_Notes/Method/2025/MedVQA-2025-001_MD_AMANDA.md) · AMANDA: Agentic Medical Knowledge Augmentation for Data-Efficient Medical Visual Question Answering | [DOI](https://doi.org/10.18653/v1/2025.findings-emnlp.1350) |
| 2025-11 | [MedVQA-2025-005](./Paper_Notes/Method/2025/MedVQA-2025-005_MD_Med-VRAgent.md) · Med-VRAgent: A Framework for Medical Visual Reasoning-Enhanced Agents | [DOI](https://doi.org/10.18653/v1/2025.emnlp-main.939)      |
| 2025-10 | [MedVQA-2025-090](./Paper_Notes/Method/2025/MedVQA-2025-090_MD_MedDAF.md) · A Dynamic Agent Framework for Large Language Model Reasoning for Medical and Visual Question Answering | [DOI](https://doi.org/10.1109/iccvw69036.2025.00124)        |
| 2025-10 | [MedVQA-2025-095](./Paper_Notes/Method/2025/MedVQA-2025-095_MD_PathFinder.md) · PathFinder: A Multi-Modal Multi-Agent System for Medical Diagnostic Decision-Making Applied to Histopathology | [DOI](https://doi.org/10.1109/iccv51701.2025.02175)         |
| 2025-04 | [MedVQA-2025-035](./Paper_Notes/Method/2025/MedVQA-2025-035_MD_AMIE.md) · Towards conversational diagnostic artificial intelligence | [DOI](https://doi.org/10.1038/s41586-025-08866-7)           |
| 2024-11 | [MedVQA-2023-022](./Paper_Notes/Method/2024/MedVQA-2023-022_MD_ChatCAD-Plus.md) · ChatCAD+: Toward a Universal and Reliable Interactive CAD Using LLMs | [DOI](https://doi.org/10.1109/tmi.2024.3398350)             |
| 2024-11 | [MedVQA-2024-007](./Paper_Notes/Method/2024/MedVQA-2024-007_MD_MMedAgent.md) · MMedAgent: Learning to Use Medical Tools with Multi-modal Agent | [DOI](https://doi.org/10.18653/v1/2024.findings-emnlp.510)  |
| 2024    | [MedVQA-2024-003](./Paper_Notes/Method/2024/MedVQA-2024-003_MD_MDAgents.md) · MDAgents: An Adaptive Collaboration of LLMs for Medical Decision-Making | [DOI](https://doi.org/10.52202/079017-2522)                 |

Overall, research on Med-VQA methods has evolved from early feature fusion and attention-based modeling toward vision-language pre-training, cross-modal alignment, knowledge enhancement, retrieval augmentation, prompt learning, parameter-efficient fine-tuning, causal debiasing, explainable reasoning, difference-aware question answering, localized answering, and MLLM/Agent-driven open-ended medical question answering. This evolution indicates that the central challenge of Med-VQA is shifting from “how to predict the correct answer” to “how to perform reliable, explainable, verifiable, and interactive clinical reasoning grounded in medical evidence.”

# AI Use Statement

This literature collection was prepared with the assistance of artificial intelligence (AI) tools for literature organization, categorization, summarization, and language editing. AI was used to support information processing rather than to independently validate the included research. Classifications, summaries, and descriptions may contain omissions or inaccuracies. Readers are encouraged to consult the original publications for authoritative details, experimental results, and scientific conclusions.



