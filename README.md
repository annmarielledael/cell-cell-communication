# Cell-to-Cell Communication: Pituitary Corticotroph to Adrenal Cortex

## Biological Question: 
- How does a pituitary corticotroph communicate with an adrenal cortex cell through ACTH-MC2R signaling to promote glucocorticoid production?

## Chosen Sender Cell and Biological Context

**Sender cell:** Pituitary corticotroph
**Tissue/context:** Anterior pituitary
**Biological context:** Neuroendocrine signaling

Human Protein Atlas (HPA) single-cell data show that POMC is enriched in pituitary corticotrophs, supporting the corticotroph as a biologically meaningful sender cell.

## Candidate Ligand and Evidence for Sender-Cell Expression

**Signaling molecule:** Adrenocorticotropic hormone (ACTH)
**Precursor:** Proopiomelanocortin (POMC)

HPA single-cell data show that POMC is cell-type enriched in pituitary corticotrophs. POMC is processed into peptides including ACTH, which serves as the signaling molecule in this proposed communication model.

## Receptor and Receiver Cell

**Receptor:** MC2R (Melanocortin 2 receptor)
**Receiver cell:** Adrenal cortex cell

HPA single-cell data show that MC2R is cell-type enriched in adrenal cortex cells and is predicted to be membrane-localized. This supports the adrenal cortex cell as a biologically reasonable receiver for the ACTH signal.

## Type of Cell-to-Cell Signaling

**Signaling type:** Endocrine

ACTH is released by pituitary corticotrophs and transported through the circulation to the adrenal cortex, where it acts on MC2R.

## OmniPath Findings

OmniPath identified a POMC → MC2R interaction supported by multiple signaling resources and 11 references. This supports a POMC/MC2R signaling relationship. Because POMC is a precursor that is processed into ACTH, the OmniPath result is interpreted as supporting the POMC-derived ACTH–MC2R signaling system rather than proving that intact POMC is the signaling ligand.

## STRING Network Interpretation

The STRING network centered on MC2R contained 11 proteins. Relevant proteins and pathway components included GNAS, CYP11A1, CYP21A2, and CYP11B1.

The network was significantly enriched for the biological process "glucocorticoid biosynthetic process" (FDR = 4.59 × 10⁻¹⁰). This is consistent with the proposed adrenal cortex response to ACTH signaling.

The STRING network supports functional associations among these proteins, but the exact order and direction of the intracellular interactions are treated as an inference rather than direct proof from STRING.

## IntAct Validation

The IntAct record examined was the MRAP–MC2R interaction.

The interaction was reported as a physical association and was detected using anti-tag co-immunoprecipitation (anti tag coIP). The interacting proteins are from *Homo sapiens*, while the host organism listed for the experiment was *Cricetulus griseus* (Chinese hamster).

Publication: **PMID 18077336**
DOI: **10.1073/pnas.0708916105**

This result provides experimental evidence for a physical association between MRAP and MC2R. It supports the receptor-associated molecular system but does not identify MRAP as the signaling ligand.

## Final Model

![Final cell-to-cell communication model](figures/06_final_model.png)

### Interpretation

The proposed communication model begins with a Pituitary corticotroph as the sender cell. HPA single-cell data show that POMC is enriched in corticotrophs, supporting the corticotroph as a biologically meaningful source of the precursor. POMC is processed to produce ACTH, the signaling peptide that acts on the adrenal cortex. OmniPath reports a POMC–MC2R interaction supported by multiple resources, while HPA data show that MC2R is enriched in adrenal cortex cells and is predicted to be membrane-localized. These findings support the adrenal cortex as a reasonable receiver. The communication is interpreted as endocrine because ACTH is released from the pituitary and transported through the circulation to the adrenal gland. The STRING network centered on MC2R contains 11 proteins and is significantly enriched for the glucocorticoid biosynthetic process (FDR 4.59 × 10⁻¹⁰). GNAS and steroidogenic proteins including CYP11A1, CYP21A2, and CYP11B1 were therefore included as relevant pathway components. IntAct provides experimental evidence for a physical association between MC2R and MRAP using anti-tag co-immunoprecipitation. The sender, receptor, receiver, and major signaling relationship are strongly supported by database evidence; however, the exact ordering of intracellular proteins remains an evidence-based inference rather than proof from STRING alone.

## Questions:

### 1. What sender cell did you choose, and in what tissue or biological context does it act?

- The sender cell is the Pituitary corticotroph, located in the anterior pituitary and involved in neuroendocrine signaling.

### 2. What signaling molecule did you identify, and what evidence supports its production or presentation by the sender cell?

- The signaling molecule is ACTH. HPA data show that POMC, the precursor of ACTH, is enriched in pituitary corticotrophs. POMC is processed to produce ACTH.

### 3. What receptor receives the signal, and which receiver cell did you select?

- The receptor is MC2R (Melanocortin 2 receptor), and the receiver cell is an adrenal cortex cell. HPA data show MC2R enrichment in adrenal cortex cells.

### 4. What type of cell-to-cell signaling is represented?

- The signaling is endocrine because ACTH is transported through the circulation from the pituitary to the adrenal cortex.

### 5. Which proteins in your STRING network appear most relevant to the receptor-associated response?

- GNAS, CYP11A1, CYP21A2, and CYP11B1 were selected as relevant pathway components because they are associated with the MC2R-centered network and steroidogenic processes.

### 6. What enriched pathway or biological process is consistent with your proposed mechanism?

- The most relevant enriched process was glucocorticoid biosynthetic process, with an FDR of 4.59 × 10⁻¹⁰.

### 7. What did IntAct show for the molecular interaction you examined?

- IntAct showed a positive physical association between MRAP and MC2R detected using anti-tag co-immunoprecipitation. The human proteins were studied using a Chinese hamster host system. The associated publication is PMID 18077336.

### 8. Which parts of your final model are strongly supported, and which parts remain an inference?

- The sender-cell POMC evidence, MC2R expression in adrenal cortex cells, the OmniPath POMC–MC2R relationship, STRING enrichment, and the IntAct MRAP–MC2R interaction are supported by database evidence. The exact ordering of intracellular proteins in the final model remains an inference.

### 9. What cellular response is expected in the receiver cell, and why?

- The expected response is increased glucocorticoid/cortisol production in the adrenal cortex. This is consistent with the MC2R-centered STRING network and its strong enrichment for glucocorticoid biosynthetic processes.

## References and Database Links

- Human Protein Atlas - POMC: https: //www.proteinatlas.org/ENSG00000115138-POMC 
- Human Protein Atlas - MC2R: https://www.proteinatlas.org/ENSG00000143801-MC2R
- OmniPath Explorer: https://explore.omnipathdb.org/
- STRING: https://string-db.org/
- IntAct: https://www.ebi.ac.uk/intact/
- PubMed - Publication 18077336: https://pubmed.ncbi.nlm.nih.gov/18077336/. DOI: https://doi.org/10.1073/pnas.0708916105
