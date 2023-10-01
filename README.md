# MaskCycleGAN-VC

This is an implementation of Kaneko et al.'s MaskCycleGAN-VC model for non-parallel voice conversion in Filipino language using Python and WSL2 (https://github.com/GANtastic3/MaskCycleGAN-VC). 

The training uses the VCC2018 dataset which has approximately 80 sentences uttered each from 6 males and 6 females. The training consumed 150GB of storage and due to machine limitations, only 3700 out of 6172 epochs recorded were saved. All codes are available using the repository given above. 

The performance of the converted audio files resampled at 16 kHz from MaskCycleGAN-VC was assessed against the baseline system of the ASR which produced a WER of **17.26%**—a 16.86% relative improvement from the baseline system's WER of 20.76%.
