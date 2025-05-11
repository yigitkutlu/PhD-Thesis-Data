This repository contains supplementary data associated with the thesis "Deciphering the Links Between Protein Dynamics and Evolution" by Yiğit Kutlu. The datasets support the analyses described in Sections 4.1–4.3 of the thesis and are shared here for transparency, reproducibility, and future reuse by the scientific community.

📁 Folder: Binding
This folder contains two Excel files summarizing ligand-binding theme analyses across protein domains with annotated ligands in our dataset.

1. DomainID_LigandName.xlsx
This file provides residue-level annotation of ligand-binding themes for each domain. Each row corresponds to a single theme identified within a domain and includes the following columns:

Domain/PDB ID

Theme ID

Start/End Positions (Sequence)

Ligand Name

Ligand Binding Residues (indices)

Number of Ligand Binding Residues

Number of Ligand Binding Residues Within the Theme

Overlap Percentage (%)

This file allows users to examine how much of the ligand-binding interface is covered by individual reused themes.

2. DomainID_LigandName_bindthemes.xlsx
This file summarizes ligand-binding themes at the domain level, focusing on whether ligand recognition is mediated by one or two themes:

Domain/PDB ID

Ligand Name

First Ligand-Binding Theme ID

Second Ligand-Binding Theme ID (or "single" if only one theme is involved)

This file enables users to explore theme combinations involved in ligand binding and their prevalence across domains.

📁 Folder: Theme_Classification_Detailed
This folder contains one Excel file per protein domain, providing detailed classification results and information transfer data for all themes identified within that domain. Each file is named according to the PDB or domain ID.

Each row corresponds to a theme within the domain and includes the following columns:

Theme ID

Classification — communication role of the theme (e.g., Strong Sender, Receiver, Bidirectional, Weak, etc.) based on GNM-TE results

Average netTE — average net transfer entropy of the residues in the theme

% of Global Source Residues in Theme — percentage of domain-level global source residues found within the theme

% of Global Sink Residues in Theme — percentage of domain-level global sink residues found within the theme

Information Transfer Partners — subsequent columns list the top themes sending information to or receiving it from the current theme, along with associated netTE values

This data enables downstream analysis of dynamic communication roles of themes and their integration into allosteric signaling pathways.

📄 License and Citation
To ensure proper attribution and support transparency in academic research, we recommend the following citation if you use this dataset:

Kutlu, Y. (2025). Deciphering the Links Between Protein Dynamics and Evolution (Doctoral dissertation). Boğaziçi University.

If you are using this repository or its data in published work, please cite the thesis and/or any related papers (e.g., Kutlu et al., 2024).




