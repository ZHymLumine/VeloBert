# VeloBERT: DNA Sequence Translation Velocity Prediction with Transformer

This repository hosts the project for predicting translation velocity from DNA sequences.

## Environment

```bash
git clone https://github.com/ZHymLumine/VeloBERT.git
cd VeloBERT
conda create -n velobert python=3.10
conda activte velobert
conda install pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia
pip install -e .
```

## Training

```bash
cd scripts
sh train.sh
```

to use codon language model, in `train.sh`, specicy

```bash
--calm
```
