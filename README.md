#Deep Lip Read
---

>## What is Deep Lip Read(DLR)?
>- Deep Lip Read is Tensorflow and OpenCV -powered *deep learning model*, convert Lip movement to Sentence.
>- It is extension of *Sign Language Detection*.
>- *Sign Language Detection* is Deep Learning Model, which is use to precieve what one is trying to say by his/her action.
>- What Deep Lip Read is doing here is that, it is capturing his/her lip movement, and by this *lip movement* we can predict what one is saying. 

## Dependencies
- Tensorflow
- OpenCV
- Keras
- ImageIO
- Gdown
- Matplotlib
- Numpy


## Installation & Usage
First you need to clone this repo using:
```
git clone https://github.com/kodedriller/Deep-Lip-Read.git
```
Then install packages using:
```
pip install opencv-python matplotlib imageio gdown tensorflow
```
**Note:** if you don't want to have CUDA,you have to use ``tensorflow`` instead of ``tensorflow-gpu``.

Now open terminal/bash/cmd to run the notebook using:
```
jupyter-lab
or
jupyter notebook
```

## Specialty
- Usage of Grid dataset
- Data Pipelines
- Convert any video format to gif format as output
- Generated subtitles for spoken words
- Helps in places where there is no sound in video

## Accuracy
```
Afte 100 epochs accuracy was 85.63
```

## Dataset
To download dataset manually:
```
https://drive.google.com/uc?id=1DNcR4xtVbWmlkqg_EWFhrc47POD2TGIh
```
For prediction data:
```
https://drive.google.com/uc?id=18QHjkLLF1Xr6hjDBW-9GXfK5DYBYD_kn
https://drive.google.com/uc?id=1oU63GpO0lhkdfPE6tDr_oVGFaKDwGy5G
```
## Upcoming[Pending]
- Fullstack app
- Realtime prediction

## References
This Deep Lip Read project was inspired from the paper '**LipNet: End-to-End Sentence-level Lipreading**' by Yannis M. Assael, Brendan Shillingford, Shimon Whiteson, and Nando de Freitas.

```
https://arxiv.org/abs/1611.01599
```