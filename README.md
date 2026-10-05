# 💫 About Me:
I'm building practical machine learning applications with Python,<br>with a focus on demand forecasting, inventory optimization,<br>and visual document understanding.<br><br>My projects combine data processing, model development,<br>error analysis, and reproducible evaluation.<br><br>Recent work includes a Streamlit application for inter-store<br>inventory transfers and a Vietnamese document question-answering<br>pipeline that returns answers with supporting evidence regions.

## 🚀 Featured Projects

### 📄 [DocViVQA](https://github.com/AIVIETNAM-AIO-LeWann/docvivqa)

A Vietnamese visual document question-answering project that combines
page images, OCR, and table structure to produce answers with supporting
evidence regions.

[![DocViVQA — Vietnamese document question answering with evidence](https://raw.githubusercontent.com/AIVIETNAM-AIO-LeWann/docvivqa/main/docs/assets/docvivqa-hero.svg)](https://github.com/AIVIETNAM-AIO-LeWann/docvivqa)

- Contributed to improving an existing competition baseline through
  error analysis of answers, row selection, and evidence regions.
- Improved bold-row detection by removing table grid lines before
  measuring text stroke thickness, with ResNet18 retained as a fallback.
- Refined Argmin/Argmax candidate selection using merged-cell handling
  and checks for complete, unambiguous row context.
- Improved evidence selection by considering duplicate names even
  when some rows have missing numeric values.
- Reproduced the full pipeline with runnable notebooks and scripts
  for inference, training, and submission validation.

**Result:** The team's final pipeline achieved **100.00 raw on the
competition private test**, compared with the original author's
reported baseline score of **94.99**. It also matched all 11,000 training
answers; that training set was used during development and error analysis.

**Scope:** Evaluated on the competition dataset; generalization to other
document collections has not yet been evaluated.

**Stack:** Python · PyTorch · OpenCV · NumPy · Jupyter

[Explore the project](https://github.com/AIVIETNAM-AIO-LeWann/docvivqa)
· [View the inference notebook](https://github.com/AIVIETNAM-AIO-LeWann/docvivqa/blob/main/notebooks/submission_pipeline_context_structure.ipynb)
· [Compare with the baseline](https://github.com/AIVIETNAM-AIO-LeWann/docvivqa/tree/baseline)

---

### 📦 [Inventory Transfer Optimization](https://github.com/AIVIETNAM-AIO-LeWann/inventory-transfer-optimization)

A Streamlit application for demand forecasting and inter-store
inventory rebalancing.

- Compares Historical Average, Moving Average, Random Forest,
  and AdaBoost for demand forecasting.
- Generates transfer plans using Greedy, Integer Programming,
  and Genetic Algorithms.
- Provides inventory analysis, interactive visualizations,
  and CSV export.
- Evaluated on a synthetic retail dataset with 20 stores,
  30 products, and 219,000 daily sales records.

**Status:** Local functional prototype.

## 🔬 How I Work

- Reproduce a baseline before changing the pipeline.
- Inspect individual failures to identify the stage causing an error.
- Compare changes on the same data and check for regressions.
- Report answer quality and supporting evidence, not just aggregate scores.
- Keep code, configuration, and run artifacts organized for reproducibility.

# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

# 📊 GitHub Stats:
![](https://github-readme-stats.shion.dev/api?username=AIVIETNAM-AIO-LeWann&theme=aura_dark&hide_border=false&include_all_commits=true&count_private=false)<br/>
![](https://streak-stats.demolab.com/?user=AIVIETNAM-AIO-LeWann&theme=aura_dark&hide_border=false)<br/>
![](https://github-readme-stats.shion.dev/api/top-langs/?username=AIVIETNAM-AIO-LeWann&theme=aura_dark&hide_border=false&include_all_commits=true&count_private=false&layout=compact)

---
[![](https://komarev.com/ghpvc/?username=AIVIETNAM-AIO-LeWann&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
