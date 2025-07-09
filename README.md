# Holstein-Incremental-ID

This repository supports the paper “Enhanced Wavelet-Convolution and Few-Shot Prototype-Driven Framework for Incremental Identification of Holstein Cattle,” and provides the dataset along with download scripts.

## 1. Project Overview

- **Task**: Few-shot incremental identification of Holstein cattle based on back-pattern images  
- **Method**: ResWTA feature extractor (ResNet + WTAConv) combined with a few-shot prototype network  
- **Performance**: Closed-set Top-1 accuracy of 97.43 %; incremental identification accuracy of 94.33 % (average incremental accuracy 95.1 %)

## 2. Dataset

- **Download Instructions**:  
  1. The full dataset (including labels) is scheduled for release in June 2026.  
  2. After release, run `scripts/download_data.py` to download all files.

- **Dataset Details**:  
  - Total images: 46 158  
  - Number of individuals: 302 Holstein cows  
  - Distribution: Long-tail, containing both few-shot and many-shot classes  
