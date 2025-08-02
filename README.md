# EEG Emotion Classification using Genetic Algorithm-based Feature Selection and Gamma Function-based Dynamic Feature Fusion

This is the official implementation of the paper:

**"EEG Emotion Classification using Genetic Algorithm-based Feature Selection and Gamma Function-based Dynamic Feature Fusion Presented at XXVIII International Conference on Soft Computing and Measurement (SCM'2025)"**

## 🧠 Overall Workflow

The proposed framework integrates **robust feature selection** with a **dual-branch deep learning model**, fusing the resulting features using a novel **Gamma function-based dynamic fusion mechanism** for highly accurate **EEG-based emotion recognition**.

![architecture](https://github.com/praetorian2710/Emotion-Recognition-mRMR-GA-Gamma/blob/main/assets/architechture.png)
---

## 🔍 Feature Selection: `mRMR + Genetic Algorithm`

To construct an optimal and compact feature set, we apply a two-stage selection process:

- **Minimum Redundancy Maximum Relevance (mRMR):**  
  Reduces the initial feature space by selecting features that are highly **relevant** to emotion classes and exhibit **minimal redundancy** among themselves.

- **Genetic Algorithm (GA):**  
  Further optimizes the feature subset using an **evolutionary search** to identify combinations that yield **maximum classification performance**.

---

## 🔗 Gamma Function-based Feature Fusion

A novel **Gamma function-based fusion mechanism** is proposed to dynamically combine the features extracted from two parallel branches:

- **ANN Branch**
- **BiLSTM Branch**

The Gamma function assigns **adaptive weights** to the feature vectors, enhancing the most **discriminative features**. The fused vector is then passed to a **fully connected classifier** for final emotion classification.

---

## 📈 Results

The model demonstrates **state-of-the-art performance** with superior classification accuracy and clear class separation on benchmark EEG datasets:

- SEED Dataset
- EEG Brainwave Dataset

---

## 🎯 Visualizations

![TSNE-Plot](https://github.com/praetorian2710/Emotion-Recognition-mRMR-GA-Gamma/blob/main/assets/SEED-BW-tsne_GA.png)

---

## ✍️ Authors

- Jotiraditya Banerjee  
- Asfak Ali  
- Om Karmakar  
- Avigyan Roy  
- Daria Sidorina  
- Ram Sarkar  

---

## 📚 Citation

If you find this work useful in your research, please cite:

```bibtex
@inproceedings{banerjee2025eeg,
  title={EEG Emotion Classification Using Genetic Algorithm-Based Feature Selection and Gamma Function-Based Dynamic Feature Fusion},
  author={Banerjee, Jotiraditya and Ali, Asfak and Karmakar, Om and Roy, Avigyan and Sidorina, Daria and Sarkar, Ram},
  booktitle={2025 XXVIII International Conference on Soft Computing and Measurements (SCM)},
  pages={152--155},
  year={2025},
  organization={IEEE}
}
