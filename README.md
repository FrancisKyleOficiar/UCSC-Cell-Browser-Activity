# UCSC-Cell-Browser-Activity
**Name:** Francis Kyle A. Oficiar
**Assigned Gene:** APP
**Associated Disease:** Early On-set Alzheimer's Disease
**Date:** September 27, 2026

# PART B. Open the UCSC Cell Browser and Choose a Dataset

| **Item**                 | **Information**                                                                                                                                                                                                 |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Dataset**              | AD and Aging Prefrontal Cortex Across 427 individuals                                                                                                                                      |
| **Organ/Tissue**         | Brain (multiple regions)                                                                                                                                                                                         |
| **Cell Types**           | Excitatory neuron subtypes (e.g., Exc L2-3 CBLN2, Exc L4-5 RORB), inhibitory neuron subtypes (e.g., Inh SST, Inh PVALB), astrocytes (Ast DCLK1, Ast GRM3), oligodendrocytes (Oli OPALIN), microglia (Mic), endothelial and vascular cells (End, SMC, Per) |
| **Gene**                 | APP                                                                                                                                                                                                             |
| **Reason for Selection** | Alzheimer’s disease affects multiple brain regions, and this dataset provides high-resolution cell-type and subtype information where APP is expressed and processed into amyloid-β, contributing to neurodegeneration. |
| **Dataset URL**          | https://cells.ucsc.edu/?ds=rosmap                                                                                                                                                                                |

<img width="1020" height="479" alt="image" src="https://github.com/user-attachments/assets/e7bace6f-e5a1-4d3b-ae80-4cfe53ffb237" />
**Figure 1.**

# PART C. Understand the Cell Map

**a. Type of visualization:**
UMAP (Uniform Manifold Approximation and Projection)

**b. What does one dot represent?**
One dot represents a single cell (or nucleus) from the brain tissue that was analyzed in the dataset.

**c. What do the clusters represent in this dataset?**
The clusters represent different brain cell types and subtypes in the Alzheimer’s disease dataset, grouped based on similar gene expression profiles (e.g., neurons, glial cells, and vascular-related cells with distinct molecular signatures).

**d. Example cluster/cell-type labels (at least 3):**
Exc (excitatory neurons), Inh (inhibitory neurons), Ast (astrocytes), Oli (oligodendrocytes), Mic (microglia)

# PART D. Search for Your Assigned Gene

| **Item**                                                                   | **Answer**                                                                                                                                                                                                      |
| -------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Assigned gene symbol**                                                   | **APP**                                                                                                                                                                                                         |
| **Dataset used**                                                           | **AD and Aging Prefrontal Cortex Across 427 individuals**                                                                                                                                                       |
| **Is expression widespread, restricted, or low/undetected?**               | **Widespread.** APP expression is detectable across many different cell clusters, including several excitatory and inhibitory neuronal populations as well as some glial and other cell types.                  |
| **Which cluster(s) appear to contain cells with stronger expression?**     | Stronger visible APP expression appears particularly around several **excitatory neuron clusters**, including **Exc L3-5 RORB** and **Exc L2-3 CBLN2**, based on the darker regions of the gene-expression map. |
| **Which cluster(s) appear to contain little or no detectable expression?** | Relatively lower or less detectable expression appears in some **vascular-associated clusters**, such as **aSMC** and **capEndo1-6**, compared with the darker neuronal regions.                                |
| **Overall observation**                                                    | APP is not restricted to a single cell type in this dataset. The map shows detectable expression across multiple cell populations, with visibly stronger expression in several neuronal clusters.               |

<img width="1020" height="480" alt="image" src="https://github.com/user-attachments/assets/9ceb6e38-a2c5-4195-a4db-33479dc784bf" />
**Figure 2.**

# PART E. Identify the Cell Types Expressing Your Gene

| **Item**                                                           | **Answer**                                                                                                                                                                                                                                                                                                                                                                                                    |
| ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Cell type/cluster with the strongest visible expression**        | **Exc L3-5 RORB** — this region appears among the darker areas of the APP expression map, indicating relatively stronger visible expression.                                                                                                                                                                                                                                                                  |
| **Another cell type/cluster with detectable expression**           | **Exc L2-3 CBLN2** — this excitatory neuron cluster also shows clearly detectable APP expression.                                                                                                                                                                                                                                                                                                             |
| **Cell type/cluster with relatively low or undetected expression** | **aSMC (smooth muscle cells)** — APP expression appears relatively low compared with the stronger neuronal clusters.                                                                                                                                                                                                                                                                                          |
| **Is the expression pattern broad or cell-type restricted?**       | **Broad.** APP is detectable across multiple neuronal and non-neuronal cell populations, although the visible expression level varies among clusters.                                                                                                                                                                                                                                                         |
| **Possible biological explanation**                                | **Based on this selected dataset, APP appears to be expressed across multiple cell types, with stronger expression in several neuronal populations. This may reflect the important role of APP in brain cells and neuronal biology, while differences between clusters may reflect cell-type-specific expression levels or differences in the cellular state of the individuals represented in the dataset.** |

<img width="1020" height="480" alt="image" src="https://github.com/user-attachments/assets/0aa3a06d-1d16-4b79-9d04-ac403e07cf55" />
**Figure 3.**

# PART F. Select Cells and Examine a Violin Plot

| **Question**                          | **Answer**                                                                                                                                                               |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Which cells/cluster did you select?   | **Exc L3-4 RORB CUX2**                                                                                                                                                   |
| Higher, lower, or similar expression? | **Higher APP expression** compared with low-expression groups such as **Ast GRM3** and **Mic P2RY12**.                                                                   |
| What does the plot add?               | It shows **average expression and the proportion of cells with detectable expression**, providing more quantitative information than the UMAP/t-SNE color pattern alone. |

<img width="809" height="774" alt="image" src="https://github.com/user-attachments/assets/38153da4-22ff-433f-81d1-fdde738b3cf3" />
**Figure 4.**

# PART G. Explore Marker Genes

| **Item**                                                        | **Answer**                                                                                                                                                                                                                                                                                                            |
| --------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **a. Cluster/cell type examined**                               | **Oligodendrocyte**                                                                                                                                                                                                                                                                                                   |
| **b. Marker gene 1**                                            | **MOG**                                                                                                                                                                                                                                                                                                               |
| **c. Marker gene 2**                                            | **MBP**                                                                                                                                                                                                                                                                                                               |
| **d. Marker gene 3**                                            | **PLP1**                                                                                                                                                                                                                                                                                                              |
| **e. Does APP behave like a cell-type marker in this dataset?** | **No. APP does not appear to behave like a cell-type-specific marker in this dataset.** APP expression is visible across multiple cell types, particularly several neuronal populations, whereas the marker genes shown for oligodendrocytes are associated more specifically with identifying oligodendrocyte cells. |

<img width="1020" height="484" alt="image" src="https://github.com/user-attachments/assets/473996b5-6559-4e20-a1b7-631d6362f503" />
**Figure 5.**

# PART H. Compare Your Assigned Gene With One Marker Gene

| **Item**                                                                | **Answer**                                                                                                                                                                                                                           |
| ----------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **a. Assigned disease gene**                                            | **APP**                                                                                                                                                                                                                              |
| **b. Marker gene**                                                      | **MOG**                                                                                                                                                                                                                              |
| **c. Which gene shows a more cell-type-restricted expression pattern?** | **MOG** shows the more cell-type-restricted pattern because it is associated with **oligodendrocytes**, whereas APP is detectable across multiple cell populations.                                                                  |
| **d. Which gene appears more broadly expressed?**                       | **APP** appears more broadly expressed across the cell types in this dataset.                                                                                                                                                        |
| **e. What does this comparison teach you?**                             | This comparison shows that a **disease-associated gene does not necessarily function as a cell-type marker**. APP can be expressed across several cell types, while MOG has a more characteristic association with oligodendrocytes. |

# PART I. Connect the Cell Browser Result to Your Previous Genome Activity

| **Item**                                                                            | **Answer**                                                                                                                                                                                                                                                                                                                                                                                                     |
| ----------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1. Chromosome location of assigned gene**                                         | **Chromosome 21 (21q21.3)**                                                                                                                                                                                                                                                                                                                                                                                    |
| **2. Disease-associated variant examined previously**                               | **NM_000484.4(APP):c.2077G>A (p.Glu693Lys)**                                                                                                                                                                                                                                                                                                                                                                   |
| **3. Cell type(s) expressing the gene**                                             | APP is detectable across multiple cell types, with stronger visible expression in several excitatory neuron clusters, including **Exc L3-5 RORB** and **Exc L2-3 CBLN2**.                                                                                                                                                                                                                                      |
| **4. Does the observed expression make biological sense?**                          | **Yes.** APP expression in several neuronal populations is consistent with its biological relevance in the brain and its association with neurodegenerative disease. The different expression levels among cell types suggest that APP may have roles across multiple brain cell populations rather than being restricted to one cell type. This interpretation is based on the selected Cell Browser dataset. |
| **5. Can this single Cell Browser dataset prove that the gene causes the disease?** | **No.** The dataset shows gene-expression patterns across cell types, but expression alone cannot establish that APP causes disease. Additional genetic, experimental, and clinical evidence is needed to establish causation.                                                                                                                                                                                 |

# PART J. SHORT REFLECTION
| **Question**                                                                                                                | **Answer**                                                                                                                                                                                                                                                                                               |
| --------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1. What did the UCSC Cell Browser show you that the UCSC Genome Browser could not?**                                      | The UCSC Cell Browser showed **where APP is expressed among different cell types and clusters**. In contrast, the Genome Browser focuses more on genomic location, gene structure, and genetic variants rather than directly showing cell-specific expression patterns.                                  |
| **2. Why can the same gene have different expression levels among different cell types?**                                   | Different cell types have different functions and therefore regulate genes differently. Regulatory mechanisms such as transcription factors and cellular signals can cause a gene to be highly expressed in one cell type but expressed at lower levels in another.                                      |
| **3. Why should you be careful when interpreting a gene that shows zero or very low expression in single-cell data?**       | A zero or very low value does not necessarily mean that the gene is completely absent or biologically inactive. Single-cell experiments can have technical limitations, such as dropout or failure to detect a transcript, so these results should be interpreted carefully.                             |
| **4. Why is it useful to combine information about genomic location, genetic variants, and cell-specific gene expression?** | Combining these types of information provides a more complete picture of how a gene may be related to disease. Genomic location identifies where the gene is found, genetic variants can indicate disease-associated changes, and cell-specific expression shows which cells or tissues may be involved. |
| **5. What was the most interesting observation you made about your assigned gene?**                                         | The most interesting observation was that                                                                                                                                                                                                                                                                |




