# Speaker re-identification

### Introduction 

Everyone’s voice has specific characteristics such as pitch timbre or tone, which allow us to recognize anyone’s voice as unique.
The goal of this project is to build a Deep Learning model capable of identifying whether two recordings belong to the same person.  

### The Dataset 

It is a .pkl file, containing voice sequences  and  people ids. Each  sequence  has  11025  points,corresponding to 1 second.
There is more than one sequence with the same id for every id in the set.

### Methodology

1. Perform data augmentation 
2. Extract voice features from audio 
3. Modeling using a 1-D CNN 

### Results 

| Validation set | Test set |
| ------------- | ------------- |
| 94.85%  | 84.48%  |

# Reference List  

- Badine, F. (2020) Classify speakers using Fast Fourier Transform (FFT) and a 1D Convnet. Retrieved from: https://keras.io/examples/audio/speaker_recognition_using_cnn/
- Padney, P. (2018) Music Genre Classification with Python. Retrieved from:
https://towardsdatascience.com/music-genre-classification-with-python-c714d032f0d8
- Sheng, L.M., & Edmund, M.W. (2017). Deep Learning Approach To Accent Classification.
