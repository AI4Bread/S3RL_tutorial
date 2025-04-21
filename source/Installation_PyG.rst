.. S3RL documentation master file, created by
   sphinx-quickstart on Wed Apr 16 19:43:51 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Installation (PyG framework)
============

Software Dependencies
---------------------
.. code-block:: python

   numpy
   opencv-python
   pandas
   PyYAML
   scanpy
   scikit-learn
   scipy
   timm
   torch-geometric
   torch==1.13.0+cu117
   torchaudio==0.13.0+cu117
   torchvision==0.14.0+cu117

Installation
---------------------

After installing the required packages, simply run the following command to install the S3RL package:

.. code-block:: bash

   pip install S3RL --index-url https://pypi.org/simple


*The code is tested with Python 3.7.12 and PyTorch 1.13.0 on a single NVIDIA GeForce RTX 3090 GPU.
If you encounter any issues, please check the compatibility of the packages in requirements.txt with your Python version.
Additionally, different versions of libraries and different GPU devices may lead to varied outcomes,
so to reproduce our results, please use the same versions and hardware configuration as specified.*


Data Preparation
---------------------

Download the datasets and place them in the Data directory, ensuring the directory structure appears as follows:

.. code-block:: text

   Data
   ├── DLPFCs
   │   ├── 151673
   │   ├── 151674
   │   └── ...
   ├── Human_Breast_Cancer
   └── Mouse_Brain_Anterior

All datasets can be downloaded from the following links:

- `DLPFC <https://github.com/LieberInstitute/spatialLIBD?tab=readme-ov-file#raw-data>`__
- `Nanostring <https://purdue0-my.sharepoint.com/personal/tang385_purdue_edu/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Ftang385%5Fpurdue%5Fedu%2FDocuments%2FSigra%5Fdataset&ga=1>`__
- `Human Breast Cancer <https://www.10xgenomics.com/resources/datasets/human-breast-cancer-block-a-section-1-1-standard-1-1-0>`__
- `Mouse Brain Anterior <https://drive.google.com/drive/folders/1jDmx8IjiGhOD__spuuhFB1fWVDJtv5CU>`__

We also provide the processed datasets for the four datasets used in our experiments, which can be accessed via the link processed datasets <https://github.com/AI4Bread/S3RL/tree/main/Data>__.

Additionally, we offer the SimCLR code used for extracting semantic features from the images, available at the link SimCLR <https://github.com/AI4Bread/S3RL/tree/main/Img_encoder>__.

Finally, the configurations used in our experiments are available at the link configuration <https://github.com/AI4Bread/S3RL/tree/main/Best_cfg>__, enabling the reproduction of the results reported in the paper.