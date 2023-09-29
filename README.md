# Viterbi_Algorthim
We use the Viterbi Algorithm to decode an English sentence from a long sequence of non-text observations. To do so, we will implement the same basic algorithm used in most engines for automatic speech recognition.
In a speech recognizer, these observations would be derived from real-valued measurements of acoustic waveforms. Here, for simplicity, the observations only take on binary values, but the high-level concepts are
the same. Project completed as part of homework 7 of CSE 250A of UCSD, CSE, Fall 2022.

# Task: 
For a detailed description of the model and tasks in this project, please refer to the file 'Problem statement.pdf'. Briefly, we consider a discrete HMM (Hidden Markov Model) with 27 hidden states and binary observations. With the data files pointed out below, we get the parameter value for the initial state distribution, transition matrix, observations, and emission matrix. We use the Viterbi algorithm to compute the most probable sequence of hidden states conditioned on this particular sequence of observations. To check our answer: suppose that the hidden states {1, 2, . . . , 26} represent the letters {a, b, . . . , z} of the
English alphabet, and suppose that hidden state 27 encodes a space between words. If we have implemented the Viterbi algorithm correctly, the most probable sequence of hidden states (ignoring repeated elements)
will reveal a famous quotation, as well as an interesting commentary on our times.

# Files :
1. emissionMatrix.txt: emission matrix data. 
2. initialStateDistribution.txt: initial state distribution data.
3. observations.txt: observation data.
4. transitionMatrix.txt: transition matrix data.  
5. Problem Statement.pdf: The detailed problem statement with each part/task is indicated and we also give a sample solution of the tasks stated. 
6. code.ipynb: The code to solve the problem as given in 'Problem Statement.pdf'.

# Execution :
Execute code.ipynb notebook sequentially to see the outputs and the decoded English sentence at the end.

