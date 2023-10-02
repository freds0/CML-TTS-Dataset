# CML-TTS: A Multilingual Dataset for Speech Synthesis in Low-Resource Languages

In this paper, we present CML-TTS, a recursive acronym for CML-Multi-Lingual-TTS, a new Text-to-Speech (TTS) dataset developed at the Center of Excellence in Artificial Intelligence (CEIA) of the Federal University of Goias (UFG). CML-TTS is based on Multilingual LibriSpeech (MLS) and adapted for training TTS models, consisting of audiobooks in seven languages: Dutch, French, German, Italian, Portuguese, Polish, and Spanish. Additionally, we provide the YourTTS model, a multi-lingual TTS model, trained using 3,176.13 hours from CML-TTS and also with 245.07 hours from LibriTTS, in English. Our purpose in creating this dataset is to open up new research possibilities in the TTS area for multi-lingual models. The dataset is available for download at [https://freds0.github.io/CML-TTS-Dataset/](https://freds0.github.io/CML-TTS-Dataset/) under the CC-BY 4.0 license.


## Download
To download the CML-TTS dataset, [click here]([https://librivox.org/](https://drive.google.com/drive/folders/1qIpZfvgoj8HGZxKmDNoMYelbad0VEI7H?usp=sharing)).

You can download each version separately:

- [CML-TTS Dataset Dutch](https://drive.google.com/file/d/12L9vuj4pGsX-Ivyu6FHmygGP8FtbN0Wo/view?usp=sharing)
- [CML-TTS Dataset French](https://drive.google.com/file/d/1o5xJBFPWaMsjBpOrHDEGta4bVxNw7Ikx/view?usp=share_link)
- [CML-TTS Dataset German](https://drive.google.com/file/d/1gny1W_SEdebT0W2LgIps3u2GGQPQ9kbS/view?usp=share_link)
- [CML-TTS Dataset Italian](https://drive.google.com/file/d/19-N1MG__mnve8rRXCfDjwB2xrWiIM4KH/view?usp=sharing)
- [CML-TTS Dataset Polish](https://drive.google.com/file/d/1tMqT6CEYX3x_iyech7mcO22dMlp-sBLx/view?usp=share_link)
- [CML-TTS Dataset Portuguese](https://drive.google.com/file/d/1KxwG0o6MwWq_hKUzeRGwZOx1HxMNfFMB/view?usp=share_link)
- [CML-TTS Dataset Spanish](https://drive.google.com/file/d/18Nw5IDusZwGJA7MhFpSFwBl8CDLPLY90/view?usp=share_link)

An alternative repository for download can be accessed [in this link](https://ufmtbr-my.sharepoint.com/:f:/g/personal/fredoliveira_ufmt_br/Ei8ztD2EsqdAiyQNEnXDHZMBW1BS_q0AD1EehRS1_m5xfQ).

The segments files are available at [Google Drive](https://drive.google.com/file/d/102DxVPyR9VgRFIZaFtEHJ3u_YAW9ZnEq/view?usp=sharing) and [One Drive](https://ufmtbr-my.sharepoint.com/:u:/g/personal/fredoliveira_ufmt_br/EScW5_fYuvtIslONTsyYJhsBiu8nzWwjDRFmMc8qBrpa7g?e=Ebrnrh).

After downloading check the md5sum of each file:
```
56e11612ffea33282eced3d499cbb1ca  cml_tts_dataset_dutch_v0.1.tar.bz
410f8e144fa1a5c8e771b08b2e555a9b  cml_tts_dataset_french_v0.1.tar.bz
263782ee31981b101c29d09b058361e2  cml_tts_dataset_german_v0.1.tar.bz
bb6160b8ee968ac8caa5a32ec4bd91ba  cml_tts_dataset_italian_v0.1.tar.bz
88e6ead2d4df5f29e080d7cd37dcdbdd  cml_tts_dataset_polish_v0.1.tar.bz
8c877a4be0eb41f275497609df5a114c  cml_tts_dataset_portuguese_v0.1.tar.bz
afdd6c348d8d1ee693ea7fcf2ea57b9c  cml_tts_dataset_spanish_v0.1.tar.bz
f529a908aba26a6d891b4fb17ab3125b  cml_tts_dataset_segments_v0.1.tar.bz
```
## Statistics

CML-TTS is a dataset comprising audiobooks sourced from the public domain books of [Project Gutenberg](https://www.gutenberg.org/), read by volunteers from the [LibriVox](https://librivox.org/) project. The dataset includes recordings in Dutch, German, French, Italian, Polish, Portuguese, and Spanish, all at a sampling rate of 24kHz. The following figure shows pie charts indicating the percentage of each language's duration (on the left), sample quality percentage (in the center), and the percentage of speakers' gender (on the right).

![](img/cml_tts_pieplot.png)

The table below displays the total duration of each language subset present in the CML-TTS dataset, as well as the duration of the Train, Test, and Dev sets. Additionally, the table provides the duration of the sets categorized by speaker gender.

![](img/cml_tts_statistics.png)

## Audio Samples

To listen to samples from all the languages available in the CML-TTS dataset, as well as hear the YourTTS model trained using CML-TTS in conjunction with LibriTTS, please visit our website [https://freds0.github.io/CML-TTS-Dataset/](https://freds0.github.io/CML-TTS-Dataset/).

## Citation

```
@InProceedings{Cmltts2023,
    title="CML-TTS: A Multilingual Dataset for Speech Synthesis in Low-Resource Languages",
    author="Oliveira, Frederico S. and Casanova, Edresson and Junior, Arnaldo Candido and Soares, Anderson S. and Galv{\~a}o Filho, Arlindo R.", 
    editor="Ek{\v{s}}tein, Kamil and P{\'a}rtl, Franti{\v{s}}ek and Konop{\'i}k, Miloslav",
    booktitle="Text, Speech, and Dialogue",
    year="2023",
    publisher="Springer Nature Switzerland",
    address="Cham",
    pages="188--199",
    isbn="978-3-031-40498-6"
}
```
