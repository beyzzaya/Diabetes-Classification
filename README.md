# Diabetes-Classification

This repository contains **`Diabetes-Classification.ipynb`**, a step-by-step Jupyter Notebook that
predicts whether a patient has diabetes using a **Keras Sequential** model
built on the classic *Pima Indians Diabetes* dataset (`diabetes.csv`).

### Key points
- Reads the dataset, scales features with **MinMaxScaler**.  
- Splits data 80 % / 20 % for train / validation.  
- Builds a simple dense network (`[32-64-128-256-512] → sigmoid`).  
- Trains with the **tf.data** input pipeline for efficiency.  
- Achieves **≈ 0.78 validation accuracy** after 100 epochs (Task 6 result).  
- Provides comments (in Turkish) explaining each step.
