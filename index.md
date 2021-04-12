## Synthesized Audio Samples

> Basilar membrane and otolaryngology are not auto-correlations.
<audio controls=""><source src="samples/1.wav"></audio>

> Scientists at the CERN laboratory say they have discovered a new particle.
<audio controls=""><source src="samples/2.wav"></audio>

> Donald Trump and I are great friends.
<audio controls=""><source src="samples/3.wav"></audio>

> Peter Piper picked a peck of pickled peppers. How many pickled peppers did Peter Piper pick?
<audio controls=""><source src="samples/4.wav"></audio>

> To cancel the payment, press one; or to continue, two.
<audio controls=""><source src="samples/5.wav"></audio>

> Performance reviews are stressful, time-consuming, and often meaningless.
<audio controls=""><source src="samples/6.wav"></audio>

> A nuclear weapon improvised from radioactive nuclear waste material and conventional explosives.
<audio controls=""><source src="samples/7.wav"></audio>

> Tina Fey's children are Alice Zenobia Richmond and Penelope Athena Richmond.
<audio controls=""><source src="samples/8.wav"></audio>

> Deny thy father and refuse thy name.
<audio controls=""><source src="samples/9.wav"></audio>

> Life is like a box of chocolates. You never know what you're gonna get.
<audio controls=""><source src="samples/10.wav"></audio>

> Prepare to make a right in 500 feet
<audio controls=""><source src="samples/11.wav"></audio>

> Sally sells seashells by the seashore. The shells she sells are seashells I'm sure
<audio controls=""><source src="samples/12.wav"></audio>

> My show is a total disaster
<audio controls=""><source src="samples/13.wav"></audio>

#### Compare Real to Generated Audio

> why not use the time to register to vote
<table>
  <thead>
    <tr>
      <th>Real</th>
      <th>Fake</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><audio controls=""><source src="samples/comparisons/1/real.wav" type="audio/wav"></audio></td>
      <td><audio controls=""><source src="samples/comparisons/1/fake.wav" type="audio/wav"></audio></td>
    </tr>
  </tbody>
</table>

> it's not a great sign for your case when
<table>
  <thead>
    <tr>
      <th>Real</th>
      <th>Fake</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><audio controls=""><source src="samples/comparisons/2/real.wav" type="audio/wav"></audio></td>
      <td><audio controls=""><source src="samples/comparisons/2/fake.wav" type="audio/wav"></audio></td>
    </tr>
  </tbody>
</table>

## Procedure
* Data was collected using my YouTube datascraper, [YTTTS](https://github.com/Ryan-Rudes/YTTTS)
* The dataset went through various processing steps, such as labelling audio that was probably not John Oliver speaking. The cleaned dataset has been posted on [Kaggle](https://www.kaggle.com/ryanrudes/johnoliver)
* Model was trained using [Tacotron 2](https://github.com/NVIDIA/tacotron2)

## Model Download + Kaggle Kernel
The model below was trained with a batch size of 32. The link contains all checkpoints saved throughout training. As it continues to train, new checkpoints will be uploaded to this directory and the files will appear accordingly:

* [Click here to download a model checkpoint](https://drive.google.com/drive/folders/1jj0Ktck3ZybpDzY1yzveODnh4qFSvsAl?usp=sharing)

<iframe src="https://drive.google.com/embeddedfolderview?id=1jj0Ktck3ZybpDzY1yzveODnh4qFSvsAl#grid" style="width:100%; height:600px; border:0;"></iframe>

* [Click here to train it yourself on Kaggle](https://www.kaggle.com/ryanrudes/voice-cloning-with-tacotron-2)

## Links
> [1] https://github.com/Ryan-Rudes/YTTTS \
> [2] https://github.com/NVIDIA/tacotron2 \
> [3] https://arxiv.org/abs/1712.05884 \
> [4] https://www.kaggle.com/ryanrudes/johnoliver \
> [5] https://drive.google.com/drive/folders/1jj0Ktck3ZybpDzY1yzveODnh4qFSvsAl?usp=sharing \
> [6] https://www.kaggle.com/ryanrudes/voice-cloning-with-tacotron-2
