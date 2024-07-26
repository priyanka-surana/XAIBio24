# 1. Artificial Intelligence in Genomics #

Artificial intelligence (AI) has revolutionized the field of genomics by enabling the analysis of vast and complex datasets to uncover previously unattainable insights. AI techniques, particularly machine learning (ML) and deep learning (DL), have been instrumental in various genomic applications.

AI has significantly improved the accuracy and efficiency of variant calling, which involves identifying variations in DNA sequences such as single nucleotide polymorphisms (SNPs) and insertions/deletions (indels). Tools like DeepVariant, developed by Google, utilize DL models to achieve high accuracy in variant calling from sequencing data. Additionally, AI-based methods for motif discovery help identify regulatory elements in DNA sequences, enhancing our understanding of gene regulation.

Moreover, machine learning algorithms have been employed to identify differentially expressed genes across various conditions, aiding in the discovery of disease biomarkers and therapeutic targets. Furthermore, DL models have been used to quantify gene expression levels from RNA sequencing data, providing more accurate and robust measurements compared to traditional methods.

Nonetheless, AI has been used to study DNA methylation patterns and histone modifications, which are crucial for gene regulation. Tools like DeepCpG integrate genomic and epigenomic data to predict DNA methylation states, offering insights into the regulatory mechanisms underlying gene expression.

Moreover, genome-wide association studies (GWAS) have benefited from AI techniques that can handle large-scale data to identify genetic variants associated with complex traits and diseases. Additionally, ML models have been used to calculate polygenic risk scores, which estimate an individual’s genetic predisposition to certain diseases based on the cumulative effect of multiple genetic variants.

AI-driven pharmacogenomics studies explore how genetic variations affect individual responses to drugs, paving the way for personalized treatment strategies. Moreover, AI models have been developed to predict genetic risk for various diseases, enabling early diagnosis and preventive measure.

# 2. Microbial Genomics #

Microbial genomics, the study of the genomes of microorganisms, has been profoundly impacted by advances in AI. The complexity and diversity of microbial communities present unique challenges that AI is well-suited to address.

AI methods have enhanced the characterization of microbial communities by analyzing metagenomic data, which involves sequencing the genetic material of entire communities. Tools like CheckM2 utilize ML algorithms to assess microbial genomes quality from metagenomic data accurately. 

AI has been instrumental in studying the interactions between host genomes and their associated microbiomes. Machine learning models can integrate host and microbial genomic data to uncover how these interactions influence health and disease (Knights et al., 2011). For example, AI has been used to predict different types of cancer based on alterations in the composition of the microbiome.

AI approaches have been employed to predict the functions of microbial genes and proteins, which is essential for understanding microbial physiology and ecology. Tools like Prodigal and DeepARG use ML algorithms to annotate microbial genes and predict their functions, contributing to our knowledge of microbial metabolic pathways and resistance mechanisms.

Nevertheless, machine learning can be utilized to study the resistome profile of different pathogens. Different ML models have been developed to predict genes involved in the resistance pathways, the resistance phenotype, or the minimum inhibitory concentration of antibiotics.   

# 3. Explainable AI (XAI)

The need for transparency and interpretability in AI models has grown as AI becomes increasingly integrated into genomics and microbial genomics. Explainable AI (XAI) aims to make AI models more understandable to humans, enhancing trust and facilitating the adoption of AI in critical applications.

XAI techniques have been applied to genomic data to interpret the predictions of ML and DL models. For instance, SHAP (SHapley Additive exPlanations) values have been used to provide a global understanding of the model by explaining the contribution of individual features to the final output. Additionally, LIME (Local Interpretable Model-agnostic Explanations) focuses on explaining the model’s prediction for individual instances and hence it provides local explainability.

In microbial genomics, XAI approaches help elucidate the factors driving microbial community composition and function predictions. For example, feature importance scores from ML models can reveal which microbial taxa or genes are most influential in predicting host health outcomes, providing insights into potential therapeutic targets.

The use of XAI in genomics and microbial genomics also addresses ethical concerns by ensuring that AI models are not black boxes. This transparency is crucial for clinical applications, where understanding the rationale behind AI predictions can inform medical decisions and foster trust among healthcare professionals and patients.

# 4. Aim

This study aims to assess six of the most well-established AI models in the field of microbial genomics to evaluate their efficiency, scalability, interoperability, fairness, trust, and robustness and apply necessary changes to the models to reach the best performance with the benefits of the explainable artificial intelligence approach.

# 5. The Models
**1. Antimicrobial resistance**

a. [code](https://github.com/erolkavvas/microbial_AMR_ML/?tab=readme-ov-file), [Paper](https://www.nature.com/articles/s41467-018-06634-y)

b. [code](https://github.com/SumayahR/antibiotic-resistance), [Paper](https://doi.org/10.1128/msystems.00123-17)

c. [code](https://github.com/PATRIC3/mic_prediction), [Paper](https://doi.org/10.1128/jcm.01260-18)

**2. Microbiome**

a. [code](https://github.com/chklovski/CheckM2/tree/main), [Paper](https://www.nature.com/articles/s41592-023-01940-w)
