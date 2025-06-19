# Structured Literature Review Dataset: Semantic Information Models in Automation

This repository provides the dataset used in our structured literature review (SLR) on the use of semantic information models in the domains of **manufacturing automation**, **energy systems**, and **building automation**. The dataset is stored as a `.bib` file (`slr-results.bib`) and includes grouped entries based on **technologies**, **application domains**, and **data sources**.

<p align="center">
   <img align="middle" height="500px" src="https://github.com/hsu-aut/semantic-technology-literature-search/blob/documentation/images/images/SLR_result-screenshot.jpg?raw=true">
</p>

## ▶️ Content and Usage Instructions

1. Open `slr-results.bib` in **JabRef** (version 5.x recommended).
2. Use the **Groups pane** (left sidebar) to filter and browse entries by:
   - Technology  
   - Application domain  
   - Data source  
3. Each entry includes all metadata such as title, authors, year, and venue.

You can filter by groups. The group structure includes:
  - **Technologies**:
    - Semantic Web  
    - OPC UA  
    - AML  
    - SysML / UML  
    - AAS  
  - **Application Domains**:
    - Manufacturing  
    - Energy Systems  
    - Construction  
  - **Data Sources**:
    - IEEE Xplore  
    - Scopus

## 🔎 Background

For an analysis of semantic technologies, we conducted a literature search with commonly used technologies:

- **Semantic Web technologies**
- **OPC Unified Architecture (OPC UA)**
- **Automation Markup Language (AML)**
- **Systems Modeling Language (SysML) / Unified Modeling Language (UML)**
- **Asset Administration Shell (AAS)**

## 📘 Query Template

The query template we used looks as shown below. The placeholders ${application domain} and ${technology} need to be resolved with a domain or technology, respectively, to get results for a certain domain and technology. Furthermore, the query is shown in IEEExlpore syntax. For Scopus, the syntax needs to be adapted accordingly.

```
ALL-METADATA (semantic OR knowledge graph OR knowledge base OR knowledge representation OR linked data OR query OR reasoning)
AND
ALL-METADATA(${application domain})
AND
ALL-METADATA(${technology})
```

## 📊 Search Results Summary

| Technology       | Results |
|------------------|---------|
| Semantic Web     | 1,319   |
| SysML / UML      | 193     |
| OPC UA           | 103     |
| AML              | 61      |
| AAS              | 51      |
| **Sum**          | **1,727** |


## 📝 Citation

If you use this dataset in your work, please cite our paper:

🚧 Coming soon... 🚧
---

Feel free to open an issue or submit a pull request if you notice any errors, like to give feedback or want to contribute.

