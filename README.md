# Pain Single Cell

Collections of Papers and Notes on Single Cell Studies in Pain Research

## Spinal Cord scRNA-seq Studies

- Delile, J., Rayon, T., Melchionda, M., Edwards, A., Briscoe, J., and Sagner, A. (2019). Single cell transcriptomics reveals spatial and temporal dynamics of gene expression in the developing mouse spinal cord. Development 146, dev173807. [#Delile:2019go]
- Häring, M., Zeisel, A., Hochgerner, H., Rinwa, P., Jakobsson, J.E.T., Lönnerberg, P., Manno, G., Sharma, N., Borgius, L., Kiehn, O., et al. (2018). Neuronal atlas of the dorsal horn defines its architecture and links sensory input to transcriptional cell types. Nat Neurosci 61, 1.[#Haring:2018dx]
  - **Method**: Fluidigm C1 Single **Cell** (not nuclei) RNA-seq from adult mouse spinal cord. Enriched dorsal horn neurons using Vglut2-EYFP and Vgat-EYFP
  - **Findings**:
    - Defined **30 neuronal types**
    - 15 GABA/15 GLUT (w/ one dual)
    - Verified mRNA expression using multiplexed RNAscope
    - Identified neuronal types responsive to heat and cold using _Arc_ expression by RNAscope
- Rosenberg, A.B., Roco, C.M., Muscat, R.A., Kuchina, A., Sample, P., Yao, Z., Gray, L., Peeler, D.J., Mukherjee, S., Chen, W., et al. (2018). Single-cell profiling of the developing mouse brain and spinal cord with split-pool barcoding. Science 12, eaam8999.[#Rosenberg:2018it]
  - **Method**: SPLIT-seq (method development paper)
  - **Findings**:
    - Identiified multiple known and unknown spinal cell types
    - Massive number of cells. 
    - Mixed the entire spinal cord, not just a single level. 
   
- Sathyamurthy, A., Johnson, K.R., Matson, K.J.E., Dobrott, C.I., Li, L., Ryba, A.R., Bergman, T.B., Kelly, M.C., Kelley, M.W., and Levine, A.J. (2018). Massively Parallel Single Nucleus Transcriptional Profiling Defines Spinal Cord Neurons and Their Activity during Behavior. Cell Reports 22, 2216–2225.[#Sathyamurthy:2018cz]
  - First study to define cell types in the mouse spinal cord using snRNA-seq (Drop-seq)
  - Formalin-inject + Fos (IEG) expression using snRNA-seq to identify stimulus-responsive cell types
- Zeisel, A., Hochgerner, H., Lönnerberg, P., Johnsson, A., Memic, F., van der Zwan, J., Häring, M., Braun, E., Borm, L.E., La Manno, G., et al. (2018). Molecular Architecture of the Mouse Nervous System. Cell 174, 999–1014.e22. [#Zeisel:2018iu]

## Dorsal Root Ganglia Single Cell RNA-seq Studies

### Naive
- Hockley, J.R.F., Taylor, T.S., Callejo, G., Wilbrey, A.L., Gutteridge, A., Bach, K., Winchester, W.J., Bulmer, D.C., McMurray, G., and Smith, E.S.J. (2018). Single-cell RNAseq reveals seven classes of colonic sensory neuron. Gut gutjnl–2017–315631.
  - Smart-seq2 based scRNA-seq
  - Retrograde labeling to capture colon-terminating DRGs (first study to do this)
- Zeisel, A., Hochgerner, H., Lönnerberg, P., Johnsson, A., Memic, F., van der Zwan, J., Häring, M., Braun, E., Borm, L.E., La Manno, G., et al. (2018). Molecular Architecture of the Mouse Nervous System. Cell 174, 999–1014.e22. [#Zeisel:2018iu]
- Li, C.-L., Li, K.-C., Wu, D., Chen, Y., Luo, H., Zhao, J.-R., Wang, S.-S., Sun, M.-M., Lu, Y.-J., Zhong, Y.-Q., et al. (2016). Somatosensory neuron types identified by high-coverage single-cell RNA-sequencing and functional heterogeneity. Cell Res 26, 83–102.[#Li:2016kq]
  - Manaul pickup of cells and SMARTer cDNA amplification
  - 10 clusters of DRG identified
  - Correlation with function: _in vivo_ DRG patch-clamp recording followed by single-cell PCR
- Usoskin, D., Furlan, A., Islam, S., Abdo, H., Lönnerberg, P., Lou, D., Hjerling-Leffler, J., Haeggström, J., Kharchenko, O., Kharchenko, P.V., et al. (2014). Unbiased classification of sensory neuron types by large-scale single-cell RNA sequencing. Nat Neurosci.[#Usoskin:2014hs]
  - Landmark scRNA-seq study on mouse DRG
  - Identified 11 types of distinct neurons
  - Manual pickup and processing with STRT-seq
  - Clustering with Bayesian methods
  
  
  
 ### Diseased/Treated
 
- Hu, G., Huang, K., Hu, Y., Du, G., Xue, Z., Zhu, X., and Fan, G. (2016). Single-cell RNA-seq reveals distinct injury responses in different types of DRG sensory neurons. Sci. Rep. 6, 31851.[#Hu:2016bya]
  - Spinal nerve transection (SNT) POD3 and POD7
  - Small cell number: 106 in total 
  - Identified differential neuronal responses to injury
  
## Spatial Transcriptomics of the Spinal Cord

### Diseased/Treated

- Maniatis, S., Äijö, T., Vickovic, S., Braine, C., Kang, K., Mollbrink, A., Fagegaltier, D., Andrusivová, Ž., Saarenpää, S., Saiz-Castro, G., et al. (2019). Spatiotemporal dynamics of molecular pathology in amyotrophic lateral sclerosis. Science 364, 89–93. [#Maniatis:2019dc]
  - **Method**: Spatial Transcriptomics
  - **Design**: Mouse ALS Model (SOD1) and Human ALS tissue with bulbar and lumbar onsets
  - **Findings**: Identified genes and gene modules differentially altered in ALS 
  - **Comments**: First study to apply a Spatial Tx platform to spinal cord, and especially human spinal cord. It was able to detect large differences in the disease state. 
