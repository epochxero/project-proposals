## Biosignal Forecasting Through Temporal Difference Learning and Prediction

### Summary:
This project aims to learn the representation of biosignals, in particular Electrocardiogram, to identify outliers or abberations present in illnesses. Biosignal data is notoriously noisy and the value inherent in being able to predict future states of the data. Most time series forecasting methods to date are based on recurrent network architectures with a notable exception being the work using tthe Seq2Seq model of timeseries prediction. 

This research would draw on two recent papers as primary sources. The paper, "Variational Autoencoders and Nonlinear ICA:A Unifying Framework" describes the use of Variational Autoencoders to identify deep latent variables to reconstruct time series data with the paper reporting state of the art results on this task. The work "Temporal Difference Variational Auto-Encoder" describes a reinforcement learning technique for the creation of a "generative sequence model that learns representations containing explicit beliefs about states several steps into the future, and that can be rolled out directly without single step transitions." 

To put the project proposal succinctly, the previously mentioned methods will be used to predict a signal state in the future. With the ability to predict future states based on these predictions a neural network classifier could be used to analyze these future signals to recognize any potential issues.

The likely dataset to be used in this work will be The PTB Diagnostic ECG Database (https://physionet.org/physiobank/database/ptbdb/).

### Areas of Study
Biosignal Analysis, Reinforcement Learning, Variational Autoencoders, Latent Variable Representation, Time Series Classification

### Minimum Required Skills
Python with an emphasis on Deep Learning frameworks, Biosignal processing, Variational Autoencoders and Reinforcement Learning techniques (particularly temporal difference learning)

### List of Interested Parties
Sanjay(Participant)
