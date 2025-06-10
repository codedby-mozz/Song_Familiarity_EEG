# EEG Study on Song Familiarity

This repository documents an **independent EEG analysis** project, driven by self-learning, that explores neural responses to familiar vs. unfamiliar melodies.

> 🧠 **Status**: In progress  
> 👩‍🔬 **Purpose**: Personal skill development in EEG analysis and MNE-Python  
> 📚 **Data Source**: Jared R. Girard, Aaron M. Bishop, and Cameron D. Hassall (2025). *Song Familiarity*. OpenNeuro.[Doi: 10.18112/openneuro.ds005876.v1.0.1](https://doi.org/10.18112/openneuro.ds005876.v1.0.1)  

---

## 🧪 Study Overview

The goal is to investigate potential neural markers of auditory familiarity using EEG event-related potentials (ERPs). Specifically, this analysis is focused on answering these questions:

- What are the EEG correlates of the moment a song becomes familiar?
- How does behavioral recognition (accuracy and response time) relate to ERP components or spectral EEG activity?
- Can we detect neural patterns predictive of correct vs incorrect identification?

⚠️ **Note:** This is not an official research project. It is a personal exploration of EEG methods and tools, based on public data.

---

## 🚧 Current Progress

- [x] Preprocessed EEG data for a single participant
- [x] Applied artifact rejection (AutoReject)  
- [x] Epoched data around labeled note events  
- [x] Re-referenced and baseline-corrected the data
- [x] Preprocess EEG data for all participants
- [x] Manual inspection of epochs - Preprocessing was largely automated. I manually reviewed each participant's data to identify any remaining bad epochs or problematic channels. If any significant issues are found, I will revisit and adjust the preprocessing steps accordingly.
- [ ] Reassess preprocessing steps - Some channels for certain participants are too noisy or completely "dead". I am currently reviewing and adjusting preprocessing methods to ensure data quality.
- [ ] Group-level ERP analysis 
- [ ] Statistical comparison of conditions
- [ ] Training an AI on EEG data to classify songs as familiar or unfamiliar

---

## 🧰 Tools & Libraries

- Python
- [MNE](https://mne.tools/stable/index.html)
- [MNE_bids](https://mne.tools/mne-bids/stable/index.html)
- [Matplotlib](https://matplotlib.org)
- [Pandas](https://pandas.pydata.org)
- [Autoreject](https://autoreject.github.io/stable/index.html)
- [Numpy](https://numpy.org)

---

## 📌 Why I'm Doing This

This project supports my self-guided learning in cognitive neuroscience and EEG analysis, aiming to:

- Deepen understanding of EEG preprocessing pipelines  
- Gain hands-on experience with the MNE-Python  
- Explore neural markers of auditory familiarity
- Improve scientific coding and visualization skills  

---

## 🧠 Data Acknowledgment

The EEG data used in this project is sourced from **OpenNeuro**, a platform for open neuroimaging datasets. This analysis is based on one of the publicly available datasets, used here strictly for educational purposes.

Dataset: Song Familiarity 

DOI: [10.18112/openneuro.ds005876.v1.0.1](https://doi.org/10.18112/openneuro.ds005876.v1.0.1)

---

### ✨ Author

This repository is maintained by Andy Hendrikx, an MSc graduate in Cognitive & Clinical Neuroscience.

---
