<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&pause=1000&color=00C2FF&center=true&vCenter=true&width=900&lines=Hi,+I'm+Ahmed+Nasser+Sayed;AI+%26+ML+Engineer;Computer+Vision+Engineer;Deep+Learning+Developer;Building+Intelligent+Systems+That+Matter)](https://git.io/typing-svg)

<p>
  <img src="https://komarev.com/ghpvc/?username=AhmedNasser5&label=Profile+Views&color=0e75b6&style=for-the-badge" alt="views"/>
</p>

</div>

---

## About Me

Computer Science student specializing in Artificial Intelligence and Machine Learning — with a focus on building production-ready systems, not just notebooks.

- Core contributor to **Kemet Vision** — an AI chatbot that classifies ancient Egyptian artifacts from a photo and delivers historical context, deployed on **Google Play & App Store**, and tested in real conditions at the **Grand Egyptian Museum**
- Experienced in the full ML pipeline: data collection, augmentation, model training, ensemble design, OOD filtering, and mobile deployment
- Interested in Computer Vision, Deep Learning, NLP, and Data Analysis
- Always building. Always learning.

---

## Featured Projects

### Kemet Vision — AI Egyptian Artifact Recognition System

An end-to-end AI chatbot that lets users photograph any Egyptian artifact and receive rich historical information in natural language. The system combines a fine-tuned Computer Vision model with an NLP model and is published as a mobile application on both **Google Play** and the **App Store**.

**Highlights:**
- **99.65% validation accuracy** across 74 Egyptian artifact classes (~31,700 images)
- 4-model ensemble: EfficientNet-B4 + CLIP ViT-L/14@336 + CLIP ViT-B/32 + CLIP ViT-B/16
- Cosine similarity OOD filter — rejects out-of-domain images before classification
- Progressive unfreezing training strategy across 3 phases with Mixed Precision (AMP)
- Tested in real-world conditions at the **Grand Egyptian Museum**
- Integrated with an NLP model that generates historical descriptions from classification output

`PyTorch` `EfficientNet-B4` `CLIP` `Hugging Face` `Transfer Learning` `Computer Vision`

---

### Background Removal Pipeline — Egyptian Monument Segmentation

Intelligent background removal system designed as the **pre-processing stage** for Kemet Vision. Isolates monuments, temples, and statues from cluttered museum environments before the classifier receives the image.

**Highlights:**
- BiRefNet + IS-Net weighted ensemble (60/40) for fine-edge segmentation
- LargeStructureSelector — suppresses tourists and small objects, keeps dominant structures
- 6-stage mask refinement: morphological ops, guided filter, bilateral filter, component removal
- Checkpoint system for crash-safe bulk dataset processing
- Coming soon: integrated into the mobile app as a pre-processing step before classification

`PyTorch` `BiRefNet` `rembg / IS-Net` `OpenCV` `Guided Image Filtering`

---

### Pix2Pix — Conditional GAN Image Translation

Full implementation of the Pix2Pix framework for converting architectural line drawings into photorealistic building facades. Includes a custom-trained model, a pretrained PyTorch baseline, quantitative comparison across three metrics, and an interactive Gradio web application.

**Highlights:**
- Custom U-Net generator (8 encoder + 8 decoder layers) with Instance Normalization trained from scratch for 600 epochs on the CMP Facades dataset
- PatchGAN discriminator — encourages sharp, high-frequency structural detail
- Custom-trained model **outperforms the pretrained Berkeley baseline on all three metrics**: MAE ↓21%, PSNR +77% (22.34 vs 12.62 dB), SSIM 3× better (0.71 vs 0.25)
- Optimized training configuration: λ=500 for L1 loss, lr=5e-5, Adam (β₁=0.5), ~3.5 hours on Tesla T4
- Interactive Gradio web app with public URL for live demonstration

`TensorFlow` `PyTorch` `GANs` `U-Net` `PatchGAN` `Gradio` `Computer Vision`

---

### Predictive Maintenance — Machine Failure Prediction (DEPI Scholarship)

ML system that predicts machine failures before they happen using operational sensor data — reducing unplanned downtime and enabling proactive industrial maintenance.

**Highlights:**
- Trained and compared 4 models: Logistic Regression, Decision Tree, SVM, and Random Forest
- Applied SMOTE to handle class imbalance in the target variable
- Tuned Random Forest Classifier achieved **≥ 90% accuracy**
- Full pipeline: EDA, feature engineering, one-hot encoding, SMOTE, hyperparameter tuning, model export
- Features include air temperature, process temperature, rotational speed, torque, and tool wear

`Python` `Scikit-Learn` `Random Forest` `SMOTE` `Pandas` `Matplotlib` `Seaborn`

---

### Call Center Performance Dashboard

Interactive Power BI dashboard for monitoring and analyzing call center operations in real time. Built to give management a clear, data-driven view of service quality, agent efficiency, and customer experience KPIs.

**Highlights:**
- Achieved **98.7% handling calls ratio** and **91.1% service level** across tracked periods
- Maintained a low **1.3% abandonment rate**, reflecting strong queue management
- Tracks four core KPIs: Handling Calls Ratio, Service Level, Abandonment Rate, and Average Speed of Answer (ASA)
- Built with DAX measures, Power Query transformations, and a fully normalized data model
- Designed for operational decision-making — not just reporting

`Power BI` `DAX` `Power Query` `Data Modeling` `SQL` `Excel`

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**AI / Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

**Computer Vision**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![EfficientNet](https://img.shields.io/badge/EfficientNet-orange?style=for-the-badge)
![CLIP](https://img.shields.io/badge/OpenAI%20CLIP-412991?style=for-the-badge)
![Transfer Learning](https://img.shields.io/badge/Transfer%20Learning-success?style=for-the-badge)

**Data & Visualization**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

**Tools & Environment**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Anaconda](https://img.shields.io/badge/Anaconda-44A833?style=for-the-badge&logo=anaconda&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

---

## Experience

**Artificial Intelligence Trainee — National Telecommunication Institute (NTI)**
Intensive program covering Python, ML, Deep Learning, and NLP. Built and evaluated models across classification, regression, and NLP tasks with hands-on project experience.

**AI & Data Science Intern — Digital Egypt Pioneers Initiative (DEPI)**
Applied full ML workflows from data collection and EDA through model training and evaluation. Worked with Pandas, NumPy, Scikit-Learn, and Deep Learning frameworks on real-world datasets.

---

## Certifications

- **DeepLearning.AI** — Machine Learning Specialization (3 courses)
- **ITI** — Machine Learning · Deep Learning · Data Analysis · Data Visualization
- **NTI** — Artificial Intelligence · NLP · Deep Learning Fundamentals
- **DEPI** — Fundamentals of Ai . Machine Learning . Deep Learning . NLP
- AI For Everyone — DeepLearning.AI

---

---

```python
class AhmedNasser:
    role    = "AI & Computer Vision Engineer"
    mission = "Build AI systems that solve real problems — not just score well on benchmarks"
    status  = "Shipping · Learning · Iterating"
```

---

<div align="center">

*Machine Learning . Deep Learning · Computer Vision · NLP · Data Analysis*

</div>
