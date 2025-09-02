# MSc Project – Brain Tumour Sub-Region Classification (BraTS-Path 2025)

This repository contains the code and outputs developed as part of my MSc Data Science dissertation project, where I explored deep learning approaches for **patch-level classification of glioblastoma sub-regions** using the **BraTS-Path 2025 dataset**.

The work was submitted both:  
- As my **MSc dissertation project**  
- As an official submission to the **BraTS-Path 2025 Challenge**, part of the **MICCAI International Conference**.

I am honoured that my submission was **accepted for presentation** at **MICCAI 2025 in Daejeon, South Korea**, where I was invited to present my findings as a **poster submission**.

---

## 📂 Contents

- **MobileNetV2_Baseline_model_(BraTS_Path).ipynb** – baseline MobileNetV2 with ImageNet pre-training.  
- **Optuna_MobileNetV2_Optimised_model_(BraTS_Path).ipynb** – optimised MobileNetV2 with Optuna-based hyperparameter search.  
- **K_Fold_Cross_Validation_(BraTS_Path).ipynb** – extended validation pipeline with stratified k-fold cross-validation.  
- **val_predictions.csv** – predictions from the optimised model on the anonymised validation set.  
  - Columns: `Image-Name`, `Predicted Class`, `Confidence Score`.

---

## 📊 Status

📄 My full MSc dissertation report may be uploaded here soon.  

---

## 📖 Citation

If you find this work useful, please cite it
