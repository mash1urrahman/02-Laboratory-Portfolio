# Protein & Enzyme Chemistry Laboratory

**Associated Courses:** BBT 314 (Protein & Enzyme Chemistry), BIO 201 (Introduction to Biochemistry and Biotechnology)  
**Institution:** Department of Biochemistry and Microbiology, North South University (NSU)

---

## 📑 Table of Contents
1. [Total Protein Estimation: Biuret Standard Curve & Semi-Automated Analyzer (BBT 314)](#1-total-protein-estimation-biuret-standard-curve--semi-automated-analyzer-bbt-314)
2. [Kinetic Determination of Serum ALT (GPT) and AST (GOT) Activity (BBT 314)](#2-kinetic-determination-of-serum-alt-gpt-and-ast-got-activity-bbt-314)
3. [Isoelectric Precipitation of Milk Casein & SDS-PAGE Separation (BBT 314)](#3-isoelectric-precipitation-of-milk-casein--sds-page-separation-bbt-314)
4. [Foundational & Clinical Biochemistry Assays (BIO 201)](#4-foundational--clinical-biochemistry-assays-bio-201)

---

## 1. Total Protein Estimation: Biuret Standard Curve & Semi-Automated Analyzer (BBT 314)

![BBT 314: Protein & Enzyme Chemistry Laboratory](BBT314%20-%20Protein%20%26%20Enzyme%20Chemistry%20Laboratory.jpg)

### Aim & Principle
* **Objectives:** Quantify an unknown protein sample using a Bovine Serum Albumin (BSA) standard curve and measure human serum total protein on a semi-automated biochemistry analyzer.
* **Principle:** In a strongly alkaline medium ($\text{NaOH}$), cupric ions ($\text{Cu}^{2+}$) form a violet coordination complex with peptide bond nitrogen atoms (requiring $\ge 2$ peptide bonds). Potassium sodium tartrate stabilizes $\text{Cu}^{2+}$, and potassium iodide prevents autoreduction. Absorbance at $540–550\ \text{nm}$ follows the Beer–Lambert Law ($A = \varepsilon c l$).

### Part A: Biuret Standard Curve Protocol ($10\ \text{mg/mL}$ BSA Stock)

| Tube | BSA Stock ($10\ \text{mg/mL}$) | Distilled Water | Final Protein ($\text{mg/tube}$) | Biuret Reagent |
| :--- | :--- | :--- | :--- | :--- |
| **Blank** | $0.0\ \text{mL}$ | $1.0\ \text{mL}$ | $0.0\ \text{mg}$ | $3.0\ \text{mL}$ |
| **S1** | $0.2\ \text{mL}$ | $0.8\ \text{mL}$ | $2.0\ \text{mg}$ | $3.0\ \text{mL}$ |
| **S2** | $0.4\ \text{mL}$ | $0.6\ \text{mL}$ | $4.0\ \text{mg}$ | $3.0\ \text{mL}$ |
| **S3** | $0.6\ \text{mL}$ | $0.4\ \text{mL}$ | $6.0\ \text{mg}$ | $3.0\ \text{mL}$ |
| **S4** | $0.8\ \text{mL}$ | $0.2\ \text{mL}$ | $8.0\ \text{mg}$ | $3.0\ \text{mL}$ |
| **S5** | $1.0\ \text{mL}$ | $0.0\ \text{mL}$ | $10.0\ \text{mg}$ | $3.0\ \text{mL}$ |
| **Unknown** | $1.0\ \text{mL}$ sample | $0.0\ \text{mL}$ | Unknown | $3.0\ \text{mL}$ |

* **Incubation & Reading:** Vortex thoroughly, incubate at $37^\circ\text{C}$ for $15\ \text{min}$ (or room temperature for $30\ \text{min}$), zero with Blank at $540\ \text{nm}$, and record $A_{540}$.

### Part B: Clinical Serum Total Protein (Semi-Automated Biochemistry Analyzer)
* **Protocol:** Mix $1000\ \mu\text{L}$ Biuret working reagent with $20\ \mu\text{L}$ Blank ($\text{H}_2\text{O}$), Standard ($6.0\ \text{g/dL}$ calibrator), or non-hemolyzed serum $\rightarrow$ incubate at $37^\circ\text{C}$ for $10\ \text{min}$ $\rightarrow$ aspirate in endpoint mode at $546\ \text{nm}$.
* **Calculation & Clinical Reference:**
  $$\text{Total Serum Protein (g/dL)} = \frac{A_{\text{Test}}}{A_{\text{Standard}}} \times \text{Concentration of Standard (g/dL)}$$
  * **Adult Reference Range:** $6.0 – 8.3\ \text{g/dL}$ ($<6.0\ \text{g/dL}$: nephrotic syndrome/hepatic cirrhosis; $>8.3\ \text{g/dL}$: dehydration/multiple myeloma).
* **Troubleshooting:** Clear lipemic turbidity via high-speed centrifugation; avoid hemolyzed samples (intracellular hemoglobin falsely elevates $A_{540}$).

---

## 2. Kinetic Determination of Serum ALT (GPT) and AST (GOT) Activity (BBT 314)

### Principle (Continuous UV-Kinetic Method at $340\ \text{nm}$)
Coupled enzymatic reactions monitor the oxidation of $\text{NADH}$ (strong absorbance at $340\ \text{nm}$) to $\text{NAD}^+$ (no absorbance at $340\ \text{nm}$):
* **ALT (Exp 2A):**
  $$\text{L-Alanine} + \alpha\text{-Ketoglutarate} \xrightarrow{\text{ALT}} \text{Pyruvate} + \text{L-Glutamate}$$
  $$\text{Pyruvate} + \text{NADH} + \text{H}^+ \xrightarrow{\text{LDH}} \text{L-Lactate} + \text{NAD}^+$$
* **AST (Exp 2B):**
  $$\text{L-Aspartate} + \alpha\text{-Ketoglutarate} \xrightarrow{\text{AST}} \text{Oxaloacetate} + \text{L-Glutamate}$$
  $$\text{Oxaloacetate} + \text{NADH} + \text{H}^+ \xrightarrow{\text{MDH}} \text{L-Malate} + \text{NAD}^+$$

### Protocol, Calculation & Reference Ranges
1. **Assay Setup:** Mix $1000\ \mu\text{L}$ pre-warmed ($37^\circ\text{C}$) working reagent ($R_1 + R_2$) with $100\ \mu\text{L}$ fresh, non-hemolyzed serum.
2. **Kinetic Measurement:** Aspirate into bioanalyzer ($340\ \text{nm}$, $37^\circ\text{C}$, $1\ \text{cm}$ path), allow a $60\text{-sec}$ lag phase, and record absorbance every $60\ \text{sec}$ for $3\ \text{min}$ to determine mean $\Delta A_{340}/\text{min}$.
3. **Activity Formula & Reference Ranges ($37^\circ\text{C}$):**
   $$\text{Activity (U/L)} = \frac{\Delta A_{340}}{\text{min}} \times \frac{V_{\text{total}} \times 1000}{\varepsilon_{340} \times l \times V_{\text{sample}}} = \frac{\Delta A_{340}}{\text{min}} \times 1746$$
   * **Normal Ranges:** ALT: $7 – 40\ \text{U/L}$ | AST: $8 – 40\ \text{U/L}$.
   * **Troubleshooting:** Dilute serum $1:10$ in $0.9\%$ saline if $\Delta A/\text{min} > 0.25$ (substrate exhaustion); reject hemolyzed samples (RBCs contain high endogenous AST).

---

## 3. Isoelectric Precipitation of Milk Casein & SDS-PAGE Separation (BBT 314)

### Part A: Isoelectric Precipitation of Casein (Exp 3)
* **Principle:** At its isoelectric point ($\text{pI} = 4.6$), casein carries zero net charge, eliminating electrostatic repulsion and triggering precipitation while whey proteins ($\beta$-lactoglobulin, $\alpha$-lactalbumin) remain soluble.
* **Workflow:** Warm $20\ \text{mL}$ skim milk to $40^\circ\text{C}$ $\rightarrow$ titrate dropwise with $10\%$ acetic acid to $\text{pH } 4.6$ $\rightarrow$ filter curds, defat with ethanol/ether, dry, and calculate percentage yield (typically $2.5–3.2\ \text{g}/100\ \text{mL}$).

### Part B: SDS-PAGE Protein Separation (Exp 4)
* **Principle:** SDS denatures proteins and imparts a uniform negative charge-to-mass ratio ($\sim 1.4\ \text{g SDS/g protein}$), while $\beta$-mercaptoethanol reduces disulfide bonds. Discontinuous polyacrylamide gels (stacking gel $\text{pH } 6.8$, resolving gel $\text{pH } 8.8$) separate polypeptides strictly by molecular weight ($\text{kDa}$).
* **Workflow:** Mix protein sample $1:1$ with $2\times$ Laemmli buffer $\rightarrow$ boil at $95^\circ\text{C}$ for $5\ \text{min}$ $\rightarrow$ electrophorese alongside pre-stained protein ladder ($100\ \text{V}$ stacking, $150\ \text{V}$ on $12\%$ resolving gel) $\rightarrow$ stain with Coomassie Brilliant Blue R-250 and destain (casein subunits resolve at $\sim 24–35\ \text{kDa}$).

---

## 4. Foundational & Clinical Biochemistry Assays (BIO 201)

![BIO 201: Introduction to Biochemistry & Biotechnology Lab](Bio201%20-Introduction%20to%20Biochemistry%20%26%20Biotechnology%20Lab.jpg)

### Experiment 1: Precision Micropipetting & Gravimetric Calibration (P10, P100, P1000)

| Micropipette Model | Valid Volume Range | Display Digit Format (Top $\rightarrow$ Bottom) | Example Reading |
| :--- | :--- | :--- | :--- |
| **P10** | $0.5 – 10.0\ \mu\text{L}$ | Tens $\cdot$ Ones $\cdot$ Tenths (red) | `0 - 7 - 5` = $7.5\ \mu\text{L}$ |
| **P100** | $10 – 100\ \mu\text{L}$ | Hundreds $\cdot$ Tens $\cdot$ Ones | `0 - 6 - 5` = $65.0\ \mu\text{L}$ |
| **P1000** | $100 – 1000\ \mu\text{L}$ | Thousands (red) $\cdot$ Hundreds $\cdot$ Tens | `0 - 7 - 5` = $750\ \mu\text{L}$ |

* Verified pipetting accuracy gravimetrically on an analytical balance ($1.0\ \mu\text{L H}_2\text{O} = 1.0\ \text{mg}$ at $20^\circ\text{C}$; acceptable error $\le 1–2\%$).

### Experiment 2: Qualitative Yeast Enzyme Activity (*Saccharomyces cerevisiae*)
* Evaluated yeast **invertase** (hydrolyzes sucrose into reducing sugars detected via Benedict's brick-red $\text{Cu}_2\text{O}$ precipitate) and **catalase** ($\text{H}_2\text{O}_2 \rightarrow \text{H}_2\text{O} + \text{O}_2$) across four conditions: native ($37^\circ\text{C}$, $\text{pH } 5.0$ — rapid hydrolysis), boiled ($100^\circ\text{C}$ — thermal denaturation), ice-cold ($4^\circ\text{C}$ — reduced kinetic rate), and extreme $\text{pH}$ ($\text{HCl}/\text{NaOH}$ — active-site disruption).

### Experiment 3: Separation of Human Plasma and Serum from Whole Blood

| Feature | Plasma | Serum |
| :--- | :--- | :--- |
| **Collection Tube** | Anticoagulant tube (EDTA, Heparin, or Citrate) | Plain clot-activator tube (no anticoagulant) |
| **Pre-Centrifugation** | Invert gently $8–10\times$; centrifuge immediately | Allow blood to clot undisturbed ($20–30\ \text{min}$, RT) |
| **Centrifugation** | $1500–2000 \times g$ for $10\ \text{min}$ | $1500–2000 \times g$ for $10\ \text{min}$ |
| **Composition** | Retains fibrinogen and clotting factors | Lacks fibrinogen and clotting factors (consumed in clot) |
| **Layers Formed** | Top: Plasma ($\sim 55\%$) $\cdot$ Middle: Buffy coat $\cdot$ Bottom: RBCs | Top: Clear yellow serum $\cdot$ Bottom: Retracted fibrin/RBC clot |

### Experiment 4: Enzymatic Estimation of Serum Glucose (GOD–POD Trinder Method)
* **Principle:** Glucose Oxidase (GOD) oxidizes $\beta$-D-glucose to gluconic acid and $\text{H}_2\text{O}_2$; Peroxidase (POD) couples $\text{H}_2\text{O}_2$ with $4\text{-aminoantipyrine}$ and phenol to form a quinoneimine dye measured at $505\ \text{nm}$.
* **Protocol & Formula:** Incubate $1000\ \mu\text{L}$ GOD–POD reagent + $10\ \mu\text{L}$ serum (or $100\ \text{mg/dL}$ standard) at $37^\circ\text{C}$ for $10\ \text{min}$ and measure $A_{505}$:
  $$\text{Serum Glucose (mg/dL)} = \frac{A_{\text{Test}}}{A_{\text{Standard}}} \times 100\ \text{mg/dL}$$
  * **Clinical Thresholds:** Fasting Normal: $70–99\ \text{mg/dL}$ | Prediabetes: $100–125\ \text{mg/dL}$ | Diabetes Mellitus: $\ge 126\ \text{mg/dL}$.
