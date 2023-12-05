# Multi-view learning methods with code
     Datasets attached with the code can be found at the end of the page.
## Part A: general multi-view methods with code 

### 1. NMF (non-negative matrix factorization) based methods
     NMF factorizes the non-negative data matrix into two non-negative matrices.

 * 1.1 AAAI17 Multi-View Clustering via Deep Matrix Factorization [(matlab)](https://github.com/hdzhao/DMF_MVC)
    - Deep Matrix Factorization is a variant of NMF.
    
 * 1.2 ICPR16 Partial Multi-View Clustering Using Graph Regularized NMF [(matlab)](https://github.com/nishantrai18/MultiViewNMF)
 
 * 1.3 ICDM16 Multi-View Clustering via Concept Factorization with Local Manifold Regularization [(matlab)](https://github.com/vast-wang/Clustering)
    - Concept Factorization is a variant of NMF.   
    
 * 1.4 TC19 Individuality- and Commonality-Based Multiview Multilabel Learning [(matlab)](http://mlda.swu.edu.cn/publication.php)
 
 * 1.7 S18 Multi-view Discriminative Learning via Joint Non-negative Matrix Factorization [(matlab)](https://www.dropbox.com/s/guohn1zhq073x9f/DICS.zip?dl=0)
 
 * 1.8 ICDM13 Multi-View Clustering via Joint Nonnegative Matrix Factorization [(matlab)](http://jialu.info/)
 
 * 1.9 KBS20 Multi-view clustering by non-negative matrix factorization with co-orthogonal constraints [(matlab)](https://github.com/liangnaiyao/NMFCC)
 
 * 1.10 KBS20 Semi-supervised Multi-view Clustering with Graph-regularized Partially Shared Non-negative Matrix Factorization [(matlab)](https://github.com/liangnaiyao/GPSNMF)
 
 * 1.11 NC18 Adaptive Structure Concept Factorization for Multiview Clustering [(matlab)](https://github.com/kunzhan/MVCF)
     - Concept Factorization is a variant of NMF.   
     
 * 1.12 ICDE20 A Novel Approach to Learning Consensus and Complementary Information for Multi-View Data Clustering [(matlab)](https://github.com/khanhluongds/Multi-view-Clustering-2CMV)
 
 * 1.13 ECCV20 SPL-MLL: Selecting Predictable Landmarks for Multi-Label Learning [(python)](https://github.com/yidaiqiushen/SPL-MLL)

 * 1.14 PR20 Auto-weighted Multi-view Clustering via Deep Matrix Decomposition [(matlab)](https://github.com/huangsd/DeepMVC)

 * 1.15 TKDE(Early Access) Learning Inter- and Intra-manifolds for Matrix Factorization-based Multi-Aspect Data Clustering [(matlab)](https://github.com/khanhluongds/Multi-viewClustering_DiMMA)
 
 * 1.16 IPM22 Co-consensus semi-supervised multi-view learning with orthogonal non-negative matrix factorization [(matlab)](https://github.com/liangnaiyao/CONMF)

### 2. Graph based methods
     It contains two kinds of methods. The first kind is using a predefined or leaning graph (also resfer to the traditional spectral clustering), and performing post-processing spectral clustering or k-means. And the second kind is to learn the graph and the index matrix simultaneously. 
     
 * 2.1 ICDM19 Consistency Meets Inconsistency: A Unified Graph Learning Framework for Multi-view Clustering [(matlab)](https://github.com/youweiliang/ConsistentGraphLearning)
 
 * 2.2 TIP19 Multiview Consensus Graph Clustering [(matlab)](https://github.com/kunzhan/MCGC)

 * 2.3 TIP18 Auto-Weighted Multi-View Learning for Image Clustering and Semi-Supervised Classification [(python)](https://github.com/Zing22/mlan)
     - The conference variant is AAAI17 Multi-View Clustering and Semi-Supervised Classification with Adaptive Neighbours.
 
 * 2.4 TKDE19 GMC Graph-based Multi-view Clustering [(matlab)](https://github.com/cshaowang/gmc)
 
 * 2.5 BD17 Multi-View Graph Learning with Adaptive Label Propagation [(matlab)](http://cobweb.cs.uga.edu/~shengli/?tdsourcetag=s_pcqq_aiomsg)

 * 2.6 TC18 Graph Learning for Multiview Clustering [(matlab)](https://github.com/kunzhan/MVGL)
 
 * 2.8 TC18 Incomplete Multiview Spectral Clustering With Adaptive Graph Learning [(matlab)](http://www.yongxu.org/lunwen.html)
 
 * 2.10 ACML19 Latent Multi-view Semi-Supervised Classification [(matlab)](https://github.com/sckangz/LMVL)
 
 * 2.11 NN20 Partition level multiview subspace clustering [(matlab)](https://github.com/sckangz/PMSC)

 * 2.12 KBS20 Multi-graph Fusion for Multi-view Spectral Clustering [(matlab)](https://github.com/sckangz/GFSC)
 
 * 2.13 TIP17 Flexible Multi-view Dimensionality co-Reduction [(matlab)](http://cic.tju.edu.cn/faculty/zhangchangqing/code.html)
 
 * 2.14 ICML19 COMIC: Multi-view Clustering Without Parameter Selection [(python)](https://github.com/limit-scu/2019-ICML-COMIC)

 * 2.15 AAAI20 Multi-View Clustering in Latent Embedding Space [(matlab)](https://github.com/Ttuo123/MCLES)
 
 * 2.16 PR19 Multi-view Subspace Clustering with Intactness-Aware Similarity [(matlab)](http://www.cbsr.ia.ac.cn/users/xiaobowang/)

 * 2.17 IF20 Multi-view spectral clustering via integrating nonnegative embedding and spectral embedding [(matlab)](https://github.com/sudalvxin/SMSC)
 
 * 2.18 N19 Auto-weighted multi-view constrained spectral clustering [(matlab)](https://github.com/ViviQian/MVCSC)
 
 * 2.19 KBS19 A Study of Graph-based System for Multi-view Clustering [(matlab)](https://github.com/cswanghao/gbs)

* 2.20 PR19 Auto-weighted Multi-view Clustering via Kernelized Graph Learning [(matlab)](https://github.com/huangsd/MVC-via-kernelized-graph-learning)

* 2.21 TKDE21 Measuring Diversity in Graph Learning: A Unified Framework for Structured Multi-view Clustering  [(matlab)](https://github.com/huangsd/CDMGC)

* 2.22 IJCAI21 Graph Filter-based Multi-view Attributed Graph Clustering [(python)](https://github.com/sckangz/MvAGC)

* 2.23 TCYB21 Structured Graph Learning for Scalable Subspace Clustering: From Single-view to Multi-view [(matlab)](https://github.com/sckangz/SGL)

* 2.24 TKDE20 Multi-View Spectral Clustering with High-Order Optimal Neighborhood Laplacian Matrix [(matlab)](https://github.com/wx-liang/ONMSC-LF)

* 2.25 TKDE21 Consensus Graph Learning for Multi-view Clustering [(matlab&python)](https://github.com/guanyuezhen/CGL)

* 2.26 AAAI20 CGD: Multi-view Clustering via Cross-view Graph Diffusion [(matlab)](https://github.com/ChangTang/CGD)

* 2.27 TKDE21 Multi-view Attributed Graph Clustering [(python)](https://github.com/sckangz/MAGC)

* 2.28 TPAMI (Early Access) Improved Normalized Cut for Multi-view Clustering [(matlab)](https://github.com/Ekin102003/MCMLE)

* 2.29 TIP22 Fast Parameter-free Multi-view Subspace Clustering with Consensus Anchor Guidance [(matlab)](https://github.com/wangsiwei2010/FPMVS-CAG)

* 2.30 TCYB19 Dubbed Contextual Correlation Preserving Multi-View Featured Graph Clustering [(matlab)](https://github.com/he-tiantian/CCPMVFGC) 

* 2.31 TPAMI21 Multi-view Clustering: A Scalable and Parameter-free Bipartite Graph Fusion Method [(matlab, fvnh)](https://pan.baidu.com/s/1ieeDwbV8M3kCzl52bnvfnQ#list/path=%2F) 

 ### 3. Self-representation based methods
     Self-representation means that each data sample is expressed by a linear combination of other samples in the same subspace.

 * 3.1 AAAI18 Consistent and Specific Multi-View Subspace Clustering [(matlab)](https://github.com/XIAOCHUN-CAS/Consistent-and-Specific-Multi-View-Subspace-Clustering)

 * 3.2 The method in 2.8 is also a self-representation based method. 
 
 * 3.3 PR18 Multi-view Low-rank Sparse Subspace Clustering [(matlab)](https://github.com/mbrbic/Multi-view-LRSSC)
 
 * 3.4 CVPR15 Diversity-induced Multi-view Subspace Clustering [(matlab)](https://hzfu.github.io/)
 
 * 3.5 TIP19 Split Multiplicative Multi-view Subspace Clustering [(matlab)](https://qianqianxu010.github.io/publications/)
 
 * 3.6 CVPR17 Exclusivity-Consistency Regularized Multi-view Subspace Clustering [(matlab)](http://cic.tju.edu.cn/faculty/zhangchangqing/code.html)

 * 3.7 TPAMI20 Generalized Latent Multi-view Subspace Clustering [(matlab)](http://cic.tju.edu.cn/faculty/zhangchangqing/code/LMSC_CVPR2017_Zhang.rar)
     - The conference variant is CVPR17 Latent Multi-view Subspace Clustering.
 
 * 3.8 IS21 Multi-view Subspace Clustering via Partition Fusion [(matlab)](https://github.com/LyuJC/PFSC)
 
 * 3.9 TNNLS21 Multiview Subspace Clustering via Co-Training Robust Data Representation [(matlab)](https://github.com/liujiyuan13/CoMSC-code_release)
 
 * 3.10 TKDE20 Consensus One-step Multi-view Subspace Clustering [(matlab)](https://github.com/Jeaninezpp/COMVSC)
 
 * 3.11 NCAA21 Smoothed Multi-View Subspace Clustering [(matlab)](https://github.com/EricliuLiang/SMVSC)

* 3.12 TCSVT21 Generalized Multi-view Collaborative Subspace Clustering [(matlab)](https://github.com/Lan-MC/GMCSC)

* 3.13 AAAI22 Efficient One-pass Multi-view Subspace Clustering with Consensus Anchors [(matlab)](https://github.com/Tracesource/EOMSC-CA)

* 3.14 IJCAI19 Flexible Multi-View Representation Learning for Subspace Clustering [(matlab)](https://github.com/lslrh/FMR)

* 3.15 ICCV19 Reciprocal Multi-Layer Subspace Learning for Multi-View Clustering [(matlab)](https://github.com/lslrh/RMSL)
 
 ### 4. Tensor based methods
     The tensor is the generalization of the matrix concept. And the matrix case is a 2-order tensor.

 * 4.2 ICCV15 Low-Rank Tensor Constrained Multiview Subspace Clustering [(matlab)](http://cic.tju.edu.cn/faculty/zhangchangqing/code.html)

 * 4.3 IJCV20 Tensorized Multi-View Subspace Representation Learning [(matlab)](https://hzfu.github.io/)
      - The conference variant may be ICCV15 Low-Rank Tensor Constrained Multiview Subspace Clustering.
 
 * 4.4 IJCV18 On Unifying Multi-view Self-Representations for Clustering by Tensor Multi-rank Minimization [(matlab)](https://www.researchgate.net/publication/324151918_the_source_of_paper_On_Unifying_Multi-View_Self-Representations_for_Clustering_by_Tensor_Multi-Rank_Minimization)

 * 4.5 TCYB20 Hyper-Laplacian Regularized Multilinear Multi-View Self-Representation for Clustering and Semi-supervised Learning [(matlab)](https://www.researchgate.net/publication/325965851_code_for_Hyper-Laplacian_Regularized_Multilinear_Multi-View_Self-Representation_for_Clustering_and_Semi-supervised_Learning)

 * 4.6 TCSVT21 Multi-View Spectral Clustering Tailored Tensor Low-Rank Representation [(matlab)](https://github.com/jyh-learning/MVSC-TLRR)
 
 * 4.7 TKDE20 TCCANet: Tensor Canonical Correlation Analysis Networks for Multi-view Remote Sensing Scene Recognition [(matlab)](https://github.com/AdvAttack/TCCANet-TKDE)  
 
 ### 5. Kernel learning based methods
     It often uses kernel representation for each view, and then incorporates different views by seeking optimal combination of multiple kernels of different views. 

 * 5.1 N18 Local kernel alignment based multi-view clustering using extreme learning machine [(matlab)](https://github.com/frash1989/Local-Kernel-Alignment-Based-Multi-view-Clustering-Using-ELM)
 
 * 5.2 TKDE20 Optimal Neighborhood Multiple Kernel Clustering with Adaptive Local Kernels [(matlab)](https://github.com/liujiyuan13/ON-ALK_release_code)
 
  ### 6. Dictionary learning based methods

 * 6.1 Access18 Multi-view Analysis Dictionary Learning for Image Classification [(matlab)](https://github.com/qianyuwang/MvADL)
 
 * 6.2 TIP16 Multimodal Task-Driven Dictionary Learning for Image Classification[(matlab)](https://github.com/soheilb/multimodal_dictionary_learning)
 
  ### 7. Deep learning based or network based methods
       Part A 11 self-supervised learning (or contrastive learning) is also based on Deep learning.

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
 
 * 7.11 ICLR20 Learning Robust Representations via Multi-View Information Bottleneck [(python)](https://github.com/mfederici/Multi-View-Information-Bottleneck)
 
 * 7.12 SIAM19 Deep Multi-view Information Bottleneck [(python)](https://github.com/wangqi1919/Code-Deep-Multiview-Information-Bottleneck)
 
 * 7.13 TIP21 Deep Spectral Representation Learning From Multi-View Data [(python)](https://github.com/XLearning-SCU/2021-TIP-MvLNet)
     - The conference variant is IJCAI19 Multi-view Spectral Clustering Network (7.9).
 
 * 7.14 TM21 Self-supervised Graph Convolutional Network For Multi-view Clustering [(python)](https://github.com/xdweixia/SGCMC)

 * 7.15 BD21 CONAN: Contrastive Fusion Networks for Multi-view Clustering [(python)](https://github.com/Guanzhou-Ke/conan)

 * 7.16 NN22 Multi-view graph embedding clustering network: Joint self-supervision and block diagonal representation [(python)]( https://github.com/xdweixia/NN-2022-MVGC)

 ### 8. SVM based methods

 * 8.1 TNNLS18 Multiview Privileged Support Vector Machines [(matlab)](https://github.com/tangjingjing13/psvm_2v)

 * 8.2 KBS18 Multi-view learning based on Nonparallel Support Vector Machine [(matlab)](https://github.com/tangjingjing13/mvnpsvm)

 * 8.3 IS19 Coupling Privileged Kernel Method for Multi-view Learning [(matlab)](https://github.com/tangjingjing13/rpsvm2v)
 
 ### 9. Co-training based methods

 * 9.1 JMLR20 Self-paced Multi-view Co-training [(python)](https://github.com/Flowerfan/SPamCo)
 
 ###  10. Metric Learning based methods
 
* 10.1 IJCAI18 FISH-MML: Fisher-HSIC Multi-View Metric Learning[(matlab)](http://cic.tju.edu.cn/faculty/zhangchangqing/code/FISH.rar)

 ### 11. Self-supervised Learning based methods

* 11.1 ICLR21 Self-supervised Learning from a Multi-view Perspective [(python)](https://github.com/yaohungt/Self_Supervised_Learning_Multiview)

* 11.2 ECCV20 Contrastive Multiview Coding [(python)](https://github.com/HobbitLong/CMC/)

* 11.3 ICML20 Contrastive Multi-View Representation Learning on Graphs [(python)](https://github.com/kavehhassani/mvgrl) 

* 11.4 CVPR21 Partially View-aligned Representation Learning with Noise-robust Contrastive Loss [(python)](https://github.com/XLearning-SCU/2021-CVPR-MvCLN) 

* 11.5 CVPR21 COMPLETER: Incomplete Multi-view Clustering via Contrastive Prediction [(python)](https://github.com/XLearning-SCU/2021-CVPR-Completer) 

* 11.6 AAAI21 Contrastive Clustering [(python)](https://github.com/Yunfan-Li/Contrastive-Clustering) 

* 11.7 The method in 7.14 is also a self-supervised Learning based method.

 ### 12. Least squares regression based methods
 
 * 12.1 PR19 Adaptive-Weighting Discriminative Regression for Multi-View Classification [(matlab)](https://github.com/muliyangm/WeightReg)

 * 12.2 TC20 Multiview Classification With Cohesion and Diversity [(matlab)](https://github.com/taohong08/Multiview-Classification-With-Cohesion-and-Diversity)

 * 12.3 TIP17 Scalable multi-view semi-supervised classification via adaptive regression [(matlab)](https://github.com/taohong08/Scalable-Multi-View-Semi-Supervised-Classification-via-Adaptive-Regression) 

 * 12.4 ML20 Joint Consensus and Diversity for Multi-view Semi-supervised Classification [(matlab)](https://github.com/ChenpingHou/Joint-Consensus-and-Diversity-for-Multi-view-Semi-supervised-Classification) 

 ### 13. Discriminant analysis based methods

 ### 14. Boosting based methods
 
 * 14.1 N19 Multiview Boosting by Controlling the Diversity and the Accuracy of View-specific Voters [(python)](https://github.com/goyalanil/PB-MVBoost)

 ### 15. SNE (Stochastic Neighbour Embedding) based methods
 
 * 15.1 arXiv21 Multi-view Data Visualisation via Manifold Learning [(python)](https://github.com/theorod93/multiView_manifoldLearning)

 ## Part B: multi-view applications with code 

 ### 1. Incomplete or partial multi-view learning
     Some views of samples are missing.

 * 1.1 AAAI19 Unified Embedding Alignment with Missing Views Inferring for Incomplete Multi-View Clustering [(matlab)](http://www.yongxu.org/lunwen.html)

 * 1.2 ECML15 Multiple Incomplete Views Clustering via Weighted Nonnegative Matrix Factorization with L2,1 Regularization [(matlab)](https://github.com/software-shao/Multi-Incomplete-view-Clustering)

 * 1.3 BD16 Online Multi-view Clustering with Incomplete Views [(matlab)](https://github.com/software-shao/online-multiview-clustering-with-incomplete-view)

 * 1.4 IJCAI16 Incomplete Multi-Modal Visual Data Grouping [(matlab)](https://github.com/hdzhao/IMG)

 * 1.5 TC20 Generalized Incomplete Multiview Clustering With Flexible Locality Structure Diffusion [(matlab)](https://sites.google.com/view/jerry-wen-hit/publications)
 
 * 1.6 IJCAI19 Spectral Perturbation Meets Incomplete Multi-view Data [(matlab)](https://github.com/cshaowang/pic)

 * 1.7 TPAMI, in press, Deep Partial Multi-View Learning [(python)](https://github.com/hanmenghan/CPM_Nets) 
      - The conference variant is NIPS19 CPM-Nets: Cross Partial Multi-View Networks.
    
 * 1.8 TPAMI20 Efficient and Effective Regularized Incomplete Multi-view Clustering [(matlab)](https://github.com/xinwangliu/TPAMI_EEIMVC)

 * 1.9 TPAMI19 Late Fusion Incomplete Multi-view Clustering [(matlab)](https://github.com/xinwangliu/Late-Fusion-Incomplete-Multi-view-Clustering)

 * 1.10 ICME21 Tensor-based Multi-view Block-diagonal Structure Diffusion for Clustering Incomplete Multi-view Data [(matlab)](https://github.com/ChangTang/TMBSD)
 
 * 1.11 NeurIPS20 Partially View-aligned Clustering [(python)](https://github.com/hi-zhenyu/PVC)

 * 1.12 TAI22 Incomplete Multiview Clustering with Cross-view Feature Transformation [(matlab)](https://github.com/liangnaiyao/CFTIMC)

 * 1.13 AAAI22 Deep Incomplete Multi-View Clustering via Mining Cluster Complementarity [(python)](https://github.com/SubmissionsIn/DIMVC)
 
 * 1.14 TKDE22 Incomplete Multi-view Clustering with Sample-level Auto-weighted Graph Fusion [(matlab)](https://github.com/liangnaiyao/SAGF_IMC)
  
 ### 2. Person Re-Identification

 * 2.1 TPAMI18 Person Re-Identification by Cross-View Multi-Level Dictionary Learning [(matlab)](https://sites.google.com/view/shengli)
 
 ### 3. Outlier detection

 * 3.1 TKDD18 Multi-View Low-Rank Analysis with Applications to Outlier Detection [(matlab)](http://cobweb.cs.uga.edu/~shengli/?tdsourcetag=s_pcqq_aiomsg)

 * 3.2 AAAI18 Partial Multi-View Outlier Detection [(matlab)](https://github.com/eeGuoJun/AAAI2018_CL)

 ### 4. Zero shot learning

 * 4.1 ECCV14 Transductive Multi-view Embedding for Zero-Shot Recognition and Annotation [(matlab)](https://yanweifu.github.io/embedding/index.html)
 
 ### 5. Multi-label learning or Weak-label learning
      - Weak-label learning is an important branch of multi-label learning. 

 * 5.2 Access19 Multi-View Multi-Label Learning With View-Label-Specific Features [(matlab)](https://github.com/jiunhwang/Date_and_Code/blob/master/code_and_data/VLSF-public.zip)
 
 * 5.3 The method in 1.4 is also a multi-label learning method.

 ### 6. Online learning      
 
 * 6.1 ICDM16 Online Unsupervised Multi-view Feature Selection [(matlab)](https://github.com/software-shao/Online-Unsupervised-Multiview-Feature-Selection)
     
 ### 7. Multi-Instance learning

 ### 8. Large-scale clustering
 
 * 8.1 AAAI20 Large-scale Multi-view Subspace Clustering in Linear Time [(matlab)](https://github.com/sckangz/LMVSC)
 
 * 8.2 AAAI15 Large-scale multi-view spectral clustering via bipartite graph [(matlab)](https://github.com/zzz123xyz/MVSC)
 
 ### 9. Non-independently and Non-identically Distributed Complex Noise
 
 * 9.1 TNNLS19 Robust Multi-view Subspace Learning with Non-independently and Non-identically Distributed Complex Noise [(matlab)](https://github.com/zsyOAOA/NIID-MSL/tree/master/inexact_alm_rpca)

 ### 10. Multiview training boost Single-view test
 
 * 10.1 TPAMI20 Multiview Feature Selection for Single-view Classification [(matlab)](https://github.com/mkomeili/MVSV)

 ### 11. Fuzzy clustering
 
 * 11.1 PR21 Collaborative feature-weighted multi-view fuzzy c-means clustering [(matlab)](https://github.com/ChrisSinaga02/Collaborative_MVFCM)

 ### 12. Trusted (or reliable) learning

 * 12.1 ICLR21 Trusted Multi-View Classification [(python)](https://github.com/hanmenghan/TMC)

 * 12.2 AAAI18 Reliable multi-view clustering [(matlab)](https://github.com/taohong08/reliable-multi-view-clustering)

 ### 13. 3D point cloud registration

 * 13.1 CVPR20 Learning multiview 3D point cloud registration [(python)](https://github.com/zgojcic/3D_multiview_reg)

 ### 14. Recommendation
 
  * 14.1 SIGIR20 MVIN: Learning Multiview Items for Recommendation [(python)](https://github.com/johnnyjana730/MVIN) 

 ### 15. Shape Reconstruction
 
  * 15.1 MIPS19 Multiview Aggregation for Learning Category-Specific Shape Reconstruction [(python)](https://github.com/drsrinathsridhar/xnocs) 

 ### 16. 3D Object Recognition
 
  * 16.1 CVPR20 Views Self Supervised and Regularized Learning for 3D Object Recognition [(python)](https://github.com/chihhuiho/VISPE) 

 ### 17. Remote Sensing Scene Representations
 
  * 17.1 CVPR21 Self-Supervised Learning of Remote Sensing Scene Representations Using Contrastive Multiview Coding [(python)](https://github.com/vladan-stojnic/CMC-RSSR) 

 ### 18. View generation
 
  * 18.1 ECCV18 Multi-view to Novel view: Synthesizing Novel Views with Self-Learned Confidence [(python)](https://github.com/shaohua0116/Multiview2Novelview) 

 ### 19. Dialog Intent Induction

  * 19.1 EMNLP19 Dialog Intent Induction with Deep Multi-View Clustering [(python)](https://github.com/asappresearch/dialog-intent-induction) 

 ### 20. Partially View-unaligned Problem
 
   * 20.1 TPAMI(Early Access) Robust Multi-view Clustering with Incomplete Information [(python)](https://github.com/XLearning-SCU/2022-TPAMI-SURE) 

 ### 21. Cancer Subtype Identification
 
   * 21.1 TCBB22 Multi-view Robust Graph-based clustering for Cancer Subtype Identification [(matlab)](https://github.com/sxf118/MRGC)

 ## Part C: Others 

 * 1.1 Multi-view dataset
 
         example: dataset name (the mark refers to the paper listed above)
          
    - yale_mtv [(Part A 1.1)](https://github.com/hdzhao/DMF_MVC/tree/master/data)

    - 20newsgroups, 3sources, BBC4view_685, BBCSport2view_544, WikipediaArticles [(Part A 1.3)](https://github.com/vast-wang/Clustering/tree/master/Code_MVCC/Dataset)

 * 1.2 famous authors in the field of multi-view learning
  
         private opinions
         
      - Feiping Nie [(Google Scholar Citations)](https://scholar.google.com/citations?user=2oB4nAIAAAAJ&amp;hl=en) 

      - Changqing Zhang [(Google Scholar Citations)](https://scholar.google.com.hk/citations?hl=zh-CN&user=yJGhdykAAAAJ&view_op=list_works&sortby=pubdate) [(home)](http://cic.tju.edu.cn/faculty/zhangchangqing/research.html)
  
      - Xinwang Liu [(Google Scholar Citations)](https://scholar.google.com.hk/citations?user=A56vWC4AAAAJ&hl=zh-CN&oi=ao) 

 * 1.3 other github pages with code      
 
      - awesome multi-view clustering [(page)](https://github.com/wangsiwei2010/awesome-multi-view-clustering)
 
      - A Survey of Multi-view Clustering Approaches [(page)](https://github.com/dugzzuli/A-Survey-of-Multi-view-Clustering-Approaches)
