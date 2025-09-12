# 🌸 Ghibli Style Image Generation

This project explores **image-to-image translation** in the style of Studio Ghibli artwork.  
It applies deep learning models to transform input photos or sketches into images that resemble the warm, hand-painted aesthetic of Ghibli films.

---

## 📂 Project Structure
```
Ghibli_Style_Image_Generation/
├── v1/               # First prototype experiments
├── v2/               # Improved version with refined models
├── presentation.pptx # Project presentation slides
├── report.pdf        # Final written report
└── 彥璋期末實驗報告.pdf  # Team member’s final report
```

---

## 🚀 Features
- Data preprocessing pipeline for training
- Neural style transfer / GAN-based methods
- Comparison between model versions (`v1` and `v2`)
- Report and presentation slides included for reference

---

## 🛠️ Requirements
- Python 3.8+
- PyTorch / TensorFlow (depending on implementation)
- Jupyter Notebook (for experiments)

Install dependencies:
```bash
pip install -r requirements.txt
```

---

## ▶️ Usage
1. Clone this repository:
   ```bash
   git clone git@github.com:BarryDoong/Ghibli-Style-Image-Generation.git
   cd Ghibli-Style-Image-Generation
   ```
2. Run preprocessing:
   ```bash
   python scripts/preprocess.py
   ```
3. Train the model:
   ```bash
   python train.py --data data/ --epochs 50
   ```
4. Generate styled images:
   ```bash
   python generate.py --input samples/input.jpg --output results/output.jpg
   ```

---

## 📊 Results
- Qualitative examples: comparison of input vs. Ghibli-styled output  
- Quantitative metrics (FID, SSIM, etc.) if available

(*Add screenshots here when ready!*)

---

## 👥 Team
- Barry Doong  
- Shao Jyuns  
- [Other contributors if any]

---

## 📜 License
This project is for **educational and research purposes only**.  
Studio Ghibli’s art style is copyright of **Studio Ghibli Co., Ltd.**
