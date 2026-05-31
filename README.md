# Breast-Cancer-Data-Analysis-Using-R
Visualization of biological data corresponding to the gene expression of breast cancer patients using R.

# Structure 
```text
breast-cancer-gene-expression-analysis/
│
├── data/
│   ├── data_complete.csv
│   └── labels.csv
│
├── scripts/
│   └── activity1_analysis.Rmd
│
├── results/
│   ├── boxplots/
│   ├── histograms/
│   └── heatmaps/
│
├── README.md
├── .gitignore
└── activity1_analysis.html
```

<p align="center">
<pre>
TargetScan
     ↓
Target Gene Identification
     ↓
Venn Diagram Analysis
     ↓
Common Target Genes
     ↓
UniProt Functional Annotation
     ↓
GO Biological Process
KEGG Pathways
Reactome
     ↓
Biological Interpretation
</pre>
</p>

graph TD
    A[TargetScan] --> B[Target Gene Identification]
    B --> C[Venn Diagram Analysis]
    C --> D[Common Target Genes]
    D --> E[UniProt Functional Annotation]
    E --> F[GO Biological Process<br>KEGG Pathways<br>Reactome]
    F --> G[Biological Interpretation]

    %% Estilos para que se vea limpio
    style A fill:#f9f9f9,stroke:#333,stroke-width:1px
    style B fill:#f9f9f9,stroke:#333,stroke-width:1px
    style C fill:#f9f9f9,stroke:#333,stroke-width:1px
    style D fill:#f9f9f9,stroke:#333,stroke-width:1px
    style E fill:#f9f9f9,stroke:#333,stroke-width:1px
    style F fill:#f9f9f9,stroke:#333,stroke-width:1px
    style G fill:#f9f9f9,stroke:#333,stroke-width:1px
