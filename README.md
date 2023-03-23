# CML-TTS: A Multilingual Dataset for Speech Synthesis in Low-Resource Languages

In this paper, we present CML-TTS, a recursive acronym for CML-Multi-Lingual-TTS, a new Text-to-Speech (TTS) dataset developed at the Center of Excellence in Artificial Intelligence (CEIA) of the Federal University of Goias (UFG). CML-TTS is based on Multilingual LibriSpeech (MLS) and adapted for training TTS models, consisting of audiobooks in seven languages: Dutch, French, German, Italian, Portuguese, Polish, and Spanish. Additionally, we provide the YourTTS model, a multi-lingual TTS model, trained using 3,176.13 hours from CML-TTS and also with 245.07 hours from LibriTTS, in English. Our purpose in creating this dataset is to open up new research possibilities in the TTS area for multi-lingual models. The dataset is available for download at [https://github.com/freds0/CML-TTS-Dataset](https://github.com/freds0/CML-TTS-Dataset) under the CC-BY 4.0 license.

## Statistics

CML-TTS is a dataset comprising audiobooks sourced from the public domain books of [Project Gutenberg](https://www.gutenberg.org/), read by volunteers from the [LibriVox](https://librivox.org/) project. The dataset includes recordings in Dutch, German, French, Italian, Polish, Portuguese, and Spanish, all at a sampling rate of 24kHz. The following figure shows pie charts indicating the percentage of each language's duration (on the left), sample quality percentage (in the center), and the percentage of speakers' gender (on the right).

![](img/cml_tts_pieplot.png)

The table below displays the total duration of each language subset present in the CML-TTS dataset, as well as the duration of the Train, Test, and Dev sets. Additionally, the table provides the duration of the sets categorized by speaker gender.

![](img/cml_tts_statistics.png)

## Audio Samples

To listen to samples from all the languages available in the CML-TTS dataset, as well as hear the YourTTS model trained using CML-TTS in conjunction with LibriTTS, please visit our website [https://freds0.github.io/CML-TTS-Dataset/](https://freds0.github.io/CML-TTS-Dataset/).
