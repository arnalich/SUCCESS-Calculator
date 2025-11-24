# SUCCESS Calculator  
**Validation and Extension of the SUCCESS Score for Fuchs Dystrophy After Cataract Surgery**  
**Short Title:** SUCCESS Score Validation in Fuchs Dystrophy

---

## 🔍 Description
The **SUCCESS Calculator** is an interactive web-based tool implementing both the **original** and **extended SUCCESS Scores**, developed to predict the likelihood of requiring **endothelial keratoplasty (EK)** after **cataract surgery** in patients with **Fuchs endothelial corneal dystrophy (FECD)**.

This calculator reproduces the risk estimation models described in the multicenter study currently under review at *JAMA Ophthalmology*. It provides objective, Scheimpflug-based predictions to assist ophthalmologists in preoperative planning and patient counseling.

---

## 🧮 How to Use
1. Enter the following **preoperative Pentacam parameters**:

   - **Central corneal thickness (µm)** measured **at the pupil center**.  
   - **Tomographic features of subclinical edema**, each evaluated as *present* or *absent* according to **Sun et al., 2018** ([Ophthalmology, 125(11):1706–1717](https://doi.org/10.1016/j.ophtha.2018.05.022)):  
     - Loss of regular isopachs  
     - Displacement of the thinnest point  
     - Focal posterior surface depression  
     (The calculator automatically sums these as 0–3 features.)  
   - **Maximum mean corneal densitometry** within the central 3-mm zone (gray-scale units, GSU).

2. The calculator outputs:
   - The **predicted probability (%)** of requiring endothelial keratoplasty (EK).  
   - The **risk category** (very low, low, intermediate, or high).

Interpret the results within the context of **routine, uncomplicated cataract surgery**.

---

## ⚙️ Model Details
- **Base SUCCESS Score:**  
  Combines central corneal thickness and Scheimpflug tomographic features of subclinical edema.

- **Extended SUCCESS Score:**  
  Adds the maximum mean corneal densitometry (≥21.2 GSU) within the central 3-mm zone.  
  This variable contributes **4 additional points** to the total score, enhancing model discrimination and calibration.

- **Validation Study:**  
  Prospective multicenter national cohort across five tertiary centers in Spain.  
  Registered at ClinicalTrials.gov (**NCT00470587**).  
  External validation demonstrated:
  - **C-index = 0.85 (95% CI, 0.79–0.90)**  
  - **Brier score improvement Δ = −0.019 (P < .001)**  
  - **Net reclassification improvement = 0.39 (95% CI, 0.14–0.64; P = .002)**

---

## 👩‍⚕️ Authors and Contributors
**Principal Investigator and Corresponding Author:**  
Francisco Arnalich-Montiel, MD, PhD  
Cornea Unit, Department of Ophthalmology, Hospital Universitario Ramón y Cajal, Universidad de Alcalá, and IRYCIS, Madrid, Spain.  

**Development of web calculator and data analysis:**  
Francisco Arnalich-Montiel, A. Muriel-Herrero, Anabel Blasco-Moreno, Ana Vázquez-Fariñas.  

**SUCCESS Study Group (recruitment collaborators):**  
Francisco J. Muñoz-Negrete, MD, PhD; Martha Stokking; David Mingo-Botín, MD, PhD;  
Nerea Saenz-Madrazo, MD; Jaime Etxebarria-Ecenarro, MD; Pedro Arriola-Villalobos, MD, PhD;  
Ana Boto de Los Bueis, MD; María Gessa-Sorroche, MD.

---

## 📊 Output Interpretation
| Risk Group | Predicted Probability of EK | Clinical Meaning |
|-------------|-----------------------------|------------------|
| Very Low | <5% | Safe for standard cataract surgery |
| Low | 5–20% | Mild risk; routine monitoring |
| Intermediate | 20–50% | Discuss potential EK |
| High | >50% | Consider combined or staged EK |

---

## 📘 Citation
If you use this calculator in research or educational work, please cite as:

> Arnalich-Montiel F, Muriel-Herrero A, Blasco-Moreno A, Vázquez-Fariñas A,  
> *Validation and Extension of the SUCCESS Score for Fuchs Dystrophy After Cataract Surgery.*  
> *JAMA Ophthalmology* (under review, 2025).

---

## ⚠️ Disclaimer and License
This calculator is provided **for academic and educational purposes only**.  
It is **not intended for commercial use, clinical decision-making, or patient care**.  
Any **commercial use, redistribution, or integration into paid software or medical platforms requires prior written permission** from the corresponding author (**F. Arnalich-Montiel, MD, PhD**).  

© 2025 Francisco Arnalich-Montiel and collaborators — All rights reserved.

---

## 🌐 Access
➡️ Online version: [https://arnalich.github.io/SUCCESS-Calculator/](https://arnalich.github.io/SUCCESS-Calculator/)
