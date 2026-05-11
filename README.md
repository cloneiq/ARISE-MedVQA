# ARISE-MedVQA
**From Passive Answering to Active Inquiry: A Review of Medical Visual Question Answering Toward ARISE-MedVQA**
Medical Visual Question Answering (Med-VQA) generates answers from medical images, connecting image understanding, language interaction, and clinical decision support. While Med-VQA has evolved to handle more complex multimodal tasks, current methods assume well-posed questions and sufficient evidence, neglecting the ongoing, dynamic nature of real clinical diagnosis, which requires active verification and incremental evidence gathering. This paper identifies the misalignment between Med-VQA’s  answering paradigm and the real-world evidence-based closed-loop process. We review Med-VQA’s progress, highlighting key challenges in answerability modeling, evidence gap identification, and stable updates. We propose a shift towards risk-aware, evidence-based diagnostic interaction, structured around a closed-loop framework of answerability, evidence gap identification, and multimodal evidence fusion. Finally, we outline a research agenda focused on data, evaluation, methods, safety, and application, emphasizing that the future of Med-VQA should focus on "when to answer, when to ask, and how to update diagnoses," advancing toward interactive intelligence for real diagnostic processes.

# Reviews
[1] **Task-Specific Models vs. Large Vision-Language Models in medical visual question answering: A Survey**<br>
	     Huahu Xu, Qishen Chen, Wenxuan He, Xingyuan Chen, [Honghao Gao](https://scholar.google.com/citations?user=PiiIpJIAAAAJ&amp;amp;hl=zh-CN) <br>
		 Expert Systems with Applications [2026-03-12] [[DOI](https://doi.org/10.1016/j.eswa.2026.132008)]

[2] **From visual question answering to intelligent AI agents in ophthalmology**    <br>
		 Xiaolan Chen, Ruoyu Chen, Pusheng Xu, Xiaojie Wan, Weiyi Zhang, Bingjie Yan, Xianwen Shang, Mingguang He, Danli Shi<br>
		 British Journal of Ophthalmology [2026-01-01] [[DOI](https://doi.org/10.1136/bjo-2024-326097)]

[3] **Generative Models in Medical Visual Question Answering: A Survey**<br>
	     Wenjie Dong, Shuhao Shen, Yuqiang Han, Tao Tan, Jian Wu, Hongxia Xu<br>
	     Applied Sciences [2025-03-10] [[PDF](https://www.mdpi.com/2076-3417/15/6/2983/pdf)] [[DOI](https://doi.org/10.3390/app15062983)]

[4] **Visual Question Answering in Robotic Surgery: A Comprehensive Review**<br>
	     Di Ding, Tianliang Yao, Rong Luo, Xusen Sun<br>
	     IEEE Access [2025-01-01] [[PDF](https://doi.org/10.1109/ACCESS.2024.3525145)] [[DOI](https://doi.org/10.1109/ACCESS.2024.3525145)]

[5] **Vision-language models for medical report generation and visual question answering: a review**<br>
	     Iryna Hartsock, Ghulam Rasool<br>
	     Frontiers in Artificial Intelligence [2024-11-19]  [[Arxiv](https://arxiv.org/pdf/2403.02469)] [[DOI](https://doi.org/10.3389/frai.2024.1430984)]

[6] **Developing ChatGPT for biology and medicine: a complete review of biomedical question answering**<br>
	     Qing Li, Lei Li, Yu Li<br>
	     Biophysics Reports [2024-06-01] [[PDF](https://www.biophysics-reports.org/en/article/pdf/preview/10.52601/bpr.2024.240004.pdf)] [[DOI](https://doi.org/10.52601/bpr.2024.240004)]

[7] **Survey of Multimodal Medical Question Answering**<br>
	     Hilmi Demirhan, Wlodek W. Zadrozny<br>
	     BioMedInformatics [2024-01-02] [[PDF](https://www.mdpi.com/2673-7426/4/1/4/pdf)] [[DOI](https://doi.org/10.3390/biomedinformatics4010004)]

[8] **Medical visual question answering: A survey**<br>
	       Zhihong Lin, Donghao Zhang, Qingyi Tao, Danli Shi, Gholamreza Haffari, Qi Wu, Mingguang He, Zongyuan Ge<br>
	       Artificial Intelligence in Medicine [2023-09-01] [[Arxiv](https://arxiv.org/pdf/2111.10056)] [[DOI](https://doi.org/10.1016/j.artmed.2023.102611)]

[9] **A comprehensive interpretation for medical VQA: Datasets, techniques, and challenges**<br>
	       Sheerin Sitara Noor Mohamed, Kavitha Srinivasan<br>
	       Journal of Intelligent & Fuzzy Systems [2023-04-03] [[DOI](https://doi.org/10.3233/JIFS-222569)]

[10] **A Critical Analysis of Benchmarks, Techniques, and Models in Medical Visual Question Answering**<br>
	       Suheer Ali Al-Hadhrami, Mohamed El Bachir Menai, Saad Al-Ahmadi, Ahmad Alnafessah<br>
	       IEEE Access [2023-01-01]   [[PDF](https://ieeexplore.ieee.org/iel7/6287639/6514899/10323452.pdf)] [[DOI](https://doi.org/10.1109/ACCESS.2023.3335216)]

[11] **Visual question answering in the medical domain based on deep learning approaches: A comprehensive study**<br>
	       Aisha Al-Sadi, Mahmoud Al-Ayyoub, Yaser Jararweh, Fumie Costen<br>
	       Pattern Recognition Letters [2021-10] [[PDF](https://pure.manchester.ac.uk/ws/portalfiles/portal/195767002/mahmoud1.pdf)] [[DOI](https://doi.org/10.1016/j.patrec.2021.07.002)]

# Datasets (Open Access)

## 1.1 Early Medical Visual Question Answering Datasets

[1] **VQA-RAD**, A dataset of clinically generated visual questions and answers about radiology images<br>
J. J. Lau, et al.<br>
Scientific Data [2018]

[2] **VQA-Med 2019**, VQA-MED: Overview of the medical visual question answering task at ImageCLEF 2019<br>
A. B. Abacha, et al.<br>
CLEF Working Notes [2019]

[3] **VQA-Med 2020**, Overview of the VQA-Med Task at ImageCLEF 2020: Visual Question Answering and Generation in the Medical Domain<br>
A. B. Abacha, et al.<br>
CLEF Working Notes [2020]

[4] **SLAKE**, Slake: A semantically-labeled knowledge-enhanced dataset for medical visual question answering<br>
B. Liu, et al.<br>
ISBI [2021]

[5] **PathVQA**, Towards visual question answering on pathology images<br>
X. He, et al.<br>
ACL-IJCNLP [2021]

[6] **OVQA**, OVQA: A clinically generated visual question answering dataset<br>
Y. Huang, et al.<br>
SIGIR [2022]

[7] **P-VQA**, Medical knowledge-based network for patient-oriented visual question answering<br>
J. Huang, et al.<br>
Information Processing & Management [2023]

## 1.2 Large-Scale General Medical VQA Datasets

[8] **PMC-OA**, PMC-CLIP: Contrastive language-image pre-training using biomedical documents<br>
W. Lin, et al.<br>
MICCAI [2023]

[9] **PMC-VQA**, Development of a large-scale medical visual question-answering dataset<br>
Xiaoman Zhang, Chaoyi Wu, Ziheng Zhao, Weixiong Lin, Ya Zhang, Yanfeng Wang, Weidi Xie<br>
Communications Medicine [2024-12] [PDF] [DOI]

[10] **PubMedVision**, Towards Injecting Medical Visual Knowledge into Multimodal LLMs at Scale<br>
J. Chen, et al.<br>
EMNLP [2024]

[11] **OmniMedVQA**, OmniMedVQA: A New Large-Scale Comprehensive Evaluation Benchmark for Medical LVLM<br>
Y. Hu, et al.<br>
CVPR [2024]

[12] **M3D-VQA**, M3D: Advancing 3D medical image analysis with multi-modal large language models<br>
F. Bai, et al.<br>
arXiv preprint [2024]

[13] **3D-RAD**, 3D-RAD: A comprehensive 3D radiology Med-VQA dataset with multi-temporal analysis and diverse diagnostic tasks<br>
X. Gai, et al.<br>
arXiv preprint [2025]

[14] **RadImageNet-VQA**, RadImageNet-VQA: A Large-Scale CT and MRI Dataset for Radiologic Visual Question Answering<br>
L. Butsanets, et al.<br>
MIDL [2026]

[15] **MedMax**, MedMax: Mixed-modal instruction tuning for training biomedical assistants<br>
H. Bansal, et al.<br>
NeurIPS [2026]

## 1.3 Chest X-ray VQA and Report-Driven Question Answering Datasets

[16] **EHRXQA / MIMIC-Ext-MIMIC-CXR-VQA**, EHRXQA: A Multi-Modal Question Answering Dataset for Electronic Health Records with Chest X-ray Images<br>
S. Bae, et al.<br>
NeurIPS [2023]

[17] **Medical-Diff-VQA**, Expert Knowledge-Aware Image Difference Graph Representation Learning for Difference-Aware Medical Visual Question Answering<br>
X. Hu, et al.<br>
KDD [2023]

[18] **Medical-CXR-VQA**, Interpretable medical image Visual Question Answering via multi-modal relationship graph learning<br>
X. Hu, et al.<br>
Medical Image Analysis [2024]

[19] **RadDialog**, Radialog: Large vision-language models for X-ray reporting and dialog-driven assistance<br>
C. Pellegrini, et al.<br>
MIDL [2025]

[20] **VinDr-CXR-VQA**, VinDr-CXR-VQA: A Visual Question Answering Dataset for Explainable Chest X-Ray Analysis with Multi-Task Learning<br>
H.-D. Nguyen, et al.<br>
ISBI [2025]

[21] **ReXVQA**, ReXVQA: A Large-scale Visual Question Answering Benchmark for Generalist Chest X-ray Understanding<br>
A. Pal, et al.<br>
arXiv preprint arXiv:2506.04353 [2025]

[22] **GEMeX-VQA**, GEMeX: A large-scale, groundable, and explainable medical VQA benchmark for chest X-ray diagnosis<br>
B. Liu, et al.<br>
ICCV [2025]

[23] **GEMeX-RMCoT**, GEMeX-RMCoT: An Enhanced Med-VQA Dataset for Region-Aware Multimodal Chain-of-Thought Reasoning<br>
B. Liu, et al.<br>
ACM Multimedia [2025]

[24] **MIMIC-Ext-CXR-QBA**, A Structured, Tagged, and Localized Visual Question Answering Dataset with Full Sentence Answers and Scene Graphs for Chest X-ray Images<br>
P. Müller, et al.<br>
ICLR [2026]

[25] **MIMIC-CXR-VQA**, MIMIC-CXR-VQA: A Medical Visual Question Answering Dataset Constructed with LLaMA-based Annotations<br>
M. Aas-Alas, et al.<br>
MIDL [2026]

[26] **DAMON-VQA**, DAMON: Difference-Aware Medical Visual Question Answering via Multimodal Large Language Model<br>
Z. Zhang, et al.<br>
IEEE Journal of Biomedical and Health Informatics [2026]

## 1.4 Specialty-Specific VQA Datasets

### 1.4.1 Ophthalmology VQA

[27] **DME-VQA**, Consistency-preserving visual question answering in medical imaging<br>
S. Tascon-Morales, P. Márquez-Neila, R. Sznitman<br>
MICCAI [2022]

[28] **OphthalVQA**, Unveiling the clinical incapabilities: a benchmarking study of GPT-4V(ision) for ophthalmic multimodal image analysis<br>
P. Xu, et al.<br>
British Journal of Ophthalmology [2024]

[29] **OphthalWeChat**, Benchmarking large multimodal models for ophthalmic visual question answering with OphthalWeChat<br>
P. Xu, et al.<br>
Advances in Ophthalmology Practice and Research [2026]

### 1.4.2 Pathology and Whole Slide Image VQA

[30] **WSI-VQA**, WSI-VQA: Interpreting Whole Slide Images by Generative Visual Question Answering<br>
P. Chen, et al.<br>
ECCV [2024]

[31] **QuiltVQA-RED / Quilt-VQA / Quilt-LLaVA-Instruct-107K**, Quilt-LLaVA: Visual Instruction Tuning by Extracting Localized Narratives from Open-Source Histopathology Videos<br>
M. S. Seyfioglu, et al.<br>
CVPR [2024]

### 1.4.3 Gastrointestinal Endoscopy and Digestive-Tract VQA

[32] **MEDVQA-GI**, Overview of ImageCLEFmedical 2023: Medical Visual Question Answering for Gastrointestinal Tract<br>
S. Hicks, et al.<br>
CLEF Working Notes [2023]

[33] **Kvasir-VQA**, Kvasir-VQA: A Text-Image Pair GI Tract Dataset<br>
S. Gautam, et al.<br>
International Workshop on Vision-Language Models for Biomedical Applications [2024]

[34] **Kvasir-VQA-x1**, Kvasir-VQA-x1: A Multimodal Dataset for Medical Reasoning and Robust MedVQA in Gastrointestinal Endoscopy<br>
S. Gautam, M. A. Riegler, P. Halvorsen<br>
MICCAI Workshop on Data Engineering in Medical Imaging [2025]

[35] **ColonINST**, Frontiers in Intelligent Colonoscopy<br>
G.-P. Ji, et al.<br>
Machine Intelligence Research [2026]

### 1.4.4 Surgical and Robotic Surgery VQA

[36] **Cholec80-VQA**, Surgical-VQA: Visual Question Answering in Surgical Scenes Using Transformer<br>
L. Seenivasan, et al.<br>
MICCAI [2022]

[37] **EndoVis-18-VQA**, Surgical-VQA: Visual Question Answering in Surgical Scenes Using Transformer<br>
L. Seenivasan, et al.<br>
MICCAI [2022]

[38] **PitVQA**, PitVQA: Image-Grounded Text Embedding LLM for Visual Question Answering in Pituitary Surgery<br>
R. He, et al.<br>
MICCAI [2024]

[39] **SSG-VQA**, Advancing surgical VQA with scene graph knowledge<br>
K. Yuan, et al.<br>
International Journal of Computer Assisted Radiology and Surgery [2024]

[40] **Surg-396K**, EndoChat: Grounded multimodal large language model for endoscopic surgery<br>
G. Wang, et al.<br>
Medical Image Analysis [2025]

[41] **EndoVis-17-VQLA / EndoVis-18-VQLA Extensions**, Surgical-VQLA++: Adversarial contrastive learning for calibrated robust visual question-localized answering in robotic surgery<br>
L. Bai, et al.<br>
Information Fusion [2025]

[42] **EndoBench**, EndoBench: A comprehensive evaluation of multi-modal large language models for endoscopy analysis<br>
S. Liu, et al.<br>
NeurIPS [2025]

### 1.4.5 Dermatology, Wound Care, and Mammography VQA

[43] **DermaVQA**, DermaVQA: A Multilingual Visual Question Answering Dataset for Dermatology<br>
W.-w. Yim, et al.<br>
MICCAI [2024]

[44] **WoundcareVQA**, WoundcareVQA: A multilingual visual question answering benchmark dataset for wound care<br>
W.-w. Yim, et al.<br>
Journal of Biomedical Informatics [2025]

[45] **MammoVQA**, A Benchmark for Breast Cancer Screening and Diagnosis in Mammogram Visual Question Answering<br>
J. Zhu, et al.<br>
Nature Communications [2025]

[46] **DermaVQA-DAS**, DermaVQA-DAS: Dermatology Assessment Schema (DAS) & Datasets for Closed-Ended Question Answering & Segmentation in Patient-Generated Dermatology Images<br>
W.-w. Yim, et al.<br>
arXiv preprint arXiv:2512.24340 [2025]

## 1.5 Localized, Explainable, and Reasoning-Enhanced VQA Datasets

[47] **RIS-VQA**, Localized questions in medical visual question answering<br>
S. Tascon-Morales, P. Márquez-Neila, R. Sznitman<br>
MICCAI [2023]

[48] **INSEGCAT-VQA**, Localized questions in medical visual question answering<br>
S. Tascon-Morales, P. Márquez-Neila, R. Sznitman<br>
MICCAI [2023]

[49] **EndoVis-17-VQLA / EndoVis-18-VQLA**, Surgical-VQLA: Transformer with Gated Vision-Language Embedding for Visual Question Localized-Answering in Robotic Surgery<br>
L. Bai, et al.<br>
ICRA [2023]

[50] **MedThink**, MedThink: A Rationale-Guided Framework for Explaining Medical Visual Question Answering<br>
X. Gai, et al.<br>
Findings of ACL: NAACL [2025]

[51] **Med-SER**, Med-SER: Enhancing Reasoning Interpretability in Medical Visual Question Answering via Structured Chain-of-Thought<br>
J. Qiao, et al.<br>
BIBM [2025]

[52] **MeCoVQA**, Towards a multimodal large language model with pixel-level insight for biomedicine<br>
X. Huang, et al.<br>
AAAI [2025]

[53] **C-SLAKE**, Consistency Conditioned Memory Augmented Dynamic Diagnosis Model for Medical Visual Question Answering<br>
T. Yu, et al.<br>
IEEE Journal of Biomedical and Health Informatics [2025]

## 1.6 Medical Education, Examination, Multi-Source Data, and Interactive Question Answering Resources

[54] **MMMD**, A Multilingual Multimodal Medical Examination Dataset for Visual Question Answering in Healthcare<br>
G. Riccio, et al.<br>
CBMS [2025]

[55] **MEDSQ**, MEDSQ: Towards personalized medical education via multi-form interaction guidance<br>
Y. Ouyang, et al.<br>
Expert Systems with Applications [2025]

[56] **MedFrameQA**, MedFrameQA: A Multi-Image Medical VQA Benchmark for Clinical Reasoning<br>
S. Yu, et al.<br>
arXiv preprint arXiv:2505.16964 [2025]

[57] **MedDQA**, Integration of Multi-Source Medical Data for Medical Diagnosis Question Answering<br>
Q. Peng, et al.<br>
IEEE Transactions on Medical Imaging [2025]

[58] **SilVar-Med**, SilVar-Med: A Speech-Driven Visual Language Model for Explainable Abnormality Detection in Medical Imaging<br>
T.-H. Pham, et al.<br>
CVPR [2025]
Information Processing & Management [2023]

# Methods (Selected)

**Related papers are being continuously updated...**
