# IndicWhisper With JAX (70x faster)

## What is IndicWhisper?

IndicWhisper is a cutting-edge speech recognition model fine-tuned specifically for Indian languages. It boasts impressive performance on various benchmarks, outperforming other publicly available models. IndicWhisper enables accurate transcription of speech in Indian languages, facilitating tasks such as voice commands, transcription of audio files, and more.


## What is IndicWhisper-JAX?

IndicWhisper-JAX is an optimized version of IndicWhisper, leveraging the JAX  library for high-performance computing. This enhancement significantly improves the speed and efficiency of the model, making it ideal for real-time transcription tasks. IndicWhisper-JAX maintains the same level of accuracy as the original model while offering unparalleled performance, particularly on TPUs and GPUs.


## Overview

IndicWhisper achieves impressive Word Error Rates (WERs) on various benchmarks for Indian languages. It outperforms other publicly available models, making it a valuable asset for speech recognition tasks in Indian languages.

### Performance on Vistaar Benchmark (Hindi Subset)

| Model         | Kathbath | Kathbath-Hard | FLEURS   | CommonVoice | IndicTTS | MUCS         | Gramvaani | Average   |
|---------------|----------|---------------|----------|-------------|----------|--------------|-----------|-----------|
| Google STT    | 14.3     | 16.7          | 19.4     | 20.8        | 18.3     | 17.8         | 59.9      | 23.9      |
| IndicWav2vec  | 12.2     | 16.2          | 18.3     | 20.2        | 15       | 22.9         | 42.1      | 21        |
| Azure STT     | 13.6     | 15.1          | 24.3     | 14.6        | 15.2     | 15.1         | 42.3      | 20        |
| Nvidia-medium | 14       | 15.6          | 19.4     | 20.4        | 12.3     | 12.4         | 41.3      | 19.4      |
| Nvidia-large  | 12.7     | 14.2          | 15.7     | 21.2        | 12.2     | **11.8**     | 42.6      | 18.6      |
| IndicWhisper  | **10.3** | **12.0**      | **11.4** | **15.0**    | **7.6**  | 12           | **26.8**  | **13.6**  |

- For quickstat use kaggle to use IndicWhisper JAX on Kaggle.
[![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/parthiv11/indic-whisper-jax-tpu-kaggle)
  
## Why and How to Use it?

IndicWhisper-JAX offers several advantages over traditional speech recognition models:

1. **Enhanced Performance:** With JAX optimization, IndicWhisper-JAX achieves remarkable speed improvements, enabling real-time transcription of speech in Indian languages.
   
2. **Ease of Use:** Integrating IndicWhisper-JAX into your projects is seamless. With pre-trained checkpoints and straightforward API usage, you can start transcribing audio files with minimal setup.

To use IndicWhisper-JAX in your projects, simply install the necessary dependencies and load the model checkpoint using the provided API. With its superior speed and accuracy, IndicWhisper-JAX empowers developers, researchers, and government agencies to leverage the power of speech recognition in Indian languages for various applications.

## Model Hosting
[![Hugging Face Indic Whisper JAX ](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/parthiv11/indic_whisper_hi_multi_gpu)

The IndicWhisper-JAX models are hosted on Hugging Face's model hub:

- [`parthiv11/indic_whisper_hi_multi_gpu`](https://huggingface.co/parthiv11/indic_whisper_hi_multi_gpu) OR
- [`parthiv11/indic_whisper_nodcil`](https://huggingface.co/parthiv11/indic_whisper_nodcil)

Feel free to explore and utilize these models for your speech recognition tasks.

## Acknowledgements

We extend our sincere gratitude to the following individuals and organizations for their contributions and support:

- EkStep Foundation for their generous grant, which facilitated the establishment of the Centre for AI4Bharat at IIT Madras.
- The Ministry of Electronics and Information Technology (NLTM) for its grant to support the creation of datasets and models for Indian languages under the Bhashini project.
- The Centre for Development of Advanced Computing, India (C-DAC), for providing access to the Param Siddhi supercomputer for training our models.
- Microsoft for its grant to create datasets, tools, and resources for Indian languages.
- Contributors: Kaushal Bhogale, Sai Narayan Sundaresan, Abhigyan Raman, Tahir Javed, Mitesh Khapra, Pratyush Kumar.

## Contributing

We welcome contributions from the community to further improve IndicWhisper. If you have any ideas, bug fixes, or enhancements, please feel free to submit a pull request.

Thank you for your interest in IndicWhisper! We hope it proves to be a valuable tool for your speech recognition needs in Indian languages.
