# Optical-Guided Super-Resolution for Thermal Imaging

Deep learning framework for enhancing **Low-Resolution (LR) Thermal Images** using **High-Resolution (HR) Optical RGB Images** through an Optical-Guided Super-Resolution approach.

The project leverages a GAN-based architecture consisting of an Enhanced U-Net Generator and a PatchGAN Discriminator to reconstruct high-quality thermal images while preserving fine structural details and improving thermal visualization.

---

## 📌 Features

- Optical-guided thermal image super-resolution
- Enhanced U-Net Generator with Attention
- PatchGAN Discriminator
- Multi-loss optimization
- High-resolution thermal image reconstruction
- Temperature estimation
- Heatmap generation
- Streamlit-based user interface
- PyTorch implementation

---

## 🖼️ Project Overview

**Input**

- Low-Resolution Thermal Image
- High-Resolution Optical RGB Image

⬇️

**Deep Learning Model**

- Enhanced U-Net Generator
- Attention Blocks
- PatchGAN Discriminator

⬇️

**Output**

- High-Resolution Thermal Image
- Temperature Map
- Heatmap
- Difference Map

---

## 🏗️ Model Architecture

### Generator

- Enhanced U-Net
- Attention Gates
- Skip Connections

### Discriminator

- PatchGAN

### Loss Functions

- L1 Loss
- Perceptual Loss
- Edge Loss
- Physics-based Loss
- Adversarial Loss

---

## 🛠️ Technology Stack

- Python
- PyTorch
- TorchVision
- OpenCV
- NumPy
- Matplotlib
- Streamlit

---

# 📂 Repository Structure

```text
Optical-Guided-Super-Resolution-Thermal-Imaging/
│
├── app/
├── src/
├── outputs/
├── models/
├── requirements.txt
├── README.md
└── LICENSE
```

---

# 📥 Dataset & Trained Model

## 🤖 Trained Model

https://drive.google.com/drive/folders/1VpYM35IJdfmYyB-YRZ53rD3cTz1nDn3_?usp=drive_link

---

## 🌡️ Low Resolution Thermal Images

https://drive.google.com/drive/folders/1j8hUqQHfjHvEoGJQaDWU-VmWYoalo5hg?usp=drive_link

---

## 📷 High Resolution Optical RGB Images

https://drive.google.com/drive/folders/1YFYjFUUpdDYJv_BgKD92SoHPLOh4MiWW?usp=drive_link

---

## 🔥 Ground Truth High Resolution Thermal Images

https://drive.google.com/drive/folders/1e4qCGX7gvEqPrToqeRKOCynrb3iUFVYG?usp=drive_link

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/your-username/Optical-Guided-Super-Resolution-Thermal-Imaging.git
```

Move to the project folder

```bash
cd Optical-Guided-Super-Resolution-Thermal-Imaging
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Project

```bash
streamlit run app.py
```

---

# 📊 Results

The model generates:

- High-Resolution Thermal Images
- Temperature Maps
- Heatmaps
- Difference Maps
- Enhanced Structural Details

---

# 📈 Evaluation Metrics

- PSNR
- SSIM
- RMSE
- LPIPS

---

# 🎯 Applications

- Industrial Inspection
- Medical Thermal Imaging
- Autonomous Driving
- Fire Detection
- Electrical Equipment Monitoring
- Remote Sensing
- Surveillance

---

# 🔮 Future Work

- Real-time deployment
- Transformer-based models
- Lightweight inference
- Mobile deployment
- Edge AI optimization

---

# 👨‍💻 Author

**Prasad Hiragond**

MCA Graduate | Deep Learning | Computer Vision | Python Developer

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.
