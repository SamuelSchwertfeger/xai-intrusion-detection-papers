# XAI for Intrusion Detection: Reading List

A curated list of papers on explainable AI (XAI) for network intrusion detection, maintained as part of my Ph.D. research at Augusta University.

Every entry has been checked against Crossref, arXiv, or the publisher's page. Papers are grouped by topic and ordered by year within each group.

## Contents

- [Foundations of XAI](#foundations-of-xai)
- [Surveys of XAI for Cybersecurity and Intrusion Detection](#surveys-of-xai-for-cybersecurity-and-intrusion-detection)
- [XAI Methods Applied to Network Intrusion Detection](#xai-methods-applied-to-network-intrusion-detection)
- [Evaluating Explanations in Security](#evaluating-explanations-in-security)
- [Benchmark Datasets and Critiques for NIDS](#benchmark-datasets-and-critiques-for-nids)

## Foundations of XAI
- **"Why Should I Trust You?": Explaining the Predictions of Any Classifier**. Ribeiro et al. *KDD*, 2016. [DOI](https://doi.org/10.1145/2939672.2939778) — Introduces LIME, which explains individual predictions of any classifier by fitting a local interpretable surrogate model.
- **A Unified Approach to Interpreting Model Predictions**. Lundberg, Lee. *NeurIPS*, 2017. [arXiv](https://arxiv.org/abs/1705.07874) — Introduces SHAP, a Shapley-value-based framework that unifies several feature attribution methods.
- **Axiomatic Attribution for Deep Networks**. Sundararajan et al. *ICML*, 2017. [arXiv](https://arxiv.org/abs/1703.01365) — Proposes Integrated Gradients, an attribution method for deep networks defined by the axioms of sensitivity and implementation invariance.
- **Anchors: High-Precision Model-Agnostic Explanations**. Ribeiro et al. *AAAI*, 2018. [DOI](https://doi.org/10.1609/aaai.v32i1.11491) — Proposes anchors, if-then rules that locally and sufficiently explain a model prediction with high precision and stated coverage.
- **Explainable Artificial Intelligence (XAI): Concepts, taxonomies, opportunities and challenges toward responsible AI**. Barredo Arrieta et al. *Information Fusion*, 2020. [DOI](https://doi.org/10.1016/j.inffus.2019.12.012) — Surveys XAI concepts and a taxonomy of explainability methods for machine learning models, with open challenges.

## Surveys of XAI for Cybersecurity and Intrusion Detection
- **Explainable Intrusion Detection Systems (X-IDS): A Survey of Current Methods, Challenges, and Opportunities**. Neupane et al. *IEEE Access*, 2022. [DOI](https://doi.org/10.1109/ACCESS.2022.3216617) — Reviews explainability methods used in intrusion detection systems and discusses open challenges.
- **Explainable Artificial Intelligence in CyberSecurity: A Survey**. Capuano et al. *IEEE Access*, 2022. [DOI](https://doi.org/10.1109/ACCESS.2022.3204171) — Surveys XAI applications across cybersecurity tasks, organized by application domain and explanation approach.
- **Explainable artificial intelligence for cybersecurity: a literature survey**. Charmet et al. *Annals of Telecommunications*, 2022. [DOI](https://doi.org/10.1007/s12243-022-00926-7) — Reviews the literature on XAI for cybersecurity, covering both defensive uses and attacks on explanations.
- **SoK: Explainable Machine Learning for Computer Security Applications**. Nadeem et al. *IEEE EuroS&P*, 2023. [DOI](https://doi.org/10.1109/EuroSP57164.2023.00022) — Systematizes how explainable ML is used in security applications and assesses the explanation methods and evaluation practices in those works.
- **A Survey on Explainable Artificial Intelligence for Cybersecurity**. Rjoub et al. *IEEE TNSM*, 2023. [DOI](https://doi.org/10.1109/TNSM.2023.3282740) — Surveys XAI techniques applied to cybersecurity problems and their use in network and service management.
- **Explainable Intrusion Detection for Cyber Defences in the Internet of Things: Opportunities and Solutions**. Moustafa et al. *IEEE COMST*, 2023. [DOI](https://doi.org/10.1109/COMST.2023.3280465) — Surveys explainable intrusion detection for IoT and discusses open challenges and solutions.

## XAI Methods Applied to Network Intrusion Detection
- **An Adversarial Approach for Explainable AI in Intrusion Detection Systems**. Marino et al. *IECON*, 2018. [DOI](https://doi.org/10.1109/IECON.2018.8591457) — Uses adversarial samples to explain misclassifications of an intrusion detection classifier by identifying the features that must change.
- **LEMNA: Explaining Deep Learning based Security Applications**. Guo et al. *ACM CCS*, 2018. [DOI](https://doi.org/10.1145/3243734.3243792) — Proposes an explanation method tailored to security models with feature dependencies, evaluated on binary-analysis and malware tasks.
- **An Explainable Machine Learning Framework for Intrusion Detection Systems**. Wang et al. *IEEE Access*, 2020. [DOI](https://doi.org/10.1109/ACCESS.2020.2988359) — Applies SHAP to an intrusion detection model to give local and global explanations on NSL-KDD.
- **DeepAID: Interpreting and Improving Deep Learning-based Anomaly Detection in Security Applications**. Han et al. *ACM CCS*, 2021. [DOI](https://doi.org/10.1145/3460120.3484589) — Proposes an interpretation method for unsupervised deep anomaly detectors in security and uses it to improve those detectors.
- **Evaluating Standard Feature Sets Towards Increased Generalisability and Explainability of ML-based Network Intrusion Detection**. Sarhan et al. *Big Data Research*, 2022. [DOI](https://doi.org/10.1016/j.bdr.2022.100359) — Compares NetFlow-based feature sets across datasets for generalisability and uses feature-importance analysis to study explainability.
- **"Why Should I Trust Your IDS?": An Explainable Deep Learning Framework for Intrusion Detection Systems in Internet of Things Networks**. Houda et al. *IEEE OJ-COMS*, 2022. [DOI](https://doi.org/10.1109/OJCOMS.2022.3188750) — Proposes a deep-learning IDS for IoT networks combined with post-hoc explanation of its decisions.
- **Explainable AI for Intrusion Detection Systems: LIME and SHAP Applicability on Multi-Layer Perceptron**. Gaspar et al. *IEEE Access*, 2024. [DOI](https://doi.org/10.1109/ACCESS.2024.3368377) — Applies LIME and SHAP to a multi-layer perceptron intrusion detector and compares the resulting explanations.

## Evaluating Explanations in Security
- **Sanity Checks for Saliency Maps**. Adebayo et al. *NeurIPS*, 2018. [arXiv](https://arxiv.org/abs/1810.03292) — Proposes randomization tests showing that some saliency methods are insensitive to model parameters and training data.
- **Evaluating Explanation Methods for Deep Learning in Security**. Warnecke et al. *IEEE EuroS&P*, 2020. [DOI](https://doi.org/10.1109/EuroSP48549.2020.00018) — Proposes criteria to compare explanation methods in security tasks and evaluates several methods against them.
- **Can We Trust Your Explanations? Sanity Checks for Interpreters in Android Malware Analysis**. Fan et al. *IEEE TIFS*, 2021. [DOI](https://doi.org/10.1109/TIFS.2020.3021924) — Applies sanity checks and robustness tests to interpretation methods for Android malware detectors.
- **Dos and Don'ts of Machine Learning in Computer Security**. Arp et al. *USENIX Security*, 2022. [URL](https://www.usenix.org/conference/usenixsecurity22/presentation/arp) — Identifies common pitfalls in ML-based security research, assesses their prevalence in the literature, and gives recommendations.
- **AI/ML for Network Security: The Emperor has no Clothes**. Jacobs et al. *ACM CCS*, 2022. [DOI](https://doi.org/10.1145/3548606.3560609) — Examines ML models for network security with explainability methods and finds that high reported accuracy can rest on unintended shortcuts.

## Benchmark Datasets and Critiques for NIDS
- **Outside the Closed World: On Using Machine Learning for Network Intrusion Detection**. Sommer, Paxson. *IEEE S&P*, 2010. [DOI](https://doi.org/10.1109/SP.2010.25) — Explains why ML for network intrusion detection is difficult to deploy and gives guidelines for evaluation.
- **UNSW-NB15: A Comprehensive Data Set for Network Intrusion Detection Systems**. Moustafa, Slay. *MilCIS*, 2015. [DOI](https://doi.org/10.1109/MilCIS.2015.7348942) — Presents the UNSW-NB15 dataset of mixed normal and synthetic attack traffic.
- **Toward Generating a New Intrusion Detection Dataset and Intrusion Traffic Characterization**. Sharafaldin et al. *ICISSP*, 2018. [DOI](https://doi.org/10.5220/0006639801080116) — Presents the CIC-IDS2017 dataset and the criteria used to design it.
- **Troubleshooting an Intrusion Detection Dataset: the CICIDS2017 Case Study**. Engelen et al. *IEEE SPW*, 2021. [DOI](https://doi.org/10.1109/SPW53761.2021.00009) — Documents labelling and traffic-generation problems in CIC-IDS2017 and provides a corrected version.
- **Bad Design Smells in Benchmark NIDS Datasets**. Flood et al. *IEEE EuroS&P*, 2024. [DOI](https://doi.org/10.1109/EuroSP60621.2024.00042) — Catalogues design flaws in widely used NIDS benchmark datasets and shows their effect on evaluation.

## Suggestions

Know a paper that belongs here? Open an issue with the title and a DOI or official link.

## License

[CC0 1.0](LICENSE). To the extent possible under law, the author has waived all copyright to this list.
