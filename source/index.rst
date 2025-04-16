.. S3RL documentation master file, created by
   sphinx-quickstart on Wed Apr 16 19:43:51 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

S3RL – Separable Spatial Single-cell Transcriptome Representation Learning via Graph Transformer and Hyperspherical Prototype Clustering
=============================================================================

.. toctree::
   :maxdepth: 1

   Installation_pyG
   T1_DLPFC
   T2_MouseBrain
   T3_Slide-seqV2
   T4_Stereo
   T5_3D
   T6_Denoising
   T7_pyG
   T8_Batch
   T9_STARmap
   AT1
   AT2

.. image:: ../Figure1_newv3.pdf
   :width: 600


News
========
2025.04.10 S3RL is now available on GitHub at https://github.com/AI4Bread/S3RL.  
S3RL is implemented based on PyTorch Geometric (pyG) and supports efficient training and flexible batch processing for large-scale spatial transcriptomics datasets.  

The model provides enhanced spatial representation learning through the use of a Graph Transformer architecture and hyperspherical prototype clustering for clear domain separation.  
Please refer to Tutorials 7 and 8 for training strategies and batch processing guidance.

Introduction
========
S3RL is a novel framework designed for spatial clustering, denoising, and interpretation of spatially resolved transcriptomics (ST) data. 

By leveraging a Graph Transformer encoder and hyperspherical prototype clustering, S3RL effectively captures both gene expression patterns and spatial dependencies.  
It constructs a separable embedding space where cells with similar transcriptional and spatial features are compactly grouped while maintaining angular separation across distinct spatial domains.

The learned low-dimensional embeddings and reconstructed expression matrices can be directly used for a variety of downstream tasks, including spatial domain identification, visualization, spatial trajectory inference, denoising, and multi-slice or 3D tissue integration.

Citation
========
Fu, Laiyi, and [Your collaborators]. "S3RL: Separable Spatial Single-cell Transcriptome Representation Learning via Graph Transformer and Hyperspherical Prototype Clustering." *[Target Journal]*, 2025.