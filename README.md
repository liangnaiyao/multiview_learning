# Multi-view learning methods with code

## Part A: general multi-view methods with code 

### 1. NMF (non-negative matrix factorization) based methods
     NMF factorizes the non-negative data matrix into two non-negative matrices.

 * 1.1 AAAI17 Multi-View Clustering via Deep Matrix Factorization [(matlab)](https://github.com/hdzhao/DMF_MVC)
    - Deep Matrix Factorization is a variant of NMF.
    
 * 1.2 ICPR16 Partial Multi-View Clustering Using Graph Regularized NMF [(matlab)](https://github.com/nishantrai18/MultiViewNMF)
 
 * 1.3 ICDM16 Multi-View Clustering via Concept Factorization with Local Manifold Regularization [(matlab)](https://github.com/vast-wang/Clustering)
    - Concept Factorization is a variant of NMF.   
    
 * 1.4 TC19 Individuality- and Commonality-Based Multiview Multilabel Learning [(matlab)](http://mlda.swu.edu.cn/publication.php)
 
 * 1.5 AAAI14 Partial Multi-View Clustering [(matlab)](https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/publication_toc.htm#Multi-View%20Learning)
 
 * 1.6 TNNLS15 Partially Shared Latent Factor Learning With Multiview Data [(matlab)](https://sites.google.com/site/zcliustc/home/publication)
 
 * 1.7 S18 Multi-view Discriminative Learning via Joint Non-negative Matrix Factorization [(matlab)](https://www.dropbox.com/s/guohn1zhq073x9f/DICS.zip?dl=0)
 
 * 1.8 ICDM13 Multi-View Clustering via Joint Nonnegative Matrix Factorization [(matlab)](http://jialu.info/)
 
 * 1.9 KBS20 Multi-view clustering by non-negative matrix factorization with co-orthogonal constraints [(matlab)](https://github.com/liangnaiyao/NMFCC)
 
 * 1.10 KBS20 Semi-supervised Multi-view Clustering with Graph-regularized Partially Shared Non-negative Matrix Factorization [(matlab)](https://github.com/liangnaiyao/GPSNMF)
 
 * 1.11 NC18 Adaptive Structure Concept Factorization for Multiview Clustering [(matlab)](https://github.com/kunzhan/MVCF)
     - Concept Factorization is a variant of NMF.   
     
 * 1.12 ICDE20 A Novel Approach to Learning Consensus and Complementary Information for Multi-View Data Clustering [(matlab)](https://github.com/khanhluongds/Multi-view-Clustering-2CMV)
 
### 2. Graph based methods
     It contains two kinds of methods. The first kind is using a predefined graph, and performing post-processing spectral clustering or k-means. And the second kind is to learn the graph and the index matrix simultaneously. 
     
 * 2.1 ICDM19 Consistency Meets Inconsistency: A Unified Graph Learning Framework for Multi-view Clustering [(matlab)](https://github.com/youweiliang/ConsistentGraphLearning)
 
 * 2.2 TIP19 Multiview Consensus Graph Clustering [(matlab)](https://github.com/kunzhan/MCGC)

 * 2.3 TIP18 Auto-Weighted Multi-View Learning for Image Clustering and Semi-Supervised Classification [(matlab)](http://www.escience.cn/people/fpnie/papers.html)
 
 * 2.4 TKDE19 GMC Graph-based Multi-view Clustering [(matlab)](https://github.com/cshaowang/gmc)
 
 * 2.5 BD17 Multi-View Graph Learning with Adaptive Label Propagation [(matlab)](http://cobweb.cs.uga.edu/~shengli/?tdsourcetag=s_pcqq_aiomsg)

 * 2.6 TC18 Graph Learning for Multiview Clustering [(matlab)](https://github.com/kunzhan/MVGL)
 
 * 2.7 IJCAI16 Parameter-Free Auto-Weighted Multiple Graph Learning [(matlab)](http://www.escience.cn/people/fpnie/papers.html)
 
 * 2.8 TC18 Incomplete Multiview Spectral Clustering With Adaptive Graph Learning [(matlab)](http://www.yongxu.org/lunwen.html)
 
 * 2.9 TKDE19 Graph structure fusion for multiview clustering [(matlab)](https://github.com/dugzzuli/Graph-structure-fusion-for-multiview-clustering)
 
 * 2.10 ACML19 Latent Multi-view Semi-Supervised Classification [(matlab)](https://github.com/sckangz/LMVL)
 
 * 2.11 NN20 Partition level multiview subspace clustering [(matlab)](https://github.com/sckangz/PMSC)

 * 2.12 KBS20 Multi-graph Fusion for Multi-view Spectral Clustering [(matlab)](https://github.com/sckangz/GFSC)
 
 * 2.13 TIP17 Flexible Multi-view Dimensionality co-Reduction [(matlab)](http://cic.tju.edu.cn/faculty/zhangchangqing/code.html)
 
 * 2.14 ICML19 COMIC: Multi-view Clustering Without Parameter Selection [(python)](https://github.com/limit-scu/2019-ICML-COMIC)

 * 2.15 AAAI20 Multi-View Clustering in Latent Embedding Space [(matlab)](https://github.com/Ttuo123/MCLES)
 
 * 2.16 PR19 Multi-view Subspace Clustering with Intactness-Aware Similarity [(matlab)](http://www.cbsr.ia.ac.cn/users/xiaobowang/)

 ### 3. Self-representation based methods
     Self-representation means that each data sample is expressed by a linear combination of other samples in the same subspace.

 * 3.1 AAAI18 Consistent and Specific Multi-View Subspace Clustering [(matlab)](https://github.com/XIAOCHUN-CAS/Consistent-and-Specific-Multi-View-Subspace-Clustering)

 * 3.2 The method in 2.8 is also a self-representation based method. 
 
 * 3.3 PR18 Multi-view Low-rank Sparse Subspace Clustering [(matlab)](https://github.com/mbrbic/Multi-view-LRSSC)
 
 * 3.4 CVPR15 Diversity-induced Multi-view Subspace Clustering [(matlab)](https://hzfu.github.io/)
 
 * 3.5 TIP19 Split Multiplicative Multi-view Subspace Clustering [(matlab)](https://qianqianxu010.github.io/publications/)
 
 ### 4. Tensor based methods
     The tensor is the generalization of the matrix concept. And the matrix case is a 2-order tensor.

 * 4.1 TNNLS18 Multiview Subspace Clustering via Tensorial t-Product Representation [(matlab)](http://www.scholat.com/portaldownloadFile.html?fileId=4623)

 * 4.2 ICCV15 Low-Rank Tensor Constrained Multiview Subspace Clustering [(matlab)](http://cic.tju.edu.cn/faculty/zhangchangqing/code.html)
 
 * 4.3 TIP19 Essential tensor learning for multi-view spectral clustering [(matlab)](https://github.com/Jlwu1992/Code-for-ETLMSC/tree/c83e5b336ca2490bbfb32415930326e0536391f1)
 
 ### 5. Kernel learning based methods

 * 5.1 N18 Local kernel alignment based multi-view clustering using extreme learning machine [(matlab)](https://github.com/frash1989/Local-Kernel-Alignment-Based-Multi-view-Clustering-Using-ELM)
 
  ### 6. Dictionary learning based methods

 * 6.1 Access18 Multi-view Analysis Dictionary Learning for Image Classification [(matlab)](https://github.com/qianyuwang/MvADL)
 
 * 6.2 TIP16 Multimodal Task-Driven Dictionary Learning for Image Classification[(matlab)](https://github.com/soheilb/multimodal_dictionary_learning)
 
  ### 7. Deep learning based or network based methods

 * 7.1 TIP19 Multi-view Deep Subspace Clustering Networks [(python)](https://github.com/huybery/MvDSCN)
 
 * 7.2 NIPS19 CPM-Nets: Cross Partial Multi-View Networks [(python)](https://github.com/hanmenghan/CPM_Nets)
 
 * 7.3 AAA18 Deep Multi-View Spatial-Temporal Network for Taxi Demand Prediction [(python)](https://github.com/huaxiuyao/DMVST-Net)

 * 7.4 TKDE20 MV-RNN: A Multi-View Recurrent Neural Network for Sequential Recommendation [(python)](https://github.com/CRIPAC-DIG/MV-RNN)

 * 7.5 TIP19 Multi-View Linear Discriminant Analysis Network [(python)](https://github.com/penghu-cs/MvLDAN)

 * 7.6 TIP19 Deep Multi-View Learning Using Neuron-Wise Correlation-Maximizing Regularizers [(python)](https://github.com/JiehongLin/CorrReg)
 
 * 7.7 ICCV15 Multi-view Convolutional Neural Networks for 3D Shape Recognition [(matlab)](https://github.com/suhangpro/mvcnn)

 * 7.8 CVPR19 AE2-Nets:Autoencoder in Autoencoder Networks [(python)](https://github.com/willow617/AE2-Nets)
 
 * 7.9 IJCAI19 Multi-view Spectral Clustering Network [(python)](https://github.com/limit-scu/2019-IJCAI-MvSCN)
  
 * 7.10 ICCV19 Reciprocal Multi-Layer Subspace Learning for Multi-View Clustering [(matlab)](https://github.com/limit-scu/2019-ICCV-RMSL)
 

 ### 8. SVM based methods

 * 8.1 TNNLS18 Multiview Privileged Support Vector Machines [(matlab)](https://github.com/tangjingjing13/psvm_2v)

 * 8.2 KBS18 Multi-view learning based on Nonparallel Support Vector Machine [(matlab)](https://github.com/tangjingjing13/mvnpsvm)

 * 8.3 IS19 Coupling Privileged Kernel Method for Multi-view Learning [(matlab)](https://github.com/tangjingjing13/rpsvm2v)

 ## Part B: multi-view applications with code 

 ### 1. Incomplete or partial multi-view learning
     Some views of samples are missing.

 * 1.1 AAAI19 Unified Embedding Alignment with Missing Views Inferring for Incomplete Multi-View Clustering [(matlab)](http://www.yongxu.org/lunwen.html)

 * 1.2 ECML15 Multiple Incomplete Views Clustering via Weighted Nonnegative Matrix Factorization with L2,1 Regularization [(matlab)](https://github.com/software-shao/Multi-Incomplete-view-Clustering)

 * 1.3 BD16 Online Multi-view Clustering with Incomplete Views [(matlab)](https://github.com/software-shao/online-multiview-clustering-with-incomplete-view)

 * 1.4 IJCAI16 Incomplete Multi-Modal Visual Data Grouping [(matlab)](https://github.com/hdzhao/IMG)

 * 1.5 TC20 Generalized Incomplete Multiview Clustering With Flexible Locality Structure Diffusion [(matlab)](https://sites.google.com/view/jerry-wen-hit/publications)

 ### 2. Person Re-Identification

 * 2.1 TPAMI18 Person Re-Identification by Cross-View Multi-Level Dictionary Learning [(matlab)](https://sites.google.com/view/shengli)
 
 ### 3. Outlier detection

 * 3.1 TKDD18 Multi-View Low-Rank Analysis with Applications to Outlier Detection [(matlab)](http://cobweb.cs.uga.edu/~shengli/?tdsourcetag=s_pcqq_aiomsg)

 * 3.2 AAAI18 Partial Multi-View Outlier Detection [(matlab)](https://github.com/eeGuoJun/AAAI2018_CL)

 ### 4. Zero shot learning

 * 4.1 ECCV14 Transductive Multi-view Embedding for Zero-Shot Recognition and Annotation [(matlab)](https://yanweifu.github.io/embedding/index.html)
 
 ### 5. Multi-label learning

 * 5.1 SIAM SDM18 Multi-view Weak-label Learning based on Matrix Completion [(matlab)](http://mlda.swu.edu.cn/codes.php?name=McWL)
      - Weak-label learning is an important branch of multi-label learning. 
      
 ### 6. Online learning      
 
 * 6.1 ICDM16 Online Unsupervised Multi-view Feature Selection [(matlab)](https://github.com/software-shao/Online-Unsupervised-Multiview-Feature-Selection)
     
 ### 7. Multi-Instance learning

 * 7.1 AAA19 Multi-View Multi-Instance Multi-Label Learning based on Collaborative Matrix Factorization [(matlab)](http://mlda.swu.edu.cn/codes.php?name=M3Lcmf)

 ### 8. Large-scale clustering
 
 * 8.1 AAAI20 Large-scale Multi-view Subspace Clustering in Linear Time [(matlab)](https://github.com/sckangz/LMVSC)
 

