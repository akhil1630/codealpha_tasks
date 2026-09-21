# CodeAlpha Bioinformatics Internship Tasks

This repository contains the completed tasks for the CodeAlpha Bioinformatics Internship.

## 👨‍🔬 Intern

**Name:** Akhilesh Savalgi  
**Domain:** Bioinformatics  
**Organization:** CodeAlpha

---

## 🧬 Task 1 — DNA/Protein Sequence Analysis Using BLAST

### Objective
To analyze a protein sequence using BLAST and identify homologous sequences based on sequence similarity.

### Protein Selected
- **Protein:** Hemoglobin subunit beta (HBB)
- **Organism:** Homo sapiens
- **UniProt Accession:** P68871
- **Sequence Length:** 147 amino acids

### Tools Used
- UniProt
- NCBI Protein BLAST

### Analysis
The HBB protein sequence was obtained from UniProt and submitted to NCBI Protein BLAST. The resulting homologous sequences were analyzed using query coverage, percentage identity, E-value, alignment score, positives and gaps.

### Main Result
The BLAST results showed significant similarity between the human HBB query and several globin proteins. The selected beta-globin hit showed:

- Query coverage: 100%
- Identity: 137/147 (93%)
- E-value: 2e-93
- Alignment score: 277 bits (708)
- Gaps: 0/147 (0%)

The complete report and screenshots are included in this repository.

---

## 🧬 Task 2 — Multiple Sequence Alignment

### Objective
To perform Multiple Sequence Alignment (MSA) of five homologous hemoglobin beta protein sequences and identify conserved regions.

### Protein Sequences Used

| Organism | UniProt Accession |
|---|---|
| Mouse | P02088 |
| Sheep | P02075 |
| Cow | P02070 |
| Human | P68871 |
| Dog | P60524 |

### Tool Used
- EMBL-EBI Clustal Omega

### Analysis
The five hemoglobin beta protein sequences were aligned using Clustal Omega. The alignment was examined for conserved residues and conserved sequence regions.

### Conserved Regions Observed

- `VKAHGKKV...`
- `...HCDKLHVDPENFRLLG...`
- `...VAGANALAHKYH`

The alignment also contains conservation symbols:

- `*` — identical residue
- `:` — strongly conserved substitution
- `.` — weaker similarity

The complete report and alignment screenshots are included in this repository.

---

## 📁 Repository Contents

### Task 1
- CodeAlpha Task 1 BLAST Report
- UniProt screenshot
- BLAST results screenshot
- Pairwise alignment screenshot

### Task 2
- CodeAlpha Task 2 MSA Report
- Clustal Omega alignment screenshots

---

## 🛠️ Bioinformatics Tools

- UniProt
- NCBI BLAST
- EMBL-EBI Clustal Omega

---

## 📌 Internship Status

Two required bioinformatics tasks have been completed:

1. DNA/Protein Sequence Analysis using BLAST
2. Multiple Sequence Alignment using Clustal Omega
