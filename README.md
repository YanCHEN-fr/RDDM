# RDDM: Practicing RAW Domain Diffusion Model for Real-world Image Restoration
The official implementation  for "RDDM: Practicing RAW Domain Diffusion Model for Real-world Image Restoration"

> **RDDM: Practicing RAW Domain Diffusion Model for Real-world Image Restoration** <br>
<div>
    Yan Chen<sup>1,†</sup>&emsp;
    Yi Wen<sup>1†</sup>&emsp;
    Wei Li<sup>1</sup>&emsp;
    Junchao Liu<sup>1</sup>&emsp;
    Yong Guo<sup>2</sup>&emsp;
    Jie Hu<sup>1</sup>&emsp;
    Xinghao Chen<sup>1</sup>&emsp;
</div>

<div>
    <sup>1</sup>Huawei Noah’s Ark Lab, <sup>2</sup>Max Planck Institute for Informatics <br/>
</div>

> **Abstract:**
## News
- [2025.11] This repo is created.

## Dependencies & Installation
Please refer to the following simple steps for installation.
```
git clone https://github.com/YanCHEN-fr/RDDM.git
cd RDDM
conda create -n RDDM python=3.10 -y
conda activate RDDM
pip install -r requirements.txt
```

## Datasets

## Training
```
cd RDDM
bash train.sh
```

## Test
```
bash test.sh
```

## Results
<details>
<summary>Quantitative Comparisons (click to expand)</summary>

<!-- <p align="center">
  <img src="./figs/light.png">
</p> -->
</details>

<details>
<summary>Visual Comparisons (click to expand)</summary>

<!-- <p align="center">
  <img src="./figs/vis.png">
</p> -->
</details>

## Acknowledgement

This work is released under the Apache 2.0 license.
 The codes are based on [OSEDiff](https://github.com/cswry/OSEDiff), [Unprocess](https://github.com/timothybrooks/unprocessing) Please also follow their licenses. Thanks for their awesome works.
