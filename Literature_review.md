# Literature review 
By Mercedes Didier Garnham

## About the project:
This project focuses on conducting a comprehensive literature review and testing vstate-of-the-art models for Explainable AI (XAI) in the context of genomic research. Explainable AI is crucial for ensuring transparency and interpretability in AI-driven analysis, which is particularly important in the field of genomics. The project will focus on Generative and Synthetic Genomics and Human Genetics
The Generative and Synthetic Genomics topic merges large-scale data generation with artificial intelligence to pioneer advances in predictive and programmable molecular biology. This aims to revolutionize the routine synthesis and engineering of genomes, enabling more precise and customizable approaches to genetic manipulation.
Human Genetics focus on developmental disorders and diseases affecting the blood and immune system, this program is at the forefront of elucidating the complex genetic factors that contribute to these conditions. By integrating innovative research methods and extensive genetic data, the programme aims to enhance our understanding of how genetic variations influence health and disease, ultimately driving improvements in diagnosis and treatment.

## Bibliographic Search Process:
I conducted a comprehensive search using major academic databases, specifically PubMed and Google Scholar. I employed a range of keywords including Artificial Intelligence, Machine Learning, Python, and Model. To narrow down the search to my specific interests, I added project-related keywords such as "Generative Genomics", "Synthetic Genomics", "Synthetic Biology", and "Human Genomics". I also explored GitHub using the same set of keywords. 
I focused on publications from the past five years to ensure the relevance and recency of the research.For each publication, I assessed the number of citations and the overall quality of the publication. Upon opening a publication, I searched for terms like "code availability", "GitHub", "repository", etc., to determine if the code was accessible. If the code was available, I reviewed it, assessing it based on the FAIR principles—Findable, Accessible, Interoperable, and Reusable.

## Findings:
In the area of Generative and Synthetic Genomics, publications in this area were relatively sparse, with few review articles available.Most of the papers did not provide accessible code. Among those with code, most offered uncommented and non-user-friendly code. Often, only the trained models were shared, not the code necessary to test them. Consequently, it was challenging to identify models that met the FAIR principles.
Human Genetics: I found it easier to locate a review on AI applications in genomic data. This field presented a more substantial number of models that adhered to the FAIR principles.

## Models:
### Human Genomics:
#### Model N°1: Clair3
- [Code](https://github.com/HKU-BAL/Clair3)
- [Article](https://www.nature.com/articles/s43588-022-00387-x.epdf?sharing_token=kNdf0czJGhElEb0EB6oagdRgN0jAjWel9jnR3ZoTv0PiJdK5GreqltZHoXbqG5RzgmGodWvUVeLCJN4bGjchqsDftg2GnKA_d8pBr_SKRpJ13BBz1pMuALldqSi4zNg48pyWtmSs4ORgZmNJ1VeOjrVcoTG0y_eyXoRHpc8498U%3D)

Clair3 is a germline small variant caller for long-reads. Clair3 makes the best of two major method categories: pileup calling handles most variant candidates with speed, and full-alignment tackles complicated candidates to maximize precision and recall. Clair3 runs fast and has superior performance, especially at lower coverage. Clair3 is simple and modular for easy deployment and integration.

#### Model N°2: DeepVariant
- [Code](https://github.com/google/deepvariant)
- [Article](https://www.nature.com/articles/nbt.4235.epdf?author_access_token=q4ZmzqvvcGBqTuKyKgYrQ9RgN0jAjWel9jnR3ZoTv0NuM3saQzpZk8yexjfPUhdFj4zyaA4Yvq0LWBoCYQ4B9vqPuv8e2HHy4vShDgEs8YxI_hLs9ov6Y1f_4fyS7kGZ)

DeepVariant is a deep learning-based variant caller that takes aligned reads (in BAM or CRAM format), produces pileup image tensors from them, classifies each tensor using a convolutional neural network, and finally reports the results in a standard VCF or gVCF file.

#### Model N°3: DeepConsensus
- [Code](https://github.com/google/deepconsensus)
- [Article](https://www.nature.com/articles/s41587-022-01435-7)

DeepConsensus uses gap-aware sequence transformers to correct errors in Pacific Biosciences (PacBio) Circular Consensus Sequencing (CCS) data.

#### Model N°4: DeepSplice
- [Code](https://github.com/Didar-Hussain/AS-Prediction-Using-DL/tree/main)
- [Article](https://www.frontiersin.org/journals/genetics/articles/10.3389/fgene.2024.1349546/full)

a deep learning approach for accurate prediction of alternative splicing events in the human genome

---
### Syntetic Biology;
#### Model N°1: Gretelai
- [Code](https://github.com/gretelai/synthetic-data-genomics/tree/main)
- [Article](https://www.nature.com/articles/ng.3609)

The code in this repository uses Gretel.ai's synthetic data APIs to create synthetic (artificial) versions of real world mouse genotype and connected phenotype datasets. 

#### Model N°2: BioAutoMATED 
- [Code](https://github.com/jackievaleri/BioAutoMATED)
- [Article](https://www.cell.com/cell-systems/fulltext/S2405-4712(23)00151-5)

BioAutoMATED predicts gene regulation, peptide-drug interactions, and glycan annotation with performance comparable to that of manually tuned models, revealing salient sequence characteristics. By automating sequence modeling, BioAutoMATED allows life scientists to more readily incorporate ML into their work.

#### Model N°3: CyanoDeeplearning
- [Code](https://github.com/EuijinSeo/CyanoDeeplearning/tree/main)
- [Article](https://academic.oup.com/nar/article/51/13/7071/7184158)

In this study, 'Design of synthetic promoters for cyanobacteria with generative deep-learning model', provides a deep-learning based generic framework to generate synthetic promoter sequences for cyanobacteria and predict their strength using a variational autoencoder (VAE) and convolutional neural network (CNN), respectively.

