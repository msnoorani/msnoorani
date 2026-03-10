# Hi, I'm Muhammad Salahuddin 👋

**MSc Artificial Intelligence & Data Science | University of Hull**  
Specialising in **Computer Vision · Unsupervised ML · NLP · Big Data**

I apply the precision of astrophysics to real-world problems — from detecting ionised bubbles in simulated galaxies to classifying vehicle damage for insurance workflows. My work spans the full ML pipeline: data cleaning, model building, evaluation, and deployment-ready code.

📍 Hull, UK &nbsp;|&nbsp; 🎓 MSc Graduate (2026) &nbsp;|&nbsp; 🔍 Open to ML Engineer / Data Scientist roles

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| **Languages** | Python |
| **ML / DL** | Scikit-learn, TensorFlow, Keras, PyTorch |
| **Computer Vision** | CNN, U-Net++, OpenCV, Image Segmentation |
| **NLP** | Naive Bayes, SVM, LSTM, RNN, CNN, TF-IDF, Gensim |
| **Unsupervised ML** | KMeans, DBSCAN, Hierarchical Clustering, HDBSCAN |
| **Data Science** | Pandas, NumPy, Matplotlib, Seaborn, SQL, SQLite |
| **Big Data** | Apriori (Association Rules), Time Series, Social Network Analysis (NetworkX) |
| **Deployment** | FastAPI (learning), Docker (learning) |
| **Tools** | Git, GitHub, Jupyter Notebook, Google Colab |

---

## 📌 Featured Projects

### 🔭 [Unsupervised ML — Ionised Bubble Detection in Galaxies](https://github.com/msnoorani/Unsupervised-ml-ionised-bubbles)
> MSc Dissertation | University of Hull | Supervisor: Alex Richings

Compared **4 unsupervised methods** for detecting H-II regions in synthetic Hα galaxy images from Richings et al. (2022) FIRE-2 simulations across 5 galaxies.

- **Hierarchical Clustering** identified **1,839–2,479 structures per galaxy** (mean: 2,146 ± 249) — most consistent and physically meaningful method
- DBSCAN identified only 1–8 regions; KMeans produced arbitrary 4–5 partitions
- Same segmentation logic applicable to **medical imaging and satellite image analysis**
- `Scikit-learn` · `SciPy` · `KMeans` · `DBSCAN` · `Agglomerative Clustering` · `Blob Extraction`

---

### 🗣️ [Sentiment Analysis of Amazon Kindle Reviews — 5 NLP Models](https://github.com/msnoorani/Sentiment-Analysis-Amazon-Reviews-NLP)
> Applied AI Module | University of Hull

Built and compared **5 ML models** for binary sentiment classification on Amazon Kindle reviews.

- **Naive Bayes achieved 84.06% accuracy** — outperforming LSTM, RNN and CNN
- CNN achieved highest **ROC-AUC: 90.01%** and **PR-AUC: 94.54%**
- Key insight: Simple RNN outperformed LSTM — Kindle reviews are too short for long-range memory to help
- `Naive Bayes` · `SVM` · `LSTM` · `SimpleRNN` · `CNN` · `SMOTE` · `GridSearchCV`

---

### 🚗 [Vehicle Damage Classification — CNN for Insurance Claims](https://github.com/msnoorani/Vehicle-Damage-Classification-Using-CNN-for-Insurance-Claims)
> Understanding AI Module | University of Hull

Built a **CNN** to classify 5 vehicle damage types from images (scratch, dent, flat tire, broken window, broken lamp) for automated insurance claim verification.

- **62.67% validation accuracy** on imbalanced dataset (70–384 samples per class)
- Window damage detection: **95% recall** — correctly identified 180/189 broken windows
- Dropout (p=0.5) + data augmentation kept train/val gap to just **2–3%**
- `TensorFlow/Keras` · `Conv2D` · `MaxPooling` · `SGD` · `ImageDataGenerator`

---

### 📊 [Customer Spending Prediction — Streaming Service ML](https://github.com/msnoorani/Customer-Spending-Prediction-Streaming-ML)
> Understanding AI Module | University of Hull

Full supervised + unsupervised ML pipeline on streaming customer data — regression, churn classification, and behavioural clustering.

- **Multi-variable Linear Regression: R² = 0.959** — outperformed ANN (0.946) and Random Forest (0.933)
- Random Forest Classifier: **100% accuracy** on churn prediction
- K-Means (k=3) identified high-value, at-risk, and low-engagement customer segments
- `Linear Regression` · `Random Forest` · `ANN (MLPRegressor)` · `KMeans` · `Hierarchical Clustering` · `PCA`

---

### 🏙️ [Urban Development Planning — Census Data Science](https://github.com/msnoorani/Urban-Development-Planning-Using-Census-Data-Data-Science-Project-)
> Fundamentals of Data Science | University of Hull

Cleaned and analysed a mock UK census (1881 format) to advise a local government on infrastructure investment decisions.

- Recommended **train station** over 5 alternatives — justified by commuter population analysis
- Recommended **old age care funding** — justified by 10-year elderly population projection
- Religion breakdown: 45.12% no religion · 28.02% Christian · 14.41% Catholic
- `Pandas` · `Seaborn` · `Statistical Analysis` · `Crude Rates` · `Age Pyramids`

---

### 🚦 [UK Road Accident Analysis & Social Network Mining](https://github.com/msnoorani/UK-Road-Accident-Analysis-and-Social-Network-Mining)
> Big Data and Data Mining Module | University of Hull

Two-part project: spatiotemporal analysis of 2019 UK accident data + Facebook social network community detection.

- Peak accidents: **18:00 on Fridays** (commuter rush) · Pedestrians peak at **15:30** (school run)
- KMeans geospatial clustering on Hull/East Riding with **interactive Folium maps**
- Apriori association rules: high speed + rural area → fatal/serious severity
- Louvain community detection on 4,039-node Facebook graph: **15 communities detected**
- `SQLite` · `Apriori` · `KMeans` · `DBSCAN` · `Folium` · `NetworkX` · `Louvain`

---

## 🌱 Currently Building

**Polyp Segmentation with U-Net++** — applying the same segmentation logic from my astrophysics dissertation to clinical diagnostics. Building a FastAPI endpoint so the model is deployable, not just a notebook.

---

## 📈 What I Bring

- **Physics background** → rigorous, evidence-based approach to data problems
- **End-to-end projects** → not just model training, but data cleaning, evaluation, and documented results
- **Cross-domain thinking** → galaxy segmentation → medical imaging → satellite analysis
- **Honest evaluation** → I report when simpler models beat complex ones (Naive Bayes > LSTM)

---

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Muhammad_Salahuddin-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/muhammad-salahuddin-080678385/)
[![GitHub](https://img.shields.io/badge/GitHub-msnoorani-black?style=flat&logo=github)](https://github.com/msnoorani)

> 💬 Open to Junior ML Engineer, Data Scientist, Computer Vision, and Research Assistant roles in the UK.  
> I'm particularly interested in HealthTech, Earth Observation, and applied AI teams.
