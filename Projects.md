---
layout: page
title: Projects
sidebar_link: true
sidebar_sort_order: 3
---
<!--
<a href="/assets/img/CellLa.jpg" data-lightbox="image-1" data-title="Workflow of the epigenetic gene regulation model">
  <img src="assets/img/CellLa.jpg" style="display: block; margin-left: auto; margin-right: auto; width:850px; height:600px;" />
</a>
-->

> ## Epigenetic Gene Regulation Model
<!--
<img src="assets/img/CellLa.jpg" style="display: block; margin-left: auto; margin-right: auto; width:850px; height:600px;" />
<img src="assets/img/CellLa.jpg" style="width:800px; height:500px;" />
![placeholder](/assets/img/CellLa.jpg/800x400 "CellLa")
[ ![](/assets/img/CellLa.jpg) ](/assets/img/CellLa.jpg)
-->
<a href="assets/img/CellLa.jpg" data-lightbox="image-1" data-title="Workflow of the epigenetic gene regulation model">
  <img src="assets/img/CellLa.jpg" style="display: block; margin-left: auto; margin-right: auto; width:850px; height:550px;" />
</a>
The Multi-Attention based Deep Learning model aims to learn regulatory latent space of epigenetic/transcriptional markers such as histone modifications, methylations, and transcription factors.
* Embedding different epigenetic/transcriptional markers into a regulatory latent space using marker-specific architectures such as CNN & RNN with attention (histone modification), RNN with attention (methylation), self-attention network (transcription factor).
* Integrating each latent feature by multi-attention block to interpret relationships between multiple regulatory features.
* In experiments with 18 cell lines, the proposed model predicted the gene expression level more accurately than the state-of-the-art model.
* Reveal the cell-type-specific gene regulation mechanisms and enriched genes in terms of their functions and epigenetic regulation.

> ## Pathway Attention Model
<a href="/assets/img/GCN_MAE_large.png" data-lightbox="image-2" data-title="Workflow of the explainable pathway GCN & attention model">
  <img src="/assets/img/GCN_MAE.png" style="display: block; margin-left: auto; margin-right: auto; width:1000px; height:450px;" />
</a>
The pathway attention model is an explainable deep learning model for predicting cancer subtypes using gene expression data and biological pathways.
* Capturing localized gene expression patterns in pathways by graph convolutional networks (GCNs)
* Reproducing biological mechanisms by combining results of GCN with multi-attention based ensemble
* Identifying transcription factors as regulator of pathways to elucidate subtype-specific biological functions from network propagation algorithm


> ## RKSS Kernel
<a href="/assets/img/RKSS_kernel.png" data-lightbox="image-3" data-title="Workflow of the Ranked K-Spectrum String Kernel">
  <img src="assets/img/RKSS_kernel.png" style="display: block; margin-left: auto; margin-right: auto; width:900px; height:450px;" />
</a>
RKSS kernel aims to measure similarity of DNA sequences in terms of evolutionary distance.
* Extension of the k-spectrum string kernel by utilizing two features for comparative and evolutionary sequence comparison
* Building a common k-mers template "landmark" to mimic common ancestors and reduce features
* Using rank information instead of frequency of k-mers to robust outliers
* Relatively well reconstruct phylogenetic trees of 10 mammalian species on three genomic regions (exon, intron, CpG island)
* Landmark space that is constructed using RKSS kernel effectively represents the genetic properties of the three regions: Order of three regions in terms of evolutionary information (exon > CpG island > intron)

> ## MIDAS
<a href="/assets/img/MIDAS.png" data-lightbox="image-4" data-title="Workflow of the MIDAS">
  <img src="assets/img/MIDAS.png" style="display: block; margin-left: auto; margin-right: auto; width:900px; height:400px;" />
</a>
MIDAS determines condition specific subpaths, each of which has different activities across multiple phenotypes.
* Utilizing explicit gene expression quantity information from RNA-seq data
* Addressing subpath mining problem on multi-class by adopting statistical approaches
* Using a greedy subpath extension method with exponentially increasing criteria to mining complex interaction of genes
