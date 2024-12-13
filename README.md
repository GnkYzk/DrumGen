# DrumGen
An AI model project on generating drum sounds

The project is aimed at getting a guitar sound of 30s as input and generating a drum sound that would musically fit it.

For now the model is able to understand and capture the ryhthm, but unable to recreate the original values. I believe the reason is the low amount of data. I downloaded Slakh2100 dataset for training, that I will do in the near future.


A VAE with LSTMs and CNNs in the encoder, and ConvTransposes in the decoder is used. The data are turned into melspectograms to be put in the model. 
