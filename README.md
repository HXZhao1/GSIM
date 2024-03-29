# GSIM
Demo of the GAN Speech Inpainting Model for Audio Editing Software.

We provide three kinds of samples of the proposed GAN speech inpainting model for audio editing software, including Samples of 'Missing of time & frequency clips', 'Missing of random T-F areas', and 'Other additional samples in inpainting of singing voice'. An example of a previous phase reconstruction algorithm(GLA) is also provided.

For samples of 'Missing of time & frequency clips', The missing areas are clips of both time waveforms and frequency bands. For samples of 'Missing of random T-F areas', impaired spectrograms are generated by randomly masking some holes, like the example in the paper. The training model used is trained as the setting in the paper.

We also carry out an additional experiment of inpainting singing voices with the proposed model. Samples of this experiment are in 'Additional attempt in inpainting of singing voice'. Since singing voices have more harmonics than speech signals, their inpainting performance is even better than that of speech signals. This experiment provides possibilities for applying the proposed GAN inpainting model to the enhancement of singing voices, such as inpainting after voice separation, even if our attempts are preliminary.

"Example of a previous phase reconstruction algorithm(GLA)" provided an example of inpainted spectrogram and audio with a previous phase reconstruction algorithm(GLA) which has the problem of oversmoothing and buzzes. Some inpainted areas are framed out to emphasize failures (oversmoothing and buzzes) of the phase reconstruction. This example can be compared to samples with the proposed phase reconstruction algorithm in our paper.
