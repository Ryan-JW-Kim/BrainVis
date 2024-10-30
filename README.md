# BrainVis

This project is an ongoing effort to self-teach and explore strategies for utilizing EEG brain signal data within pytorch

While working on this project I am also writing regular development logs to explain my findings, and improve my technical communication skills.

Data used in the BrainVis project will be sourced from the MindBigData dataset where each example is three seconds long covering 5 channels from the commercial EEG headset the Emotiv Insight. Data was collected from a single subject David Vivancos who viewed images from ILSVRC2013 a public dataset for an image recognition challenge whos data can be downloaded from Kaggle.

## Goals

#### EEG Auto Encoding (IN PROGRESS)

Create a model based off image autoencoders to recontruct EEG signal samples.

#### Image reconstruction (PLANNED)

Attempt to reconstruct images viewed by the subject based on the representation created by the autoencoder.

Realistically impossible due to the signal to noise ratio of EEG but I will still make an effort.

I may also try to agressibley 

#### Image classification (PLANNED)
