---
layout: post
title: Education, Projects, Research
# date: 2017-09-12 00:00:00 +0300
description: A deeper look into my academic achievements. # Add post description (optional)
img: academic-experience.jpg # Add image post (optional)
# tags: [Productivity, Software] # add tag
visibility: False
---

# Undergraduate
I received my BS degree in Software Engineering from Azad University of Iran. I graduated with a GPA of 3, which I'm not very proud of. As a final project (some kind of thesis for undergraduate) in 2021, I developed an Android app that can send and receive messages like any other messaging app, but it only operates on Bluetooth to connect people in a wide area whereby each person acts as a hub in the network. You can find the source code in the link below.

[Messaging Application using Bluetooth Low Energy (BLE) to Send and Receive Messages](https://github.com/aryazady/BT-Messaging)

Working with Bluetooth API required a great knowledge of Android SDK and there was not much documentation. So, if you encountered a problem it could take you days to resolve it. The skills from my work experience helped me here.

# Graduate
I received my MS degree in Bioinformatics from Sharif University of Technology. I graduated with a GPA of 3.9. I had many projects and implementations which I listed below.

### Implementations
Implementations usually require less innovation and have a defined template.

##### Signal Processing
* [Denosing and Sharping Images using Filters, Fourier Transform, and Classical Approaches](https://github.com/aryazady/projects-coding-experiences/blob/main/Medical%20Image%20Processing/classic_denosing_enhancing.ipynb)

##### Bioinformatics
* [Metagenomics: Analysis and Binning Reads using BusyBee](https://github.com/aryazady/projects-coding-experiences/blob/main/Bioinformatics/metagenomics_binning.ipynb)
* [NGS reads Alignment using HISAT2](https://github.com/aryazady/projects-coding-experiences/blob/main/Bioinformatics/hisat2_aligment.ipynb)

##### Systems Biology
* [Reaction Coupling and Finding Essential Ones](https://github.com/aryazady/projects-coding-experiences/blob/main/Computational%20Biology/coupled_essential_reaction.ipynb)
* [Finding Motifs in E. coli Transcription Network](https://github.com/aryazady/projects-coding-experiences/blob/main/Computational%20Biology/network_motifs_neural_dynamics.ipynb)

##### Computational Genomics
* [Differential Gene Expression Analysis: Full Pipeline](https://github.com/aryazady/projects-coding-experiences/blob/main/Computational%20Genomics/RNA-seq%20alignment/code/alignment_deseq.ipynb)
* [Weighted Correlation Network and Differential Gene Correlation Analysis](https://github.com/aryazady/projects-coding-experiences/blob/main/Computational%20Genomics/WGCNA%20and%20DGCA/gene_network_analysis.ipynb)

##### Deep Learning
* [Image Captioning, COCO Dataset](https://github.com/aryazady/projects-coding-experiences/blob/main/Machine%20Learning/image_captioning_coco.ipynb)
* [MNIST Image Generation: Variational Autoencoder](https://github.com/aryazady/projects-coding-experiences/blob/main/Machine%20Learning/mnist_vae.ipynb)
* [Brain MRI Abnormality Detection using RESNET and VGG](https://github.com/aryazady/projects-coding-experiences/blob/main/Machine%20Learning/brain_mri_anomaly_detection_VGG_RESNET.ipynb)

##### Medical Image Processing
* [Measuring and Analyzing Cell Images using CellProfiler](https://github.com/aryazady/projects-coding-experiences/tree/main/Medical%20Image%20Processing/CellProfiler)
* [Interpretability: Highlighting Damaged Area in Lungs Due to COVID-19](https://github.com/aryazady/projects-coding-experiences/blob/main/Medical%20Image%20Processing/COVID-19_classification_interpretability_gradCam.ipynb)
* [Breast Tumor Histopathological Images Classification using GNN, BRACS Dataset](https://github.com/aryazady/projects-coding-experiences/blob/main/Medical%20Image%20Processing/GNN_pathology.ipynb)
* [Semantic Segmentation of CT-Scan Images](https://github.com/aryazady/projects-coding-experiences/blob/main/Medical%20Image%20Processing/semantic_segmentation_2D_3D_unet.ipynb)

##### Natural Language Processing
* [Drug Name Prediction from its Description](https://github.com/aryazady/projects-coding-experiences/blob/main/Natural%20Language%20Processing/english_description_drug_suggestion_fasttext_mpnet.ipynb)

##### Reinforcement Learning
* [DQN agent with OpenAI Gym's LunarLander-v3 environment](https://github.com/aryazady/projects-coding-experiences/blob/main/Reinforcement%20Learning/DQN.ipynb)
* [SAC and Behavioral Cloning Agents on the CartPole environmnet](https://github.com/aryazady/projects-coding-experiences/blob/main/Reinforcement%20Learning/SAC_Behavioral-Cloning.ipynb)

##### Structral Bioinformatics
* [Extracting Important Information about Protein 2mw4 using TCL language](https://github.com/aryazady/projects-coding-experiences/tree/main/Structral%20Bioinformatics/protein%202mw4)

There are more implementations that you can find in this [repository](https://github.com/aryazady/projects-coding-experiences), and you can explore them in detail.

### Projects
Projects need originality and are programmed from scratch. Also, they require further evaluation and analysis, so it takes much longer.

* [Microarray Gene Expression: Finding Involved Genes in AML](https://github.com/aryazady/projects-coding-experiences/tree/main/Microarray%20Gene%20Expression%20-%20AML%20Involved%20Genes)
* [Fruquintinib Docking and Conformation Optimization](https://github.com/aryazady/projects-coding-experiences/tree/main/Fruquintinib%20Docking%20and%20Configuration%20Optimization)
* [Single-cell RNA Sequencing (scRNA-seq) Analysis](https://github.com/aryazady/projects-coding-experiences/blob/main/Machine%20Learning/scRNA_seq_analysis_pipeline.ipynb)
* [Financial Market Price Prediction using Transformers](https://github.com/aryazady/projects-coding-experiences/tree/main/Natural%20Language%20Processing/Financial%20Market%20Prediction)

# Research
In the second semester, after I learned preliminaries about the Bioinformatics major, I decided to take a deeper look into constraint-based reconstruction and analysis (COBRA) in Systems Biology because I found a specific subfield interesting, strain design. Therefore, I spent my time looking for great ideas to implement.

First, it was the strain design that got my attention. It's a fantastic field that intends to design a metabolic network that satisfies an interest. In the field of COBRA, most of the works want to solve an optimization, which in many cases is not practical. It was difficult for me to come up with a novelty in this field because my background mostly covered concepts in computer engineering, but this field required excessive knowledge of mathematics. Therefore, it took me longer to study plenty of papers to get a better Idea.

I got introduced to objective prediction for the community instead of single strain by a paper that was shared with me by my dissertation advisor, the paper's goal was to predict the proportion of each strain in a microbial consortium, the algorithm name was SteadyCom. I found it appealing so I researched more about it. The interactions between organisms in the community were extraordinary and astounding. In the subject of microbial consortium, you can even design a modular community, which means each organism has a specific role. So, I proposed my first method, *Maximizing Community Growth by Modulation* which includes an optimization to maximize growth by imposing a constraint for each organism to produce a particular metabolite. However, as I mentioned earlier these constrained-based optimizations are not practical.

It was almost impossible to design an optimization that could be practical too, even the most famous papers lack the practicality. So, I decided to solve these problems using Deep Neural Networks. The most or maybe the only important feature in every metabolic network is the topology. Only Graph Neural Networks can capture this characteristic, thus, I proposed a GNN architecture that could predict our objective. Right now I'm working on this idea and looking to achieve a better representation of organisms' fluxome.