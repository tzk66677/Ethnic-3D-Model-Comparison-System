# IMGD-MS-Project
# Ethnic-3D-Model-Comparison-System
### 3D Facial Comparison & Cultural Visualization Web System
---
## Project Overview

**Ethnic-3D-Model-Comparison-System-glb** is a web-based, academic-grade 3D facial model comparison system designed for researchers, educators, students, developers, and the general public.

The platform focuses on **3D head models of Chinese ethnic minorities**, created in **Maya (centimeter units)** and exported as **GLB assets**, aiming to provide a **neutral, data-driven visualization** of facial diversity across different ethnic groups in China.

By offering interactive 3D comparison tools and cultural annotations, the platform helps:
- Demonstrate **natural facial variation** between ethnic groups  
- Support **academic teaching, presentations, and research**  
- Reduce misunderstandings and stereotypes  
- Enable overseas developers and researchers to better understand the appearance and diversity of China’s multi-ethnic population  

The system is fully frontend-based, built with Three.js + native HTML/CSS/JavaScript.

## Project Objectives

The platform is designed to achieve the following objectives:

1. Enable **side-by-side comparison** of two 3D models (A vs B)  
2. Support **local file upload** and **static asset loading**  
   - Formats: **GLB**  
3. Provide **ethnic group and gender classification**  
4. Implement an **ethnic facial feature annotation system**  
5. Support **bilingual interface switching (Chinese / English)**  

---
## System Functional Requirements
### 3.1 3D Model Functionality
- Supports **OBJ / GLB / GLTF** formats  
- Allows users to upload **local 3D model files**  
- Provides three comparison modes:
  - Side-by-Side
  - Overlay
  - Single Model
- Interactive controls:
  - Rotation  
  - Zoom  
  - Pan  
  - Automatic rotation  
  - View reset  
- Camera utilities:
  - **Normalize Scale** (for models with different units)  
  - **Automatic camera framing**

---
### 3.2 Ethnic + Gender Presets
The system includes **nine Chinese ethnic minority groups**, each differentiated by gender:

- Mongolian  
- Zhuang  
- Dai  
- Wa  
- Uyghur  
- Bai  
- Tajik  
- Achang  
- Dong  

Model naming convention:
Example:
mongol_male.glb
mongol_female.glb

---

### 3.3 Bilingual System
- One-click **Chinese / English language switching**
- All interface elements are bilingual:
  - Buttons  
  - Labels  
  - Mode names  
  - System prompts  
  - Annotation text  
- Language state is synchronized across the system

---

### 3.4 Ethnic Characteristics Annotation System

Text annotation panels are displayed on **both sides of the 3D viewer**, providing contextual explanations for the selected models:

- Common facial characteristics of the selected ethnic group  
- Explanations related to:
  - Geography  
  - Environment  
  - Lifestyle  
- Annotation text:
  - Automatically updates with **ethnic group selection**  
  - Automatically updates with **language switching**

This feature is designed for **academic interpretation rather than aesthetic judgment**.

---

## System Architecture

project/
├── index.html # Main entry point
├── assets/ # 3D model assets (GLB)
│ ├── mongol_male.glb
│ ├── mongol_female.glb
│ └── ...
├── data/ # Structured data (JSON)
│ └── data.json
├── public/ # Static resources (icons, UI images, fonts)
│ ├── main.css
│ └── main.js
└── README.md


This structure separates **models**, **data**, and **presentation resources**, making the system easier to maintain, extend, and reuse in academic or production environments.

---

## User Operation Flow

1. Open the **homepage (`index.html`)**  
2. Select **interface language**  
3. Choose **ethnic group A / B** and **gender**  
4. 3D models load automatically  
5. Select a **comparison mode**  
6. Read **facial feature annotations** displayed on both sides of the viewer  

---

## Deliverables

The project delivers the following components:

1. **index.html** – Main 3D comparison interface  
2. **assets/** – 3D model resources (GLB-based)  
3. **data/** – JSON-based configuration and annotation data  

---

## License & Usage

**Ethnic-3D-Model-Comparison-System-glb** is intended for:

- Academic research  
- Educational use  
- Cultural visualization  
- Non-commercial demonstrations  

All 3D models and cultural descriptions should be used with appropriate attribution and cultural respect.

## Model Disclaimer

The 3D facial models presented in this project are **research-oriented visual representations** created for the purposes of **academic study, education, and cultural visualization**.

Please note the following:

- The models **do not represent any specific real individual**.  
  All facial features are synthesized, averaged, or artistically reconstructed based on general anthropometric references and academic sources.

- The models **do not claim to represent the full diversity** within any ethnic group.  
  Facial appearance varies widely among individuals, regions, and communities, and no single model should be interpreted as a definitive or exhaustive representation.

- The models are **not intended for identification, profiling, or classification of real people**, nor should they be used for biometric, surveillance, or discriminatory purposes.

- Facial features shown in this system are presented **solely for educational and comparative visualization**, aiming to illustrate how geography, environment, and historical lifestyle may influence general morphological tendencies.

- Any resemblance to real persons, living or deceased, is **purely coincidental**.

This project emphasizes **cultural respect, academic neutrality, and responsible use of visual data**, and all content should be interpreted within its stated educational and research context.
