# Leak Detection and Localization Project

This repository includes our fully data-driven unsupervised leak detection and localization framework in water distribution networks, employing 1D-CAE and SDNML change-point detector to realize
real-time leak detection.

## Dependencies

Python v3.8.11

Pytorch v1.8.0 cuda11.1

numpy v1.24.3

pandas v1.5.3

matplotlib v3.2.2

sklearn v1.2.2

epynet v1.1

rtchange

## Dataset

Our work is validated on the L-Town dataset. Dataset source: https://github.com/KIOS-Research/BattLeDIM

## Get Started

1. ```
   $ git clone https://github.com/Jolyne-lhy/WaterLeakDetection.git
   $ cd WaterLeakDetection
   ```

2. Install dependencies.

3. Download dataset.

4. Train and test the 1D-CAE model with `1D-CAE Trainer.ipynb` and `1D-CAE Tester.ipynb`, run `Leak detection (Change Point Detection).ipynb`  to do change point detection.

5. Run `Leak localization (impact factor).ipynb` to do localization.
