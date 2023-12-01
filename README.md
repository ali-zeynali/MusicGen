# Music Generation using Deep Learning and LSTM

This repository contains code for generating music using deep learning techniques, particularly Long Short-Term Memory (LSTM) networks. The model is trained on a dataset of music samples and is capable of generating new musical sequences. The code is written based on the project published on [Kaggle](https://www.kaggle.com/code/karnikakapoor/music-generation-lstm/notebook).

## Overview

The primary goal of this project is to explore the use of LSTM networks in generating music. The model is trained on a dataset of MIDI files (or any suitable music format) and learns to produce new music sequences in a similar style.

## Clone the project
```bash
git clone https://github.com/ali-zeynali/MusicGen.git
```
```bash
cd MusicGen
```
## Prepare dataset
Uzip dataset.zip into dataset folder.
## Requirements

To run the code in this repository, you'll need:
- Python (>=3.6)
- NumPy (>= 1.24.1)
- TensorFlow (>=2.13)
- Keras (>= 2.13)
- music21 (>= 8.3)

You can install the required dependencies via pip. For example:

```bash
python -m pip install numpy
python -m pip install tensorflow numpy
python -m pip install keras
python -m pip install music21
```
or simpy run:
```bash
python -m pip install -r requirements.txt
```

## Usage
The code is written in Jupyter-notebook environment under Python 3.x version. Simpy run command below to open jupyter-notebook:
```bash
python -m notebook
```