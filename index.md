## Synthesized Audio Samples

> #### Basilar membrane and otolaryngology are not auto-correlations.
<audio controls=""><source src="samples/1.wav"></audio>

> #### Scientists at the CERN laboratory say they have discovered a new particle.
<audio controls=""><source src="samples/2.wav"></audio>

> #### Donald Trump and I are great friends.
<audio controls=""><source src="samples/3.wav"></audio>

## Procedure
* Data was collected using my YouTube datascraper, [YTTTS](https://github.com/Ryan-Rudes/YTTTS)
* The dataset went through various processing steps, such as labelling audio that was probably not John Oliver speaking. The cleaned dataset has been posted on [Kaggle](https://www.kaggle.com/ryanrudes/johnoliver)
* Model was trained using [Tacotron 2](https://github.com/NVIDIA/tacotron2)

## Model Download + Kaggle Kernel
The model below was trained with a batch size of 32. The link contains all checkpoints, up to step 205,000 as of March 28, 2021. As it continues to train, new checkpoints will be uploaded to this directory and the files will appear accordingly:

* [Click here to download a model checkpoint](https://drive.google.com/drive/folders/1jj0Ktck3ZybpDzY1yzveODnh4qFSvsAl?usp=sharing)
* [Click here to train it yourself on Kaggle](https://www.kaggle.com/ryanrudes/voice-cloning-with-tacotron-2)

## Links
> [1] https://github.com/Ryan-Rudes/YTTTS \
> [2] https://github.com/NVIDIA/tacotron2 \
> [3] https://arxiv.org/abs/1712.05884 \
> [4] https://www.kaggle.com/ryanrudes/johnoliver \
> [5] https://drive.google.com/drive/folders/1jj0Ktck3ZybpDzY1yzveODnh4qFSvsAl?usp=sharing \
> [6] https://www.kaggle.com/ryanrudes/voice-cloning-with-tacotron-2
