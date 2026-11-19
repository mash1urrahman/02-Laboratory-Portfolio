# Molecular Biology & Biotechnology Laboratory

**Associated Courses:** BBT 312 (Molecular Biology), BBT 413 (Plant Biochemistry & Biotechnology), BBT 415 (Molecular Biotechnology)  
**Institution:** Department of Biochemistry and Microbiology, North South University (NSU)

---

## 📑 Table of Contents
1. [Bacterial Genomic DNA Isolation, Quantification & Purity Determination (BBT 312)](#1-bacterial-genomic-dna-isolation-quantification--purity-determination-bbt-312)
2. [Restriction Digestion & Fragment Mapping of Lambda ($\lambda$) DNA (BBT 312)](#2-restriction-digestion--fragment-mapping-of-lambda-lambda-dna-bbt-312)
3. [Plant Genomic DNA (CTAB) & Total RNA (TRIzol) Extraction (BBT 413)](#3-plant-genomic-dna-ctab--total-rna-trizol-extraction-bbt-413)
4. [Plasmid Isolation (pBR322 / pGLO) & Bacterial Transformation (BBT 415)](#4-plasmid-isolation-pbr322--pglo--bacterial-transformation-bbt-415)
5. [Fungal Genomic DNA Extraction & ITS PCR Amplification (BBT 415)](#5-fungal-genomic-dna-extraction--its-pcr-amplification-bbt-415)

---

## 1. Bacterial Genomic DNA Isolation, Quantification & Purity Determination (BBT 312)

![BBT 312: Molecular Biology Laboratory Workflow](BBT312%20-%20Molecular%20Biology%20Laboratory%20Workflow.jpg)

### Aim & Objectives
* Isolate high-molecular-weight genomic DNA from overnight *Escherichia coli* culture free of proteins, RNA, and cellular debris for downstream PCR and restriction digestion.
* Quantify dsDNA concentration and assess purity via UV-Vis spectrophotometry ($A_{260}/A_{280}$ and $A_{260}/A_{230}$ ratios).

### Principle
Cells are lysed using SDS (solubilizes lipid membranes and denatures proteins) and Proteinase K (digests cellular proteins and nucleases), while EDTA chelates divalent cations ($\text{Mg}^{2+}$, $\text{Ca}^{2+}$) to inhibit endogenous DNases. Following RNase A digestion and high-salt/organic protein precipitation, nucleic acids are selectively precipitated from the aqueous phase using ice-cold ethanol or isopropanol.

### Protocol Summary
1. **Cell Harvesting:** Pellet $1.5\ \text{mL}$ overnight *E. coli* culture at $10,000 \times g$ for 2 min.
2. **Lysis:** Resuspend pellet in $500\ \mu\text{L}$ TE buffer ($10\ \text{mM}$ Tris-HCl, $1\ \text{mM}$ EDTA, pH 8.0), add $30\ \mu\text{L}$ 10% SDS and $5\ \mu\text{L}$ Proteinase K ($20\ \text{mg/mL}$), and incubate at $56^\circ\text{C}$ for 1 hr.
3. **RNA Removal:** Add $5\ \mu\text{L}$ RNase A ($10\ \text{mg/mL}$) and incubate at $37^\circ\text{C}$ for 15–20 min.
4. **Protein Precipitation:** Add $200\ \mu\text{L}$ of $5\ \text{M}$ NaCl (or equal volume phenol:chloroform:isoamyl alcohol 25:24:1) and centrifuge at $12,000 \times g$ for 10 min at $4^\circ\text{C}$.
5. **DNA Precipitation & Washing:** Precipitate aqueous phase with $2\times$ volumes ice-cold 100% ethanol ($-20^\circ\text{C}$, 20 min), pellet at $12,000 \times g$, wash with $500\ \mu\text{L}$ 70% ethanol, air-dry, and rehydrate in $50\ \mu\text{L}$ TE buffer.

### Quantification & Quality Thresholds
$$\text{dsDNA Concentration } (\mu\text{g/mL}) = A_{260} \times 50 \times \text{Dilution Factor}$$

| Parameter | Target / Ideal Value | Analytical Interpretation |
| :--- | :--- | :--- |
| **$A_{260}/A_{280}$ Ratio** | **1.80 – 2.00** | Pure dsDNA ($<1.8$: protein/phenol carryover; $>2.0$: residual RNA) |
| **$A_{260}/A_{230}$ Ratio** | **2.00 – 2.20** | Free of salts, carbohydrates, or chaotropic agents ($<2.0$: salt/ethanol carryover) |

### Troubleshooting Notes
* **Low Yield:** Incomplete resuspension prior to SDS lysis or accidental aspiration of pellet during ethanol decanting.
* **Sheared DNA Smear:** Vigorous vortexing post-lysis; genomic DNA must be mixed strictly by gentle tube inversion.

---

## 2. Restriction Digestion & Fragment Mapping of Lambda ($\lambda$) DNA (BBT 312)

### Principle & Objectives
Type II restriction endonucleases (*EcoRI*, *HindIII*) cleave palindromic dsDNA sequences in the presence of $\text{Mg}^{2+}$. During agarose gel electrophoresis, negatively charged DNA fragments migrate toward the anode inversely proportional to $\log_{10}(\text{bp})$, enabling fragment sizing against a $1\ \text{kb}$ DNA ladder and verification of the linear $\lambda$ DNA ($48,502\ \text{bp}$) restriction map.

### Reaction Setup ($20\ \mu\text{L}$ Total Volume, Prepared on Ice)

| Component | Tube 1 (Uncut Control) | Tube 2 (*EcoRI*) | Tube 3 (*HindIII*) | Tube 4 (*EcoRI* + *HindIII*) |
| :--- | :--- | :--- | :--- | :--- |
| **Nuclease-Free $\text{H}_2\text{O}$** | $16.0\ \mu\text{L}$ | $15.0\ \mu\text{L}$ | $15.0\ \mu\text{L}$ | $14.0\ \mu\text{L}$ |
| **$10\times$ Reaction Buffer** | $2.0\ \mu\text{L}$ | $2.0\ \mu\text{L}$ | $2.0\ \mu\text{L}$ | $2.0\ \mu\text{L}$ |
| **$\lambda$ DNA ($0.5\ \mu\text{g}/\mu\text{L}$)** | $2.0\ \mu\text{L}$ | $2.0\ \mu\text{L}$ | $2.0\ \mu\text{L}$ | $2.0\ \mu\text{L}$ |
| ***EcoRI* ($10\ \text{U}/\mu\text{L}$)** | — | $1.0\ \mu\text{L}$ | — | $1.0\ \mu\text{L}$ |
| ***HindIII* ($10\ \text{U}/\mu\text{L}$)** | — | — | $1.0\ \mu\text{L}$ | $1.0\ \mu\text{L}$ |

* **Incubation & Resolution:** Incubate at $37^\circ\text{C}$ for 1 hr, heat-inactivate at $65^\circ\text{C}$ for 10 min (to dissociate annealed 12-nt *cos* cohesive ends), chill on ice, and resolve on a $0.8\%$ agarose gel ($1\times$ TAE, $80–100\ \text{V}$).
* **Expected Fragment Profiles:**
  * *EcoRI* (6 fragments): $21,226$; $7,421$; $5,804$; $5,643$; $4,878$; $3,530\ \text{bp}$.
  * *HindIII* (8 fragments): $23,130$; $9,416$; $6,557$; $4,361$; $2,322$; $2,027$; $564$; $125\ \text{bp}$.
* **Troubleshooting:** Prevent extra $\sim 27.5\ \text{kb}$ *cos*-annealed bands in *HindIII* digests by heating at $65^\circ\text{C}$ immediately before loading; prevent star activity by keeping enzyme glycerol volume $\le 10\%$ of total reaction volume.

---

## 3. Plant Genomic DNA (CTAB) & Total RNA (TRIzol) Extraction (BBT 413)

![BBT 413: Plant Biochemistry & Biotechnology Lab](BBT413%20-%20Plant%20Biochemistry%20%26%20Biotechnology%20Lab.jpg)

### Part A: Plant Genomic DNA Isolation (CTAB Method)
* **Principle:** Cationic detergent CTAB solubilizes plant membranes and forms soluble complexes with DNA at high salt ($>0.7\ \text{M}$ NaCl), while insoluble polysaccharides and polyphenols are removed via chloroform:isoamyl alcohol (24:1) extraction in the presence of PVP and $\beta$-mercaptoethanol.
* **Workflow:** Grind $100–200\ \text{mg}$ leaf tissue $\rightarrow$ lyse in $700\ \mu\text{L}$ pre-warmed ($65^\circ\text{C}$) $2\times$ CTAB buffer ($2\%$ CTAB, $100\ \text{mM}$ Tris-HCl pH 8.0, $20\ \text{mM}$ EDTA, $1.4\ \text{M}$ NaCl, $1\%$ PVP, $0.2\%$ $\beta$-ME) for 30–45 min $\rightarrow$ extract with equal volume chloroform:isoamyl alcohol (24:1) $\rightarrow$ treat aqueous phase with RNase A ($37^\circ\text{C}$, 20 min) $\rightarrow$ precipitate with $0.7\times$ ice-cold isopropanol, wash twice with 70% ethanol, and elute in TE buffer.

### Part B: Plant Total RNA Isolation (TRIzol Method — Strict RNase-Free)
* **Principle:** Monophasic phenol–guanidinium isothiocyanate rapidly lyses cells and denatures endogenous RNases; chloroform phase separation partitions RNA exclusively into the acidic upper aqueous phase ($\text{pH} \sim 4.5$).
* **Workflow:** Homogenize $50–100\ \text{mg}$ leaf tissue in $1.0\ \text{mL}$ TRIzol $\rightarrow$ phase-separate with $200\ \mu\text{L}$ chloroform ($12,000 \times g$, 15 min, $4^\circ\text{C}$) $\rightarrow$ precipitate top 70% aqueous phase with $500\ \mu\text{L}$ isopropanol $\rightarrow$ wash pellet with $1.0\ \text{mL}$ 75% ethanol (DEPC-treated) $\rightarrow$ dissolve in RNase-free water and store at $-80^\circ\text{C}$.
* **Quality Verification:** Pure plant RNA yields $A_{260}/A_{280} \approx 1.90–2.10$ and $A_{260}/A_{230} > 2.00$, displaying distinct 28S and 18S rRNA bands (plus chloroplast 23S/16S rRNA bands) on agarose gel electrophoresis.

---

## 4. Plasmid Isolation (pBR322 / pGLO) & Bacterial Transformation (BBT 415)

![BBT 415: Molecular Biotechnology Laboratory](BBT415%20-%20Molecular%20Biotechnology%20Laboratory.jpg)

### Principle & Workflow
* **Alkaline Lysis Plasmid Extraction:** Lysis of *E. coli* with SDS/NaOH ($\text{pH } 12.0–12.5$) followed by acidic potassium acetate ($\text{pH } 5.2$) neutralization precipitates high-molecular-weight chromosomal DNA while supercoiled **pBR322** ($\text{Amp}^R/\text{Tet}^R$) or **pGLO** ($\text{bla}/\text{Amp}^R$, *araC*, *GFP*) remains soluble.
* **Heat-Shock Transformation:** Incubate $50\ \mu\text{L}$ chemically competent ($\text{CaCl}_2$-treated) *E. coli* with $10–50\ \text{ng}$ plasmid on ice (20–30 min) $\rightarrow$ heat-shock at $42^\circ\text{C}$ for exactly **45 sec** $\rightarrow$ chill on ice (2 min) $\rightarrow$ recover in $250\ \mu\text{L}$ LB/SOC broth ($37^\circ\text{C}$, 45–60 min) $\rightarrow$ plate on selective media (LB + Amp; LB + Amp + Arabinose for $P_{\text{BAD}}$-regulated GFP UV fluorescence).
* **Transformation Efficiency:**
  $$\text{Transformation Efficiency (CFU}/\mu\text{g)} = \frac{\text{Number of Colonies on Selective Plate}}{\mu\text{g of Plasmid DNA Plated}}$$

---

## 5. Fungal Genomic DNA Extraction & ITS PCR Amplification (BBT 415)

### Principle
Chitin-rich mycelia of mosquito-killing entomopathogenic fungi (*Fungus 2* and *Fungus 3*) were mechanically disrupted for genomic DNA extraction. Universal primers **ITS1** and **ITS4** flank conserved 18S and 28S rRNA genes to amplify the hypervariable nuclear ribosomal **ITS1–5.8S–ITS2** barcode region for species-level identification.

### PCR Setup ($25\ \mu\text{L}$) & Thermal Cycling Profile

| Component | Volume | Final Conc. | Thermal Cycling Step | Temp & Duration | Cycles |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **$2\times$ Taq PCR Master Mix** | $12.5\ \mu\text{L}$ | $1\times$ | **Initial Denaturation** | $95^\circ\text{C}$, 3–5 min | $1\times$ |
| **Forward Primer (ITS1)** | $1.0\ \mu\text{L}$ | $0.4\ \mu\text{M}$ | **Denaturation** | $95^\circ\text{C}$, 30 sec | $35\times$ |
| **Reverse Primer (ITS4)** | $1.0\ \mu\text{L}$ | $0.4\ \mu\text{M}$ | **Annealing** | $55^\circ\text{C}$, 30 sec | $35\times$ |
| **Fungal gDNA Template** | $2.0\ \mu\text{L}$ | $20–50\ \text{ng}$ | **Extension** | $72^\circ\text{C}$, 1 min | $35\times$ |
| **Nuclease-Free Water** | $8.5\ \mu\text{L}$ | — | **Final Extension / Hold** | $72^\circ\text{C}$, 7 min $\rightarrow 4^\circ\text{C}$ | $1\times$ |

* **Expected Results & Troubleshooting:** $1.5\%$ agarose gel electrophoresis resolves a single sharp amplicon at **$500–750\ \text{bp}$** with a clean No-Template Control (NTC). If fungal polysaccharides/melanin inhibit amplification, dilute template DNA $1:10$ in nuclease-free water.
