# Diabetes-Classification

This repo contains **` Diabetes-Classification.ipynb`**, a Jupyter Notebook that predicts
whether a patient has diabetes using a neural network written **only with
NumPy**.

### What the notebook does
1. **Load data** · reads `diabetes.csv` (Pima Indians Diabetes dataset).  
2. **Pre-process** · standard-scales features, splits train/validation (80 / 20).  
3. **Build network** · 1 hidden layer (2 neurons) + sigmoid output, coded
   from scratch (forward & back-prop).  
4. **Train** · up to 1000 iterations with mini-report every 100 steps.  
5. **Evaluate** · best run ≈ **0.71 validation accuracy** and **0.81 AUC**;  
   plots training / validation loss curves.
