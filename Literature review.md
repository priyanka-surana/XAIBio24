1. ## **Introduction**

   Cancer biology is the study of cellular, genetic and molecular attributes that revolves around cancers. The field encompasses many stages of the disease, including initiation, progression and development and treatment. As cancers develop from the uncontrollable growth of cells in the human’s bodies, they are unique to each individual and hence referred to as “cancer heterogeneity”. Due to its complexity, and its variation from person to person, cancers are difficult to treat and can spread to other organs (metastasis). Henceforth, it is one of the most pioneered and focused fields of study in the current time.  
     
   The study of cancer biology is booming with data, from genomics, transcriptomics and epigenetics \[1\], many of which have been utilized to draw more information in conjunction with each other \[2\]. The amount of data sparks potential for applying technology that can make use of them, allowing us to understand in depth the complexity of tumor heterogeneity \[3\]. Consequently, artificial intelligence (AI) models are being employed across a broad spectrum of applications in cancer biology, ranging from clinical diagnostics and predictive aids to cancer drug development pipelines. AI algorithms can analyze vast datasets quickly and accurately, identifying patterns and correlations that might be missed by traditional methods. Machine learning techniques, in particular, are being used to predict patient outcomes, personalize treatment plans, and even identify new therapeutic targets. The integration of AI in cancer research is revolutionizing our approach to understanding and treating this disease, offering the potential for more precise and effective interventions. Utilizing such data promises a deeper understanding of cancers and more effective treatment strategies.  
     
   However, skepticism remains as there are huge concerns towards using AI in treating cancer. As the data and the amount of data increases, the complication in the models’ architecture also makes it difficult to digest the models’ decisions. With the extremely large amount of usage in cancer biology, it has been recognized that being able to distinguish the reasons behind the models’ works would be extremely beneficial to support the models’ application in clinical scenarios.

   

2. ## **Related work**

a. **AI in drug discovery**  
   In drug discovery, AI has been instrumental in evaluating the synergistic attributes of drug combinations. It is well-documented that drug combinations often yield more effective responses compared to monotherapy in cancer treatment. Given the adaptive nature of cancer cells, which can develop resistance to single drugs, using multiple drugs concurrently can mitigate the likelihood of resistance. AI models enhance this process by analyzing drug interactions and predicting the most effective combinations, thereby optimizing treatment protocols and improving therapeutic outcomes.   
     
   Recent innovations include a machine learning model from the DREAM AstraZeneca-Sanger Drug Combination Prediction Challenge. This model, using biologically relevant drug and cell line features, ranked in the top 15 out of 76 submissions, achieving a primary metric score of 0.36 and providing insights into key tumorigenesis regulators involved in synergistic interactions. Additionally, the deep-learning multitask model MARSY predicts drug-pair synergy scores by incorporating gene expression profiles and drug-induced differential expression signatures. MARSY outperformed traditional models, predicting 133,722 new drug-pair cell line combinations with validated accuracy. Furthermore, ensembles of explainable machine-learning models have improved feature attribution quality in high-dimensional transcriptomic datasets. This approach identified a haematopoietic-differentiation signature linked to therapeutic synergy in drug combinations tested on ex vivo tumor samples from acute myeloid leukemia patients. These advancements in AI models enhance the understanding and prediction of effective drug synergies, aiding in more informed cancer treatment strategies.  
 


b. **AI in drug repurposing**  
   Drug repurposing is an emerging field driven by the need to find new uses for existing drugs, which is more cost-effective and faster than developing new drugs. AI significantly contributes to this area by identifying new therapeutic uses for established drugs through the analysis of vast datasets of drug interactions, side effects, and genetic information. This approach not only conserves resources but also leverages the existing safety profiles of known drugs.  
     
   One innovative method is BiFusion, a bipartite graph convolution network model that integrates heterogeneous information for drug repurposing. By constructing a multi-relational graph of drug-protein, disease-protein, and protein-protein interactions (PPIs), BiFusion uses protein nodes as bridges for message passing, enhancing the assessment of drug-disease associations. Extensive experiments demonstrated that BiFusion outperformed multiple baselines in drug repurposing analysis. Another approach, GraphRepur, is a graph neural network model based on GraphSAGE designed for breast cancer drug repurposing. GraphRepur integrates drug network-based and drug signature-based methods, utilizing differentially expressed genes, drug-exposure gene expression data, and drug-drug links information. By extracting drug signatures and topological structure information, GraphRepur predicts new drugs for breast cancer, outperforming previous state-of-the-art methods. Many of the high-ranked drugs identified by GraphRepur have been recently reported as potential treatments for breast cancer.  
 


c. **AI in drug response**  
   AI is revolutionizing our understanding of drug response in cancer treatment by integrating patient data, genetic profiles, and treatment histories. This personalized approach allows for more precise and effective therapies, minimizing adverse effects and improving outcomes. AI models can identify biomarkers that predict a patient's response to a drug, enabling clinicians to tailor treatments to each individual’s unique profile.  
     
   One notable development is DeepTTA, a deep learning model that uses transcriptome gene expression data and chemical substructures of drugs to predict cancer drug responses. DeepTTA achieved higher performance compared to existing methods and identified potential therapeutic options for drugs like bortezomib and dactinomycin. Another example is a deep learning model for predicting the response to palbociclib, a CDK4/6 inhibitor used in breast cancer therapy. The model, which is based on a reference map of multiprotein assemblies in cancer, successfully stratified palbociclib-sensitive and \-resistant cell lines by integrating genetic alterations across 90 genes. This approach was validated in patient-derived xenografts and provided insights into mechanisms of drug resistance. DeepCDR is another advanced model that integrates multi-omics profiles of cancer cells with the intrinsic chemical structures of drugs to predict cancer drug responses. This hybrid graph convolutional network automatically learns topological structures among atoms and bonds in drugs, outperforming state-of-the-art methods. DeepCDR's predictive power highlights its potential in guiding disease-specific drug design. Lastly, DrugCell is an interpretable deep learning model trained on responses from 1,235 tumor cell lines to 684 drugs. It integrates tumor genotypes and drug structures to predict therapy responses and uncover biological mechanisms underlying drug responses. DrugCell's predictions were accurate and led to the design of synergistic drug combinations validated through various methods.  
   

   ## 

   3. ## References**

   Celebi, R., Bear Don’t Walk, O., Movva, R. et al. In-silico Prediction of Synergistic Anti-Cancer Drug Combinations Using Multi-omics Data. Sci Rep 9, 8949 (2019). [https://doi.org/10.1038/s41598-019-45236-6](https://doi.org/10.1038/s41598-019-45236-6)  
     
   Mohamed Reda El Khili, Safyan Aman Memon, Amin Emad, MARSY: a multitask deep-learning framework for prediction of drug combination synergy scores, Bioinformatics, Volume 39, Issue 4, April 2023, btad177, [https://doi.org/10.1093/bioinformatics/btad177](https://doi.org/10.1093/bioinformatics/btad177)  
     
   Janizek, J.D., Dincer, A.B., Celik, S. et al. Uncovering expression signatures of synergistic drug responses via ensembles of explainable machine-learning models. Nat. Biomed. Eng 7, 811–829 (2023). [https://doi.org/10.1038/s41551-023-01034-0](https://doi.org/10.1038/s41551-023-01034-0)  
     
   Jannis Born, Matteo Manica, Ali Oskooei, Joris Cadow, Greta Markert, María Rodríguez Martínez, PaccMannRL: De novo generation of hit-like anticancer molecules from transcriptomic data via reinforcement learning,  
   iScience, [https://doi.org/10.1016/j.isci.2021.102269](https://doi.org/10.1016/j.isci.2021.102269).  
     
   Zichen Wang, Mu Zhou, Corey Arnold, Toward heterogeneous information fusion: bipartite graph convolutional networks for in silico drug repurposing, Bioinformatics, Volume 36, Issue Supplement\_1, July 2020, Pages i525–i533, [https://doi.org/10.1093/bioinformatics/btaa437](https://doi.org/10.1093/bioinformatics/btaa437)  
     
   Chen Cui, Xiaoyu Ding, Dingyan Wang, Lifan Chen, Fu Xiao, Tingyang Xu, Mingyue Zheng, Xiaomin Luo, Hualiang Jiang, Kaixian Chen, Drug repurposing against breast cancer by integrating drug-exposure expression profiles and drug–drug links based on graph neural network, Bioinformatics, Volume 37, Issue 18, September 2021, Pages 2930–2937, [https://doi.org/10.1093/bioinformatics/btab191](https://doi.org/10.1093/bioinformatics/btab191)  
     
   Likun Jiang, Changzhi Jiang, Xinyu Yu, Rao Fu, Shuting Jin, Xiangrong Liu, DeepTTA: a transformer-based model for predicting cancer drug response, Briefings in Bioinformatics, Volume 23, Issue 3, May 2022, bbac100, [https://doi.org/10.1093/bib/bbac100](https://doi.org/10.1093/bib/bbac100)  
     
   Park, S., Silva, E., Singhal, A. et al. A deep learning model of tumor cell architecture elucidates response and resistance to CDK4/6 inhibitors. Nat Cancer 5, 996–1009 (2024). [https://doi.org/10.1038/s43018-024-00740-1](https://doi.org/10.1038/s43018-024-00740-1)  
   Qiao Liu, Zhiqiang Hu, Rui Jiang, Mu Zhou, DeepCDR: a hybrid graph convolutional network for predicting cancer drug response, Bioinformatics, Volume 36, Issue Supplement\_2, December 2020, Pages i911–i918, [https://doi.org/10.1093/bioinformatics/btaa822](https://doi.org/10.1093/bioinformatics/btaa822)

   Kuenzi, Brent M. et al. Predicting Drug Response and Synergy Using a Deep Learning Model of Human Cancer Cells, [https://doi.org/10.1016/j.ccell.2020.09.014](https://doi.org/10.1016/j.ccell.2020.09.014)

   

   

   