# Source code for "Try this model to quickly tell if it is a faulty motor by listening"
The repo contains the trainig data located in the data folder and a jupyter notebook for the tutorial.

You may also read my [write up](https://www.dlology.com/blog/try-this-model-to-quickly-tell-if-it-is-a-faulty-motor-by-listening/) for more detail.
## Updates
10/24/2017
You might also be interested in using MFCC feature as input to imporve audio classifier accuracy, read my write up [here](https://www.dlology.com/blog/one-simple-trick-to-improve-the-motor-acoustic-classifier/).

Tested with Python 3.5
## Dependencies

 numpy, pickle, tensorflow, scipy, pylab, sklearn, librosa


### How to Run
Run the python notebook by cd into the directory in command line then run
```
jupyter notebook
```
Select either of those in the browser
**Acoustic_TF_LSTM_MFCC.ipynb** model input is MFCCs
**Acoustic_TF_LSTM.ipynb** model input is audio time series

Enjoy, leave a comment in my [blog post](https://www.dlology.com/blog/try-this-model-to-quickly-tell-if-it-is-a-faulty-motor-by-listening/) if you have any question.