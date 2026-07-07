# RNA-seq-Analysis
Tools:
GEOquery (data retrieval from GEO)
DESeq2 (differential expression analysis)
ggplot2 (visualization)
pheatmap / ComplexHeatmap (heatmaps)
clusterProfiler (GO / pathway enrichment)
org.Hs.eg.db (gene annotation)

#Deliverables:
Quality-controlled expression dataset
Differentially expressed gene (DEG) table (log2FC, p-value, FDR)
Volcano plot (annotated key genes)
PCA plot (sample clustering)
Heatmap of top DEGs
GO enrichment results (Biological Processes)
KEGG pathway enrichment (optional)
Publication-ready figures

# RNA-seq Analysis of Schizophrenia Neurons (GSE107638)

## Overview
This project analyzes RNA-seq data from NeuN+ neuronal nuclei obtained from schizophrenia and control human brain samples. The goal is to identify differentially expressed genes and explore disrupted biological pathways.

## Dataset
- GEO: GSE107638
- Samples: 50 total (23 schizophrenia, 27 control)
- Tissue: NeuN+ neurons (human brain)

## Workflow

1. Data import (GEO count matrix)
2. Quality control and sample annotation
3. Filtering low-count genes
4. Normalization using DESeq2
5. Variance stabilizing transformation (VST)
6. Exploratory analysis (PCA, sample distances)
7. Differential expression analysis
8. Functional enrichment analysis (GO)

## Key Results

### Differential Expression
- Total significant DEGs: 1,106 (FDR < 0.05)

### Top Upregulated Genes
- PEG10
- HSP90AA1
- PDK4
- TDO2

### Top Downregulated Genes
- SHANK3
- GRID1
- GPC1

## Biological Insights
- Synaptic dysfunction and altered neuronal signaling
- Metabolic reprogramming (PDK4)
- Stress-response activation (HSP90AA1)
- Potential involvement of retrotransposon-derived gene PEG10

## Tools Used
- R / Bioconductor
- DESeq2
- GEOquery
- clusterProfiler
- ggplot2
- org.Hs.eg.db

## Figures
- PCA plot
- Volcano plot
- Heatmap
- GO enrichment plot

## Author
Roya keshvari
