# Predicting Mutation Effects on Protein-Protein Interactions using Hybrid Graph Neural Networks

## 📌 Overview
This project focuses on predicting the impact of mutations on protein-protein interactions (PPIs) using a **Hybrid Graph Neural Network (GNN) model**. Protein mutations can alter binding affinity, leading to critical effects in **drug discovery, genetic diseases, and protein engineering**.  

We designed and evaluated a **hybrid model** that combines **Graph Neural Networks (GNNs)** with additional deep learning architectures to improve prediction performance. The model was compared with standard approaches for mutation effect prediction.

---

## ⚙️ Features
- Implemented a **Hybrid GNN architecture** to predict mutation effects on PPIs.  
- Benchmarked results against baseline models (standard GNNs, CNN-based approaches).  
- Curated datasets from **SKEMPI v2** and **PDB structural files**.  
- Generated **graph-based representations** of proteins and integrated structural/sequence information.  
- Visualized predictions to interpret the impact of mutations on stability.  

---

## 🛠️ Tech Stack
- **Languages**: Python  
- **Frameworks & Libraries**: PyTorch, PyTorch Geometric, TensorFlow, NetworkX, NumPy, Pandas, Matplotlib  
- **Tools**: Google Colab, Jupyter Notebook  

---

## 📂 Dataset
- **SKEMPI v2**: Binding free energy changes upon mutation.  
- **Protein Data Bank (PDB)**: Structural data for protein complexes.  

---

## 🚀 Results
- The **Hybrid GNN model** outperformed traditional GNN baselines in predicting mutation effects.  
- Demonstrated improved accuracy in identifying whether mutations **strengthen** or **weaken** PPIs.  
- Results highlight potential applications in **drug discovery pipelines** and **disease mutation analysis**.  

---

## 📊 Comparison
- **Baseline Models**: Standard Graph Neural Networks, CNNs.  
- **Our Hybrid Model**: Combined GNN with additional deep learning layers for enhanced feature extraction.  
- Achieved measurable improvements in prediction metrics over baselines.  

---

## 📖 Future Work
- Explore transformer-based architectures for protein modeling.  
- Extend to **large-scale protein datasets**.  
- Deploy as an **open-source web service** for researchers.  

---

## 👨‍💻 Authors
- Aditya Kumar  
- Akkul Verma  
- Jyotish Yadav  
- Alok Sinha  
- Rudraksh Sevda  

---

## 📜 License
This project is released under the **MIT License**.
