# Title: cell-cell-communication
## Name: Angela B. Villegas 
## Biological Question

- What structural and functional evidence supports the role of membrane-bound CD86 on dendritic cells in triggering CD28-mediated T-cell activation and interleukin-2 (IL-2) expression?

## Part A. Choose and Register Your Sender Cell (10–15 min)

| Category | Information |
|---|---|
| Sender cell | Dendritic cell |
| Tissue/context | Peripheral tissues |
| Biological context | Inflammation, repair, metabolism, etc. |

---

## Part B. Discover a Candidate Signal Produced by the Sender Cell (25–35 min)

| Category | Information |
|---|---|
| Sender cell | Dendritic cell |
| Candidate ligand | CD86 molecule |
| Official gene symbol | CD86 |
| Proposed communication | contact-dependent (juxtacrine) signaling |
| Evidence of production | The Human Protein Atlas reports CD86 gene expression in dendritic cells, supporting the selection of CD86 as a candidate signaling molecule produced by the sender cell. |
| Source | HPA / UniProt |

---

## Part C. Identify the Receptor and Receiver Cell (20–30 min)

| Category | Information |
|---|---|
| Ligand | CD86 (B7-2) |
| Receptor | CD28 (or CTLA-4) |
| Receiver cell | T lymphocyte / CD4+ Helper T cell (or Naïve T cell) |
| Signaling context | Antigen presentation and T-cell costimulation during immune response activation. |
| Supporting source(s) | OmniPath: Confirms CD86 annotated as an intercellular membrane ligand binding to CD28. |
| Supporting source(s) | Human Protein Atlas / UniProt: Confirms CD86 expressed on dendritic cells (cDC) and CD28 localized on the plasma membrane of T cells. |
| Checkpoint | The dendritic cell presents CD86, which can signal through CD28 on T cells in the context of T-cell costimulation during adaptive immune activation. |

---

## Part D. Explore the Receptor-Centered Network in STRING (25–35 min)

| Category | Information |
|---|---|
| Enriched Pathway / Process / Term | GO:2000516 – Positive regulation of CD4-positive, alpha-beta T cell activation. |
| Protein 1 | CD4 |
| Protein 2 | CTLA4 |
| Protein 3 | IFNG |
| Protein 4 | IL10 |
| Protein 5 | CD40 |

---

## STRING Network Interpretation 
- The STRING network showed 11 proteins and 55 connections, with a significant enrichment result (p = 1.4 × 10⁻⁷). This suggests that the proteins are functionally related and may work together in immune signaling. The main proteins related to the proposed mechanism were CD86, CD28, and CTLA4, along with CD4, CD40, CD80, and CD83. The cytokines TNF, IFNG, and IL10 were also included and are related to immune-response regulation. These results support the proposed connection between dendritic-cell signaling and T-cell activation. However, STRING shows functional associations, so the connections do not automatically prove that the proteins directly bind or act in a specific sequence. Therefore, the network supports the overall signaling model, while the exact order of the intracellular pathway is still a proposed interpretation.


## Part E. Validate One Molecular Interaction in IntAct (20–30 min)

| Category | Information |
|---|---|
| Interacting molecules – Molecule A | CD86 (Human / *Homo sapiens*, UniProt ID: P42081) |
| Interacting molecules – Molecule B | CD28 (Human / *Homo sapiens*, UniProt ID: P10747) |
| Experimental detection method | Fluorescence-activated cell sorting |
| Organism | Human / *Homo sapiens* |
| Publication/reference | Publication IDs: 27708164 |
| Title/Citation | Levy, R., Rotfogel, Z., Hillman, D., Popugailo, A., Arad, G., Supper, E., Osman, F., & Kaempfer, R. (2016). Superantigens hyperinduce inflammatory cytokines by enhancing the B7-2/CD28 costimulatory receptor interaction. *Proceedings of the National Academy of Sciences of the United States of America, 113*(42), E6437–E6446. |
| DOI | https://doi.org/10.1073/pnas.1603321113 |

---

## Final Model



## Interpretation

### 1. What sender cell did you choose, and in what tissue or biological context does it act?

Sender cell: Dendritic cell. It acts mainly in peripheral tissues and is involved in immune responses, including inflammation and tissue repair.

### 2. What signaling molecule did you identify, and what evidence supports its production or presentation by the sender cell?

The signaling molecule  identified is CD86 (B7-2), which is encoded by the CD86 gene. The Human Protein Atlas and UniProt show CD86 expression in dendritic cells, supporting that dendritic cells can present CD86 as a membrane-associated signaling molecule.

### 3. What receptor receives the signal, and which receiver cell did you select?

The receptor  selected is CD28, which can receive the CD86 signal. The receiver cell is a T lymphocyte, particularly a CD4+ helper T cell or naïve T cell. CD28 is found on the surface of T cells and can interact with CD86.

### 4. What type of cell-to-cell signaling is represented: paracrine, endocrine, autocrine, or contact-dependent?

The signaling represented is contact-dependent or juxtacrine signaling. This is because CD86 is a membrane-associated molecule on the dendritic cell, so it needs to interact directly with a receptor on the surface of the T cell.

### 5. Which proteins in your STRING network appear most relevant to the receptor-associated response? Explain briefly.

The proteins that appear most relevant are CD4, CTLA4, IFNG, IL10, and CD40. CD4 is related to T-cell activation, while CTLA4 helps regulate T-cell responses. IFNG and IL10 are involved in immune responses, and CD40 is involved in immune-cell signaling. These proteins are therefore relevant to the immune response associated with CD86–CD28 signaling.

### 6. What enriched pathway or biological process is consistent with your proposed mechanism?

The enriched biological process was GO:2000516, positive regulation of CD4-positive, alpha-beta T cell activation. This fits the proposed mechanism because CD86–CD28 interaction provides a costimulatory signal that helps activate T cells during an immune response.

### 7. What did IntAct show for the molecular interaction you examined? What type of evidence was reported?

I examined the interaction between CD86 (B7-2) and CD28 in humans. IntAct linked this interaction to the study by Levy et al. (2016), with Publication ID 27708164. The experimental detection method reported was fluorescence-activated cell sorting (FACS). This provides experimental evidence related to the CD86–CD28 interaction, although the exact type of molecular interaction should be interpreted based on the information provided in the IntAct record.

### 8. Which parts of your final model are strongly supported, and which parts remain an inference?

The strongest-supported parts are that dendritic cells express CD86, CD86 can interact with CD28, and CD28 is associated with T cells. The STRING network also supports the involvement of proteins related to T-cell and immune responses. However, the exact order of the intracellular proteins in my final diagram is still an inference because STRING associations do not necessarily prove that the proteins directly interact or act one after another.

### 9. What cellular response is expected in the receiver cell, and why?

The expected response in the T cell is T-cell activation and regulation of the immune response. This is because the CD86–CD28 interaction provides a costimulatory signal, and the STRING analysis showed enrichment for positive regulation of CD4-positive, alpha-beta T-cell activation.

References and database links:

https://omnipathdb.org/

https://string-db.org/

https://www.ebi.ac.uk/intact/

https://www.proteinatlas.org/

https://www.uniprot.org/

https://europepmc.org/article/MED/27708164

https://www.ebi.ac.uk/intact/search?query=CD86%20CD28

https://string-db.org/cgi/network?taskId=bYy91UcF6mJ0&sessionId=b5YFCoglO65F
