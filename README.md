# BANK_NOTE_AUTHENTICATION USING TENSORFLOW
This code is done for training a classifier that detects fake notes from a given set of images(of currency notes).


## OVERVIEW

I built a multilayered perceptron that classifies fogred and original notes using <a 
href='https://www.tensorflow.org/'>TENSORFLOW</a> library.
i used <a href='http://scikit-learn.org/stable/'>Scikit-learn</a> to preprocess the data.
INPUTS:numerical values that include image variance,skewness,curtosis and entropy.
OUTPUTS:binary values(0 or 1) 


## SOFTWARE DEPENDENCIES

~numpy
~pands
~Scikit-learn
~Tensorflow
 Install dependencies using <a href='https://pip.pypa.io/en/stable/'>pip</a>

## DATA set

The data set was taken from the <a href='https://archive.ics.uci.edu/ml/datasets/banknote+authentication'>UCI Repository</a>
it contain 1,372 banknotes(observations) and 4 attributes.

NOTE:***the numerical values in the dataset are extracted from the Wavelet Transformed Images(WTI) of bank_note specimens***
defining the features termed as input and output 
        COLUMN     |      DEFINITION
 __________________|_________________________
   Image.Var       |     Variance of WTI
   Image.Skew      |     Skewness of WTI
   Image.Curt      |      Curtosis of the WTI
   Entropy         |      Entropy of the Image
   Class           |      Authenticity of note
 
 ## RUNNING ENVIRONMENT
 Run the notebook on a localhost server using `jupyter notebook`.
 ENVIRONMENT:Tensorflow