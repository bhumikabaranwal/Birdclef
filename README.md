# 🐦 BirdCLEF M 2025 – Acoustic Species Recognition

This project is part of the **BirdCLEF M 2025 Kaggle Competition**, focused on identifying under-studied species based on their acoustic signatures in tropical lowland rainforests. Using machine learning, the project processes continuous audio data to recognize species from different taxonomic groups — enabling large-scale, cost-effective biodiversity monitoring.

---

## 🌱 Overview

Traditional biodiversity surveys are expensive and time-consuming. This project leverages **passive acoustic monitoring (PAM)** and modern **machine learning** techniques to identify rare and endangered species from soundscape data in the **Magdalena Valley** of Colombia.

The machine learning model developed in this project aims to:
- Detect and classify species with limited labeled data.
- Utilize unlabeled audio data to enhance detection.
- Support conservationists in monitoring ecological restoration efforts more efficiently.

---

## 📍 Context

The **Magdalena Valley** in Colombia is one of the most biodiverse regions on Earth, but it's under severe threat due to deforestation, cattle ranching, and illegal logging. The **El Silencio Natural Reserve** — protecting 5,407 acres of tropical forests and wetlands — is a critical site for ecological restoration and biodiversity conservation.

Key biodiversity stats from El Silencio:
- 🐦 295 bird species
- 🐸 34 amphibian species
- 🐾 69 mammal species
- 🐍 50 reptile species
- 🌿 Nearly 500 plant species

The goal is to automate species detection from soundscape data collected in this reserve and contribute to monitoring the success of restoration projects.

---

## 🎯 Goals of the Competition

1. **Species Identification**: Detect species from different taxonomic groups using acoustic recordings from El Silencio Natural Reserve.
2. **Limited Data Training**: Build models that perform well even with minimal labeled data, especially for rare/endangered species.
3. **Unlabeled Data Utilization**: Improve classification results by leveraging large volumes of unlabeled data.

Successful models will make it easier for researchers to analyze biodiversity and adjust conservation actions based on real-time insights.

---

## 🧠 Project Highlights

- Built a machine learning pipeline for species classification from audio.
- Focused on transfer learning and semi-supervised learning to handle limited labels.
- Applied data preprocessing techniques using audio libraries like Librosa.
- Evaluated performance on diverse and imbalanced species datasets.

---

## 📁 Project Structure

```bash
├── update-version-of-birdclef-m-2025.ipynb   # Main Jupyter notebook
├── data/                                     # (Not included) Directory for input audio and metadata
├── models/                                   # Trained model weights and logs
├── requirements.txt                          # Python dependencies (optional)
└── README.md                                 # Project description and instructions
```

---

## 🛠 Tech Stack

- Python
- Jupyter Notebook
- Librosa (audio processing)
- PyTorch / TensorFlow
- Pandas, NumPy

---

## ▶️ How to Run

```bash
# Step 1: Clone the repository
git clone https://github.com/yourusername/birdclef-m-2025.git
cd birdclef-m-2025

# Step 2: Install dependencies (if using requirements.txt)
pip install -r requirements.txt

# Step 3: Run the notebook
jupyter notebook update-version-of-birdclef-m-2025.ipynb
```

> Replace `yourusername` with your GitHub username in the clone link above.

---

## 📊 Results and Impact

By applying machine learning to soundscape data, this project helps:
- Improve biodiversity monitoring at scale.
- Enable fast, automated detection of multiple species.
- Assist conservation teams in making data-driven decisions.

---

## 🤝 Acknowledgments

This competition is collaboratively organized by:
- Chemnitz University of Technology  
- Fundación Biodiversa Colombia  
- Google Research  
- iNaturalist  
- Instituto Humboldt  
- K. Lisa Yang Center for Conservation Bioacoustics (Cornell Lab of Ornithology)  
- LifeCLEF  
- Red Ecoacústica Colombiana  
- University College London (UCL)  
- Xeno-canto  

Special thanks to the local communities and researchers working to protect Colombia’s rich biodiversity.

---

## 🙋‍♀️ Author

**Bhumika Baranwal**  
B.Tech CSE (3rd Year), NIT Delhi  

---

## 📄 License

This project is licensed under the **MIT License**.
