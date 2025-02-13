# **Leiden University Medical Center: PathAI Organization**

## **Mission**
The **PathAI organization** aims to foster collaboration and streamline code-sharing across all digital pathology projects conducted at the **Leiden University Medical Center (LUMC)**. Our overarching goal is to **standardize digital pathology workflows**, from **quality control (QC) and slide processing** to downstream tasks like **multiple instance learning (MIL), segmentation, and graph neural networks (GNNs)**. 

Standardization enhances **efficiency, reduces errors, and accelerates research** by ensuring reproducibility and resource optimization. Access to the organization is restricted to **LUMC researchers**, who can be invited by one of the moderators. However, select repositories, such as **[PathBench-MIL](https://github.com/Sbrussee/PathBench-MIL)**, will be publicly available.

---

## **Ongoing Computational Pathology Research**
### **Cutaneous Lymphomas Team**
- **Deep Learning–Based Classification of Early-Stage Mycosis Fungoides and Benign Inflammatory Dermatoses**
  - [Study](https://www.sciencedirect.com/science/article/pii/S0022202X24021018)
  - [Code](https://github.com/Sbrussee/MF_BID_MIL)
- **PathBench-MIL: A Comprehensive, Flexible Benchmarking / AutoML Framework for Multiple Instance Learning in Histopathology**
  - [Code](https://github.com/Sbrussee/PathBench-MIL)

### **Endometrial Cancer Team**
- **HECTOR: Multimodal Deep Learning to Predict Distant Recurrence-Free Probability from Digitized H&E Tumor Slides and Tumor Stage**
  - [Study](https://www.nature.com/articles/s41591-024-02993-w)
  - [Code](https://github.com/AIRMEC/HECTOR)
- **Im4Mec: Interpretable Deep Learning Model to Predict the Molecular Classification of Endometrial Cancer**
  - [Study](https://www.sciencedirect.com/science/article/pii/S2589750022002102?via%3Dihub)
  - [Code](https://github.com/AIRMEC/im4MEC)

### **Lung / Salivary Gland Cancers Team**
🚧 *To be announced!*

### **Kidney Team**
🚧 *To be announced!*

### **Bone / Soft Tissue Team**
🚧 *To be announced!*

---

## **Practicalities**
### **Gaining Access**
Access is available to researchers **working in or collaborating with LUMC’s digital pathology research projects**. Please contact a moderator for more information.


### **Goals of the PathAI Organization**
Our repositories aim to **accelerate and standardize digital pathology research** through the following key objectives:

#### **1. Modular Digital Pathology Pipelines**
We provide **small-scale repositories** that fulfill specific needs within the **PathAI workflow** (e.g., **QC, tissue detection, slide processing, normalization, and cell segmentation**). These modules may be **forks of existing repositories** or modified for LUMC’s use cases.

Each module:
- Has its **own dedicated environment** to avoid package conflicts.
- Contributes to a **standardized workflow**, reducing redundant work and allowing researchers to focus on **data engineering and project-specific challenges**.


#### **2. Scripts & Standards for Data Management**
LUMC’s **digital pathology department** is moving towards **FAIR-compliant (Findable, Accessible, Interoperable, and Reusable) data standards**. The PathAI organization will host:
- Scripts for **annotation file creation, data conversion, metadata generation, and SlideScore interoperability**.
- Clearly documented **data standardization guidelines**.
- Tools to **ensure consistency in dataset structure and annotation formats**.


#### **3. Annotation Pipelines**
We provide workflows for **generating and processing annotations** from tools like **QuPath, ASAP, and NuClick**. These repositories will include:
- Scripts to convert **raw annotations into model-ready formats**.
- Best practices for **annotation standardization**.
- Examples of how annotations can be **efficiently used in AI pipelines**.


#### **4. Visualization & Clinical Implementation**
For translation from research to **clinical practice**, PathAI will support:
- **AI-overlay visualization scripts** for **WSI viewers**.
- Integration tools for **slide visualization software**.
- Methods for **clinical validation and interpretability** of AI models.


#### **5. Collaboration & Knowledge Sharing**
A central goal of this organization is to **foster knowledge sharing**. We encourage:
- Active use of the **discussion feature** in repositories to retain expertise from **senior researchers** and provide guidance to **newcomers**.
- Consolidation of **best practices** in digital pathology.
- Open sharing of **educational resources** for researchers entering this field.

---

By organizing our digital pathology efforts within PathAI, we aim to create a **more structured, efficient, and collaborative environment** that accelerates the development and implementation of AI in pathology research. 🚀
