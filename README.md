# Climate Shift Detection using Synthetic Image Data

This project demonstrates how to identify climate shifts (e.g., El Niño, La Niña, Neutral phases) using image-based pattern recognition powered by Convolutional Neural Networks (CNNs). To simulate real-world scenarios, we generate synthetic climate images that represent different climate states and train a deep learning model to classify them.

## 🔍 Project Highlights

- **Synthetic Climate Image Generation**: Create simple representations of different climate regimes using mathematical functions.
- **Deep Learning Model (CNN)**: Learn spatial patterns in synthetic image data.
- **Evaluation**: Classification accuracy, prediction visualization, and metrics.
- **Downloadable Dataset**: Save and explore the synthetic dataset in Excel format.

---

## 🗂 Files

| File | Description |
|------|-------------|
| `climate_shift_cnn.py` | Main script for image generation, model training, and evaluation. |
| `synthetic_climate_data.xlsx` | Flattened image data with labels in tabular format (Excel). |
| `README.md` | Project overview and instructions. |

---

## 🛠 Setup

Install the required packages:

```bash
pip install numpy matplotlib tensorflow scikit-learn pandas openpyxl
🚀 Run the Project
Generate synthetic image data for climate patterns.

Train a CNN model to classify images.

Evaluate model accuracy and predictions.

Example run:

python


# Run the script in Python environment
python climate_shift_cnn.py
📊 Dataset Description
Each climate pattern is represented by a 64x64 grayscale image:

El Niño: Gaussian-like warm anomaly.

La Niña: Sinusoidal cold pattern.

Neutral: Random noise-based representation.

The Excel file (synthetic_climate_data.xlsx) contains:

4096 columns for pixel values (64x64).

1 column for the corresponding climate label.

📌 Future Work
Integrate real satellite or reanalysis data (e.g., NOAA SST).

Use sequence models (e.g., ConvLSTM) for temporal pattern recognition.

Apply unsupervised learning for shift detection without explicit labels.

🧠 Author
Tarinabo williamtarinabo@gmail.com

