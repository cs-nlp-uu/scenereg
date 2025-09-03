# COOCO: Common Objects Out-of-Context

**Authors:** Filippo Merlo\*, Ece Takmaz, Wenkai Chen, Albert Gatt
\*Corresponding author: [f.merlo.research@gmail.com](mailto:f.merlo.research@gmail.com)
**Affiliations:** Utrecht University, University of Trento

---

## 🌐 Project Overview

This repository supports the paper:

**"Common Objects Out-of-Context: Semantic Violation in Scenes for Investigating Multimodal Context in Referential Communication"**
*Submitted to TACL (under review)*

COOCO is a large-scale dataset for studying how **Vision-Language Models (VLMs)** use scene context in **referring expression generation**. It introduces **semantic violations** by replacing target objects with alternatives of **low**, **medium**, or **high semantic relatedness** to the scene, plus a **same-target control**.

Each sample includes:

* An original scene from COCO-Search18 with a labeled **target object**
* A **Clean version** (object removed)
* Multiple **inpainted versions** with semantically manipulated replacements

Semantic relatedness is computed using **ConceptNet embeddings** and **THINGSplus norms**, with inpainting guided by LLaVA prompts and validated via automated visual QA.

COOCO enables novel investigations into:

1. **Object naming in context** (referring expression generation)
2. **Robustness testing** under **scene-object incongruity**

---

> 📦 **Data**: [GitHub Repository](https://github.com/cs-nlp-uu/scenereg)
