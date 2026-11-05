# Lysomal_enzyme

# Exploring Lysosomal Enzymes Using NCBI and R

## Cell and Molecular Biology Laboratory

**Name:** Maria Ryzah May I. Vertudazo 
**Section:** A  
**Selected Gene:** GBA1  
**Enzyme:** Lysosomal acid glucosylceramidase (Glucocerebrosidase)  
**Organism:** *Homo sapiens*

---

# 1. Protein Information

GBA1 is a lysosomal enzyme that cleaves glucosylceramide into glucose and ceramide, a reaction that supports lipid turnover and normal cellular function. Because the enzyme’s activity depends on its structure, which comes from its amino acid sequence, this laboratory activity analyzed the sequence of human GBA1 to learn more about the protein behind this reaction.

**Table 1. General Information and Biological Function of the Human GBA1 Enzyme**

| Required Information | GBA1 Enzyme |
|---|---|
| Gene name | GBA1 (glucosylceramidase beta 1) |
| Enzyme name | Lysosomal acid glucosylceramidase (glucocerebrosidase) |
| NCBI protein accession | NP_000148.2 |
| What it breaks down | Glucosylceramide (glucocerebroside) |
| Normal function | Breaks down glucosylceramide into glucose and ceramide inside lysosomes, supporting lipid degradation and cellular recycling. |

Table 1 summarizes the general information and biological function of human GBA1. This lysosomal enzyme catabolizes glucosylceramide, a glycolipid found in cell membranes, by cleaving it into glucose and ceramide. These products can then be reused in other cellular processes. By degrading glucosylceramide, GBA1 helps maintain normal lipid metabolism and prevents the abnormal buildup of complex lipids within cells.

**NCBI Protein Record:**  
https://www.ncbi.nlm.nih.gov/protein/NP_000148.2

---

# 2. Results and Interpretation

## 2.1. Protein Sequence Summary

The amino acid sequence of human lysosomal acid glucosylceramidase (GBA1) was retrieved from the NCBI Protein database using the RefSeq accession number NP_000148.2. The sequence was analyzed using R to determine its total length, amino acid composition, and potential N-glycosylation motifs.

**Table 2. Summary of the Human GBA1 Protein Sequence Analysis**

| Parameter | Result |
|---|---|
| Gene | GBA1 |
| NCBI protein accession | NP_000148.2 |
| Protein length | 536 amino acids |
| Potential N-glycosylation motifs | 5 |

Table 2. The GBA1 protein sequence analysis showed that the protein is 536 amino acids long and contains five potential N-glycosylation motifs. These motifs follow the N-X-S/T pattern, where X is any amino acid except proline, and they mark possible sites of N-linked glycosylation. However, sequence analysis alone cannot confirm that these sites are actually glycosylated

## 2.2. Amino Acid Composition

The amino acid composition of GBA1 was calculated from its protein sequence by counting each of the 20 standard amino acids and expressing each count as a percentage of the total 536 residues. This profile shows which residues are most and least abundant and provides a basis for interpreting the protein’s overall properties, such as hydrophobicity and charge.

**Table 3. Five Most Abundant Amino Acids in the Human GBA1 Protein**

| Amino Acid | Count | Percentage |
|---|---:|---:|
| Leucine (L) | 60 | 11.19% |
| Serine (S) | 44 | 8.21% |
| Alanine (A) | 42 | 7.84% |
| Glycine (G) | 37 | 6.90% |
| Proline (P) | 37 | 6.90% |

Table 3 presents the five most abundant amino acids in the human GBA1 protein. Leucine (L) was the most abundant, with 60 residues (11.19%), followed by serine (S), with 44 residues (8.21%). Alanine (A) accounted for 42 residues (7.84%), while glycine (G) and proline (P) each contained 37 residues (6.90%). These findings demonstrate that leucine is the most frequently occurring amino acid in the 536-residue GBA1 protein sequence.

**Figure 1. Amino Acid Composition of GBA1**

<img width="1590" height="875" alt="IMG_3189" src="https://github.com/user-attachments/assets/ce13d00d-7bfa-4e1e-9aee-fd10108074fb" />


Figure 1. Amino Acid Composition of the Human GBA1 Protein. The bar graph illustrates the distribution of the 20 standard amino acids in the 536-amino-acid sequence of human lysosomal acid glucosylceramidase (GBA1). The x-axis represents the amino acids using their one-letter codes, while the y-axis indicates the number of residues.

Figure 1 shows that leucine (L) had the highest frequency, with 60 residues (11.19%), followed by serine (S), with 44 residues (8.21%). Alanine (A) accounted for 42 residues (7.84%), while glycine (G) and proline (P) each contained 37 residues (6.90%). In contrast, cysteine (C) was among the least abundant amino acids, with only 8 residues (1.49%). The differences in bar heights illustrate the varying distribution of amino acids throughout the GBA1 protein sequence.

## 2.3. Identification of Potential N-Glycosylation Motifs

The GBA1 protein sequence was examined for potential N-glycosylation motifs using the N-X-S/T sequence pattern, where N represents asparagine, X represents any standard amino acid except proline, and S/T represents serine or threonine.

**Table 4. Potential N-Glycosylation Motifs Identified in the Human GBA1 Protein**

| Amino Acid Position | Motif |
|---:|---|
| 58 | NAT |
| 98 | NHT |
| 185 | NFS |
| 309 | NST |
| 501 | NRS |

Table 4 presents the positions and sequences of the five potential N-glycosylation motifs identified in the human GBA1 protein. The first motif was located at position 58 (NAT), while the last was detected at position 501 (NRS). All five identified sequences followed the N-X-S/T pattern. These findings indicate the presence of several possible sites for N-linked glycosylation distributed along the protein sequence.

**Figure 2. Potential N-Glycosylation Motifs in GBA1**

<img width="2360" height="1387" alt="IMG_3188" src="https://github.com/user-attachments/assets/db3bca0a-7c95-4407-9126-098c93120ab9" />


Figure 2. Distribution of Potential N-Glycosylation Motifs in the Human GBA1 Protein. The horizontal line represents the 536-amino-acid protein sequence, while the markers indicate the starting positions of the five potential N-glycosylation motifs.

Figure 2 illustrates the distribution of the five potential N-glycosylation motifs along the GBA1 protein sequence. The identified motifs were located at positions 58, 98, 185, 309, and 501. The earliest motif occurred at position 58, while the last was found at position 501. Their distribution indicates multiple potential sites for N-linked glycosylation throughout the protein. However, these motifs represent computational predictions and do not confirm actual glycan attachment. Furthermore, GBA1 differs from many other lysosomal enzymes because its transport to lysosomes depends on lysosomal integral membrane protein 2 (LIMP-2), rather than the conventional mannose-6-phosphate-dependent pathway.

---

# 3. Questions and Answers

### 1. What does your enzyme normally break down inside lysosomes?

Lysosomal acid glucosylceramidase (GBA1) breaks down glucosylceramide, also known as glucocerebroside, inside lysosomes. It catalyzes the hydrolysis of this glycolipid into glucose and ceramide. This process contributes to lipid degradation and the recycling of cellular components, particularly those derived from cell membranes (MedlinePlus Genetics, n.d.).

### 2. What is the total length of your protein, and which amino acids are most common?

Based on the sequence analysis, the human GBA1 protein (NP_000148.2) consists of 536 amino acids. Leucine (L) was the most abundant amino acid, with 60 residues (11.19%), followed by serine (S), with 44 residues (8.21%). Alanine (A) accounted for 42 residues (7.84%), while glycine (G) and proline (P) each contained 37 residues (6.90%). These results indicate that leucine is the most frequently occurring amino acid in the GBA1 protein sequence.

### 3. How many potential N-glycosylation motifs did you find? Where are they located?

The R sequence analysis identified five potential N-glycosylation motifs in the GBA1 protein sequence. These motifs were located at amino acid positions 58 (NAT), 98 (NHT), 185 (NFS), 309 (NST), and 501 (NRS). All identified sequences followed the N-X-S/T pattern, indicating possible sites for N-linked glycosylation. However, their presence does not establish whether glycosylation actually occurs at these positions.

### 4. Why can glycosylation matter for lysosomal proteins? Does finding a motif prove the protein is glycosylated?

Glycosylation contributes to proper protein folding, stability, and intracellular processing. In many lysosomal enzymes, N-linked glycans may also receive mannose-6-phosphate modifications that help direct them toward lysosomes. However, GBA1 is an exception because it is transported to lysosomes through its interaction with LIMP-2 rather than the conventional mannose-6-phosphate receptor pathway. Identifying an N-X-S/T motif does not prove that a protein is glycosylated, since the sequence only indicates a potential site for glycan attachment. Experimental evidence is required to confirm actual glycosylation (Ysselstein et al., 2021).

### 5. What could happen in the cell if your enzyme did not work properly?

If GBA1 does not function properly, glucosylceramide cannot be adequately degraded inside lysosomes, resulting in its abnormal accumulation within cells. This can interfere with normal lipid metabolism and cause cellular and tissue damage. Deficiency of glucocerebrosidase is associated with Gaucher disease, a lysosomal storage disorder that can affect the liver, spleen, bone marrow, and, in some forms, the nervous system. These effects demonstrate the importance of GBA1 in maintaining normal lysosomal function and cellular homeostasis (MedlinePlus Genetics, n.d.).

---

# 4. References

National Center for Biotechnology Information. (n.d.). *GBA1 glucosylceramidase beta 1 [Homo sapiens (human)]* (Gene ID: 2629). National Library of Medicine. https://www.ncbi.nlm.nih.gov/gene/2629

National Center for Biotechnology Information. (n.d.). *Lysosomal acid glucosylceramidase isoform 1 precursor [Homo sapiens]* (NP_000148.2). National Library of Medicine. https://www.ncbi.nlm.nih.gov/protein/NP_000148.2

MedlinePlus Genetics. (n.d.). *GBA1 gene*. U.S. National Library of Medicine. https://medlineplus.gov/genetics/gene/gba1/

Ysselstein, D., et al. (2021). *Evaluation of strategies for measuring lysosomal glucocerebrosidase activity*. Movement Disorders. 

