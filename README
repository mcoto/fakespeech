# Implementation of a Fake Speech Detection System

## Project Description
This project aims to implement a system for the **automatic detection of synthesized speech** (fake speech / audio deepfake) using open-source models. The system will be adapted and validated in the context of **Costa Rican voices** to assess its effectiveness in detecting falsified audio.

The increasing availability of speech synthesis models (TTS and Voice Cloning) poses challenges to **security**, **information veracity**, and **trust** in digital environments. This work seeks to lay the groundwork for defense tools against these risks.



---

## Requirements
- **Python:** 3.10 or higher  
- **Main libraries:**  
  - `torch`
  - `torchaudio`
  - `scikit-learn`
  - `librosa`
  - `matplotlib`
  - `pandas`

### Install dependencies:

```bash
pip install -r requirements.txt
````

---

## How to Run the System

### Prepare the Dataset

1. Place **real audio** in:

   ```
   data/real/
   ```
2. Place **fake audio** in:

   ```
   data/fake/
   ```
3. Fill in the file:

   ```
   dataset_info.csv
   ```

   with the required metadata (e.g., filename, label, duration, source).

---

### Run Detection

```bash
python src/detect.py
```

---

### Check Results

* Review predictions in:

  ```
  results/detections.csv
  ```
* Review calculated metrics in:

  ```
  results/metrics.json
  ```

---

## Evaluation Metrics

The following metrics will be used:

* **Accuracy**
* **Precision**
* **Recall**
* **AUC**
* **Equal Error Rate (EER)**

---

## Contribution and Pull Request Guidelines

1. **Fork** this repository.
2. Create a new branch for your development:

   ```bash
   git checkout -b feature/student-name
   ```
3. Add your files and modifications.
4. Commit your changes:

   ```bash
   git commit -m "Fake speech detection implementation - [Student name]"
   ```
5. Push your branch:

   ```bash
   git push origin feature/student-name
   ```
6. Open a **Pull Request** describing the changes you made.


---

## License

This project is developed for academic purposes at the **University of Costa Rica** and is intended exclusively for educational and research use.
