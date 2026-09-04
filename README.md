
# Prof. Michaël Aupetit
<img width="125" height="150" alt="photoid_professional_500x600" src="https://github.com/user-attachments/assets/05d166b5-dcdd-4dbe-aded-59e521ef7770" />


*Full Professor* at [EPITA](https://www.epita.fr/en/){:target="_blank"}


Formerly *Senior Scientist* at [Qatar Center for Artificial Intelligence](https://qcai.qcri.org/){:target="_blank"}

 [LRE](https://www.lre.epita.fr/){:target="_blank"} -
 [LinkedIn](https://www.linkedin.com/in/micha%C3%ABl-aupetit-1a70592){:target="_blank"}
 
## Publications
 [DBLP](https://dblp.org/pid/48/3879.html){:target="_blank"} -
 [Google Scholar](https://scholar.google.com/citations?user=UszzuaAAAAAJ){:target="_blank"} -
 [ORCID](https://orcid.org/0000-0001-6321-5242){:target="_blank"} -
 [ResearchGate](https://www.researchgate.net/profile/Michael_Aupetit){:target="_blank"}

---

- **IEEE ICDE 2026**
    > M. S. Ahmad, Z. A. Naeem, M. Aupetit, A. Elmagarmid, M. Eltabakh, X. Ma, M. Ouzzani, C. Ruan, H. Al-Sayeh 
      <br> **HCT-QA: A Benchmark for Question Answering on Human-Centric Tables** <br>
      [arXiv](https://arxiv.org/html/2504.20047v3){:target="_blank"} -
      [HF](https://huggingface.co/datasets/qcri-ai/HCTQA){:target="_blank"} -
      [GitHub](https://github.com/qcri/HCTQA-Benchmark){:target="_blank"}

<details>
<summary><img src="https://github.com/user-attachments/assets/e9db3625-5d5e-49c6-b058-c974e0433942" style="width:auto; height:50px" alt="HCTQA data collection">
<img src="https://github.com/user-attachments/assets/c7deb881-d540-48e2-871f-742ec9dcb3b4" style="width:auto; height:50px" alt="HCTQA data collection">
<img src="https://github.com/user-attachments/assets/9c500cb6-a68c-4fe7-9e0c-e2cffef3eff3" style="width:auto; height:50px" alt="HCTQA data collection"></summary>

Human-centric tables (HCTs) are everywhere in official industrial, governmental, or institutional reports, but their complex layout makes it difficult to answer natural questions about them, even by recent LLMs
<img src="https://github.com/user-attachments/assets/e9db3625-5d5e-49c6-b058-c974e0433942" width="100%" alt="HCT complex layouts">

HCT-QA is a benchmark of HCTs and related question-answer pairs carefully collected from real sources, manually verified, and enriched with metadata for deep analysis
<img src="https://github.com/user-attachments/assets/c7deb881-d540-48e2-871f-742ec9dcb3b4" width="100%" alt="HCT-QA data collection and validation">

HCT-QA benchmark is enriched with thousands of synthetic HCTs, QA, and metadata with a generator, thanks to the correspondence between SQL and template-based questions, and pivoted relational tables and HCT to get valid answers at scale.
<img src="https://github.com/user-attachments/assets/9c500cb6-a68c-4fe7-9e0c-e2cffef3eff3" width="100%" alt="HCT-QA synthetic data generator">
</details>

---

- **IEEE TVCG 2026**
    > R. Cutura, S. Sadler, Q. Quang Ngo, M. Aupetit, and M. Sedlmair 
      <br> **ISilDR: Isometric-Seriation-Based Dimensionality Reduction for Visual Cluster Analysis** <br>
      [PacificVis IEEE TVCG track](https://doi.ieeecomputersociety.org/10.1109/TVCG.2026.3694456){:target="_blank"} -
      [Slides](https://github.com/user-attachments/files/27026598/IsilDR.PacificVis.Presentation_unfold.pdf){:target="_blank"}

<details>
<summary><img src="https://github.com/user-attachments/assets/8a0a795c-a55e-43af-89da-44d8da0420f1" style="width:auto; height:50px" alt="ISilDR principle">
<img src="https://github.com/user-attachments/assets/41ed5f00-c5af-441c-992a-3aee6cd0b898" style="width:auto; height:50px" alt="ISilDR -> OLP Inference">
<img src="https://github.com/user-attachments/assets/9cbf7328-14e9-45ad-ac41-7b8608f5b2dc" style="width:auto; height:50px" alt="OLP -> ISilDR Inference"></summary>

ISilDR is a new family of dimensionality reduction (DR) techniques that never produce false neighbors, by contrast to Orthogonal Linear Projections like Principal Component Analysis, which never produce Missing neighbors. This is the first time that such a family of DR techniques has been identified. All other DR techniques always produce some False Neighbors... And so what?
<img src="https://github.com/user-attachments/assets/8a0a795c-a55e-43af-89da-44d8da0420f1" width="100%" alt="ISilDR principle">

When a group of data is identified in an ISilDR and in an OLP, we can infer that this group exists in the original multidimensional (MD) data space.  
<img src="https://github.com/user-attachments/assets/41ed5f00-c5af-441c-992a-3aee6cd0b898" width="100%" alt="ISilDR -> OLP Inference">

When a group of data is identified in an OLP, then in an ISilDR, we can infer that this group exists in the original MD data space.
<img src="https://github.com/user-attachments/assets/9cbf7328-14e9-45ad-ac41-7b8608f5b2dc" width="100%" alt="OLP -> ISilDR Inference">

This is the first time such a strong conclusion about an MD data pattern has been derived from combining two independent DR layouts.  In contrast, observing the same group across any combination of two or more OLP layouts, two or more ISilDR layouts, or two or more tSNE or UMAP layouts, for instance,  does not guarantee that this group exists in the MD data space. In general, in DR, two wrongs don't make a right! But here, OLP + ISilDR can tell us some truth about the MD data.
</details>

---

 - **IEEE TVCG 2026** 
    > H. Jeon, M. Aupetit, S. Lee, K. Ko, Y. Kim, G. J. Quadri, and J. Seo
      <br> **Distortion-Aware Brushing for Reliable Cluster Analysis in Multidimensional Projections** <br>
      [IEEE TVCG](https://doi.org/10.1109/TVCG.2025.3615314){:target="_blank"} -
      [Demo](https://distortion-aware-brushing.github.io/site/){:target="_blank"}

<details>
<summary><img src="https://github.com/user-attachments/assets/31daec41-38c7-4dd4-84c3-9ee134d1e7b7" style="width:auto; height:50px" alt="Interactive Lasso Techniques vs Distortion Aware Brushing">
<img src="https://github.com/user-attachments/assets/f1b5525c-c71f-44c6-a2b9-c7836533d487" style="width:auto; height:50px" alt="Distortion Aware Brushing in action"></summary>

Lasso techniques for selecting data from dimensionality-reduced (DR) layouts are prone to DR-induced distortions: the lasso can capture false neighbors and miss true neighbors. We propose Distortion-Aware Brushing, a technique that permanently rearranges the data in the DR layout to minimize local distortions. The clusters you build in the layout match the clusters in the multidimensional data space.
<img src="https://github.com/user-attachments/assets/31daec41-38c7-4dd4-84c3-9ee134d1e7b7" width="100%" alt="Interactive Lasso Techniques vs Distortion Aware Brushing">

Distortion Aware Brushing in action
<img src="https://github.com/user-attachments/assets/f1b5525c-c71f-44c6-a2b9-c7836533d487" width="100%" alt="Distortion Aware Brushing in action">
</details>

---

- **IEEE TPAMI 2025**
    > H. Jeon, M. Aupetit, D. Shin, A. Cho, S. Park, J. Seo 
     <br> **Measuring the Validity of Clustering Validation Datasets** <br>
     [IEEE TPAMI](https://doi.org/10.1109/TPAMI.2025.3548011){:target="_blank"} -
     [Ranked Datasets](https://hyeonword.com/clm-datasets/){:target="_blank"} -
     [(Python) Dataset reader](https://github.com/hj-n/labeled-datasets){:target="_blank"} -
     [(Python) Adjusted Internal Validation Measures](https://github.com/hj-n/clm){:target="_blank"}

<details>
<summary><img src="https://github.com/user-attachments/assets/1df04369-5537-4838-9981-4e23186ac10b" style="width:auto; height:50px" alt="Class Label Matching and External Validation Measures">
<img src="https://github.com/user-attachments/assets/fc46dfea-a6ff-4ca8-acff-ced23e41aaa8" style="width:auto; height:50px" alt="Consider only the CLM-best data has an effect on ranking stability">
<img src="https://github.com/user-attachments/assets/919aae33-4d45-4490-b456-4f3e2229b878" style="width:auto; height:50px" alt="Speed and correlation with ground truth"></summary>

Cluster Label Matching (CLM) is the assumption that class labels in datasets used for benchmarking clustering techniques match their cluster structure. This assumption is essential for evaluating the quality of clustering techniques using External Validation Measures (EVMs) such as the Normalized Mutual Information or the Adjusted Rand Index. EVMs compare the classes obtained by a clustering technique to the class labels of the data (in multidimensional space). The issue is that no one checked whether the CLM assumption was valid, which calls into question comparisons of clustering techniques on such benchmark datasets. We propose a way to quantify the CLM of multidimensional datasets by defining across-dataset axioms and deriving internal validation measures (IVMs) like Silhouette or Davies-Bouldin, that enable comparison of datasets with different numbers of data points, dimensionality, and classes.
<img src="https://github.com/user-attachments/assets/1df04369-5537-4838-9981-4e23186ac10b" width="100%" alt="Class Label Matching and External Validation Measures">

Considering only the dataset with the best CLM to compare clustering techniques has a strong positive effect on ranking stability. Whichever subset of these good-CLM datasets is used for benchmarking clusterings yields a similar ranking of the compared techniques. By contrast, using all datasets, ignoring their CLM, or picking only the bad-CLM ones leads to far more unstable rankings, underscoring the importance of measuring CLM and selecting only the best-CLM datasets.
<img src="https://github.com/user-attachments/assets/fc46dfea-a6ff-4ca8-acff-ced23e41aaa8" width="100%" alt="Consider only the CLM-best data has an effect on ranking stability">

The proposed adjusted IVMs are both computationally efficient and more highly correlated with the generally intractable ground truth than the standard IVMs.
<img src="https://github.com/user-attachments/assets/919aae33-4d45-4490-b456-4f3e2229b878" width="100%" alt="Speed and correlation with ground truth">
</details>

---

- **...**

  

## Projects

TBA soon
