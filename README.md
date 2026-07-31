# EEDPF-LA: Systematic Review on Student Dropout Prediction in Latin America

Welcome to the official repository for the supplementary material (Open Science) of the scientific article: 
**"Machine Learning Predictive Models and Determinants of Student Dropout in Higher Education in Latin America: A Systematic Literature Review"**.

This repository has been created to ensure full transparency, traceability, and reproducibility of our Systematic Literature Review (SLR), conducted following the strict guidelines of the **PRISMA 2020** statement.

---

## Study Summary
Despite the proven effectiveness of Machine Learning classifiers internationally, their direct extrapolation to the Latin American context presents empirical and methodological gaps. This study systematically analyzes 156 primary research articles to evaluate predictive architectures, the treatment of imbalanced classes (e.g., SMOTE vs. GANs), and the integration of Explainable Artificial Intelligence (XAI) techniques.

As a core theoretical contribution, the article proposes the **EEDPF-LA** (*Explainable Educational Dropout Prediction Framework for Latin America*), a five-layer architecture aimed at overcoming the "black box" predictive approach and fostering prescriptive and hyper-personalized pedagogical interventions.

### Research Questions (RQs) addressed:
* **RQ1:** Which predictor variables (academic, socioeconomic, institutional, or demographic) have the highest prevalence and algorithmic impact identified in dropout prediction models in Latin America?
* **RQ2:** Which machine learning architectures report the highest implementation frequency and comparative effectiveness in recent regional literature?
* **RQ3:** What performance metrics and preprocessing techniques (for imbalanced classes) constitute the evaluation standard of methodological rigor in these empirical studies?

---

## Repository Structure

In this repository, you will find the detailed methodological inputs used in the study:

* **`Search_Strings.txt`**: Contains the exact parameterization of the boolean search equations applied in Scopus, Web of Science (WoS), IEEE Xplore, and the ACM Digital Library.
* **`PrismaDataExtraction.csv`**: The consolidated data extraction matrix. It contains the manual coding of the 12 analytical dimensions extracted from the 156 primary studies in the final sample.
* **`prisma_diagram.pdf`**: The complete PRISMA 2020 flow diagram, detailing the inclusion and exclusion of records at each phase.
* **`VOSviewer_Files.zip`**: Relational datasets exported for the generation of the bibliometric co-occurrence (thematic evolution) and co-authorship networks analyzed in Chapter 4.

---

## About the Framework (EEDPF-LA)
The proposed framework consolidates the regional state-of-the-art into 5 sequential layers:
1. **Data Ingestion and Governance** (DAMA-DMBOK validation and Privacy *by-design*).
2. **Preprocessing and Synthetic Balancing** using Generative Adversarial Networks (CTGAN / WGAN-GP).
3. **Hybrid Predictive Model** (Tree-based Ensembles + Recurrent Neural Networks/LSTM).
4. **Explainable AI (XAI)** (Local and global model-agnostic techniques such as SHAP and LIME).
5. **Intervention and User Experience (UX)** (Learning Analytics Dashboards centered on reducing the academic manager's cognitive load).

---

## Contact
For questions regarding the methodology, data analysis, or potential research collaborations, please feel free to open an *Issue* in this repository or contact the authors of the article directly.

