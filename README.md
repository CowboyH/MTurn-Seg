# MTurn-Seg: A Large-Scale Bilingual Medical Benchmark for Multi-Turn Reasoning Segmentation
Official repository for “MTurn-Seg: A Large-Scale Bilingual Medical Benchmark for Multi-Turn Reasoning Segmentation (BIBM 2025)”.  You can check the current version here: [https://cowboyh.github.io/MTurn-Seg/](https://cowboyh.github.io/MTurn-Seg/). 
## Authors
**Haitao Nie***, **Yimeng Zheng***, **Ying Ye***, **Bin Xie**†  
Artificial Intelligence and Robotics Laboratory (AIRLab),  
Central South University, Changsha, China

\* Equal contribution.  
† Corresponding author.
## Highlights

* **New Task — Multi-Turn Reasoning Segmentation (MTRS):** At each turn, the model consumes the **current instruction + interaction history** (prior prompts and masks) to produce the **next segmentation**.
* **Three Reasoning Facets:** (i) **Clinical/Anatomical** (e.g., “segment the solid organ in the right upper abdomen involved in glucose metabolism”), (ii) **Spatial** (e.g., “segment the elliptical structure adjacent to the right side of the abdominal aorta”), (iii) **History-based References** (e.g., “segment the necrotic region surrounding the previously segmented tumor”).
* **Bilingual Benchmark (ZH/EN):** First dataset supporting **multi-turn medical dialogues** in **Chinese and English**.
* **Scale & Coverage:** **28,904 images**, **113,963 masks**, **232,188 QA pairs** across **CT & MRI**; covers major organs and anatomical systems.
* **What It Measures:** Cross-turn **memory**, **history-conditioned mask refinement**, and **language-to-image alignment** over multiple rounds.
* **SOTA Evaluation:** Benchmarked **MedCLIP-SAM**, **LISA**, and **LISA++** under multi-turn settings.
* **Key Findings:**

  1. Current models are **well below clinical usability** on this benchmark.
  2. **Performance degrades** as dialogue turns increase.
  3. **General-purpose models** outperform **medical-specific** models, indicating a need to infuse stronger domain knowledge.
* **Intended Impact:** Establishes the **first large-scale yardstick** for MTRS, enabling fair, reproducible comparison and catalyzing progress on **multi-turn reasoning in medical imaging**.

## License
MTurn-Seg Dataset License: CC BY-NC-SA 4.0

You are free to share and adapt the dataset under the following terms:
- Attribution (BY)
- NonCommercial (NC)
- ShareAlike (SA)

Full text: https://creativecommons.org/licenses/by-nc-sa/4.0/

## 📚 Citation
If you find this work useful or use this dataset in your research, please cite our paper.<br>
**Note: The paper has been accepted at BIBM 2025 and is to appear; final publication details (e.g., pages/DOI) will be updated upon release.**

**BibTeX**
```bibtex
@InProceedings{MTurnBIBM,
  author    = {Haitao Nie, Yimeng Zheng, Ying Ye, Bin Xie},
  title     = {MTurn-Seg: A Large-Scale Bilingual Medical Benchmark for Multi-Turn Reasoning Segmentation},
  booktitle = {Proceedings of the IEEE International Conference on Bioinformatics and Biomedicine (BIBM)},
  year      = {2025},
}


