# Illustration
1) Training: We train an LSTM model on Sine wave
2) Testing: We extrapolate and predict the upcoming waveform after a given input

# Model & Architecture
1) LSTM DL Model
2) Number of layers "depth" = 2
3) Number of hidden layers  = 16
4) Used around 6 complete waveforms in the training
5) MSE Loss

# Results
1) Bad Results: the sine waveform predicted was not matching the original sine wave frequency
2) Good Results: the sine waveform amplitude is matching the original amplitude

# Conclusions: We can try different solutions in future to fix the results
1) Increase sequence length provided 
2) Increase the number of layers and hidden layers
3) We can try combining the lstm with a fourier transform
4) We can try other regularization techniques
5) I can read papers to come up with different solutions if above solutions did not solve it
