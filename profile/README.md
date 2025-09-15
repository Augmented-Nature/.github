# Augmented Nature

Welcome to **Augmented Nature** — bridging bioinformatics, cheminformatics, and AI-powered data services to help researchers, developers, and scientists access, analyse, and build on rich biological, chemical, and genomic datasets.

---

## 🔍 What We Do

We develop and maintain *Model Context Protocol (MCP) Servers* that expose structured APIs for a wide range of biological / chemical / genomic resources. Our goal is to make it easier to integrate, query, and visualise data from trusted databases in a standardised way.

---

## 📚 Repositories & Key Services

Here are some of our active repositories and what they offer:

| Repository | Summary |
|------------|---------|
| **OpenFDA-MCP-Server** | MCP server for the OpenFDA dataset (drug and device regulatory info in the US). |
| **OpenGenes-MCP-Server** | Enables querying of “Open Genes” data with the Model Context Protocol. |
| **ClinicalTrials-MCP-Server** | Access to clinical trials information exposed via MCP. |
| **BioThings-MCP-Server** | MCP interface to curated biological data (various sources). |
| **AlphaGenome-MCP-Server** | (Tentative) Genome-scale data served through MCP for various alpha (reference) genomes. |
| **NCBI-Datasets-MCP-Server** | Access to NCBI Datasets API; search and retrieve genomic, taxa, etc. |
| **SureChEMBL-MCP-Server** | Chemical patent database from SureChEMBL via MCP. |
| **KEGG-MCP-Server** | Pathways, genes, compounds, etc. via KEGG database. |
| **UniProt-MCP-Server** | Representation of the UniProt protein database via MCP. |
| **ChEMBL-MCP-Server** | Chemical bioactivity data via ChEMBL exposed by MCP. |
| **AlphaFold-MCP-Server** | Protein structure predictions and associated metadata from AlphaFold. |
| **PDB-MCP-Server** | Protein Data Bank structures and related data. |
| **STRING-db-MCP-Server** | Protein interaction networks via STRING database. |
| **PubChem-MCP-Server** | Compounds, properties, bioassays etc from PubChem. |
| **OpenTargets-MCP-Server** | Gene-drug-disease association data from Open Targets. |
| **Reactome-MCP-Server** | Pathways and systems biology content via Reactome. |
| **Ensembl-MCP-Server** | Genomic annotations, comparative genomics, etc via Ensembl. |
| **GeneOntology-MCP-Server** | Ontology and annotation info via Gene Ontology. |
| **ProteinAtlas-MCP-Server** | Expression and spatial proteomics via Protein Atlas. |
| **BioOntology-MCP-Server** | Various biomedical ontologies accessible via MCP. |

---

## ✅ Why Use Our MCP Servers

- **Standardised interface**: All datasets are served under a common protocol (MCP), so integration across datasets is consistent.  
- **Broad coverage**: From clinical trials, proteins, pathways, compounds to ontologies, you get many of the key bio / chem / genomic data sources.  
- **Open source, MIT-licensed**: You can use, modify, and build upon our code with minimal restrictions.  
- **Ease of deployment**: Designed to be lightweight and scalable, suitable for research or production use.

---

## 🛠 Getting Started

To use any of our MCP servers:

1. Pick the MCP server for the dataset you need (for example, `UniProt-MCP-Server`).
2. Review its README in that repo for usage instructions (installation, endpoints, examples).
3. Use REST calls / HTTP clients to query the endpoints. Most servers support typical query parameters (filters, paging, etc.).
4. Combine or chain calls across servers for richer workflows (e.g. combine UniProt + STRING + Reactome).

---

## 📅 Recent Activity & Plans

- Many of our repos have been updated in mid-2025, showing active maintenance. ([See all repositories](https://github.com/orgs/Augmented-Nature/repositories))  
- Ongoing work includes expanding coverage of more datasets, improving documentation and examples, and enhancing performance / stability.  
- Also plan to add more example client libraries (Python / JS), dashboards, tutorials for “multi-MCP workflows.”

---

## 👥 Get Involved

We welcome contributions! Whether it’s code, documentation, examples, or dataset requests. Some ways to help:

- Open issues or feature requests in repos where functionality is missing.  
- Submit pull requests to fix bugs or add features.  
- Contribute example scripts or notebooks using the MCP servers.  
- Suggest new data sources you’d like to see integrated.

---

## 📫 Contact

For questions, feedback, or suggestions:

- Open an issue in the relevant repository  
- Merge requests are welcome  
- You can reach us via **[moudather.chelbi@gmail.com]** 
---

Thanks for checking out **Augmented Nature**! We hope this helps you harness bioinformatics/cheminformatics data more efficiently.
