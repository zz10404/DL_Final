# DL_Final CNN vs. Transformer for Remote Sensing Change Detection

**NYU MSCS Deep Learning – Final Project**

**Author**: Zhongrui Zhao (zz10404)

## Overview

A comparative study of three change detection models on the LEVIR-CD dataset:
- FC-Siam-Diff (CNN baseline)
- SNUNet (CNN with attention)
- BIT (Transformer-based)

## Project Files

📁 **Google Drive**: [https://drive.google.com/drive/folders/1kLDa_Pw5o7DygWni-pHrzaNcCK0ntjE9?usp=sharing]
```
ChangeDetection/
├── final_change_detection_project.ipynb
├── data/
│   ├── LEVIR-CD/                          # Original dataset
│   ├── LEVIR-CD-256/                      # Cropped 256x256 patches
│   ├── train.zip
│   ├── val.zip
│   └── test.zip
└── checkpoints/
    ├── FCSiamDiff_best.pth                # Model weights
    ├── SNUNet_best.pth
    ├── BIT_best.pth
    ├── evaluation_results.json            # Quantitative results
    ├── FC_Siam_Diff_training_history.png  # Training curves
    ├── SNUNet_training_history.png
    ├── BIT_training_history.png
    ├── scale_analysis.png                 # Analysis plots
    ├── edge_comparison.png
    ├── predictions_comparison.png
    └── finalresult_summary.png
```

## Environment

Google Colab with A100 GPU, PyTorch 2.0+

https://drive.google.com/drive/folders/1kLDa_Pw5o7DygWni-pHrzaNcCK0ntjE9?usp=sharing
