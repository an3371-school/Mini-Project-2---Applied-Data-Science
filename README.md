# Mini Project 2: Dictyostelium Aggregation Center Prediction

## Project Overview
This project predicts where *Dictyostelium discoideum* cells will aggregate by analyzing early temporal dynamics from microscopy time-lapse videos.

## Links

### 📊 Project Report
[View Full Write-up (Google Drive)](https://drive.google.com/file/d/1Zu9gcGj4sy81HLlXjEaieXBShy6q4Jr0/view?usp=sharing)

### 💻 Code Implementation
[Open in Google Colab](https://colab.research.google.com/drive/1jyOYaWKrE3dveWd4vrbHsdwoKHtQwmbG?usp=sharing)

## Quick Start

1. Click the Colab link above
2. Make a copy to your own Google Drive (File → Save a copy in Drive)
3. Run all cells to reproduce results

## Project Structure

- **Models Implemented:**
  - Conv3D baseline (deep learning)
  - Gaussian Mixture Model (probabilistic clustering)
  - Poisson Hotspot detector (statistical baseline)

- **Key Finding:** Only **4 consecutive frames** are needed to accurately predict aggregation centers

## Requirements

See the Colab notebook for full dependency list. Main libraries:
- PyTorch
- scikit-learn
- numpy
- matplotlib

## Data

Data is confidential (provided by Janelia HHMI) and not included in this repository.

## Author

ANIQA NAYIM
Applied Data Science Course
[Your University/Program Name]

## Acknowledgments

Data provided by Allyson Sgro and Jennifer Hill from Janelia HHMI.
