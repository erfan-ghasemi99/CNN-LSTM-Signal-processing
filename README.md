# CNN-LSTM-Signal-processing

🧠 Automatic Diagnosis of Schizophrenia from EEG Signals using CNN-LSTM (based on 2109.01120v2)

This project implements a deep learning model for the automatic classification of schizophrenia using raw EEG data. The approach is based on the paper *"Automatic Diagnosis of Schizophrenia in EEG Signals Using CNN-LSTM Models"* by P. R. Sharma et al. (arXiv:2109.01120v2).

We used 1142 EEG frames (6250×19) extracted from 28 subjects (14 SZ + 14 HC), each segmented into 33 frames. The EEG data were preprocessed using Z-score and L2 normalization, as described in the original paper.

The CNN-LSTM architecture achieves **92.29% ± 1.63% validation accuracy (5-fold cross-validation)** on the dataset.  
All training, evaluation, and visualization codes (ROC, confusion matrix, etc.) are included.

📌 Final model includes:
- Two 1D Conv layers
- MaxPooling
- LSTM (100 units)
- Dropout layers
- Fully connected classification head

🎯 Reproducible, clean, and ready for experimentation or clinical adaptation.

