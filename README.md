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
3. Modeling using a 1-d CNN 

### Results 

| Validation set | Test set |
| ------------- | ------------- |
| 94.85%  | 84.48%  |
