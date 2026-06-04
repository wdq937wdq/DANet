# DANet

Official implementation of **DANet: Degradation-Aware Visual Understanding for Ancient Murals**.

## Overview

DANet is a degradation-aware visual understanding framework designed for ancient mural analysis. The proposed architecture enhances feature representation in degraded regions and can be flexibly applied to both mural element detection and damage segmentation tasks.


## Environment

### Requirements

* Python 3.9.25
* PyTorch 2.1.0
* CUDA 12.1
* Ultralytics 8.3.0

### Installation

Clone the repository:

```bash
git clone https://github.com/yourname/DANet.git
cd DANet
```

Create a virtual environment (optional):

```bash
conda create -n danet python=3.10
conda activate danet
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Training

```bash
python train.py
```

or

```bash
yolo train model=cfg/models/danet/danet.yaml data=data.yaml
```

## Validation

```bash
python val.py
```

## Inference

```bash
python predict.py
```

