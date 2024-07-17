# Roadmap

- ❌ : Not implemented at all yet.
- 🟨 : Script exists but sill needs work.
- ✅ : Implemented and useable.

1. [General](#general)
- [Feature extraction](#feature-extraction)
- [Audio analysis](#audio-analysis)
- [Image analysis](#image-analysis)
- [Video analysis](#video-analysis)
- [Classification](#classification)
- [Storage](#storage)
- [Scraping](#scraping)
2. [Workflows](#workflows)
- [Distant viewing](#distant-viewing)

## General

### Feature extraction

|Process               |References            |Colab                 |Anaconda              |
|----------------------|----------------------|----------------------|----------------------|
|dps|[implementation](https://github.com/jdchart/dps), [article]()|[❌]()|[✅](/jupyter/general/feature_extraction/vosk_speech_recognition_features.ipynb)|
|Audio descriptors|[IRCAM](http://recherche.ircam.fr/anasyn/peeters/ARTICLES/Peeters_2003_cuidadoaudiofeatures.pdf), [article]()|[❌]()|[❌]()|
|Image embeddings||[❌]()|[❌]()|

### Audio Analysis

|Process               |References            |Colab                 |Anaconda              |
|----------------------|----------------------|----------------------|----------------------|
|Speech Recognition|[wikipedia](https://en.wikipedia.org/wiki/Speech_recognition), [vosk](https://alphacephei.com/vosk/)|[✅](/colab/general/audio_analysis/vosk_speech_recognition.ipynb)|[✅](/jupyter/general/audio_analysis/vosk_speech_recognition.ipynb)|

### Image Analysis
|Process               |References            |Colab                 |Anaconda              |
|----------------------|----------------------|----------------------|----------------------|
|Face detection||[❌]()|[❌]()|
|Pose detection||[❌]()|[❌]()|
|Object detection||[❌]()|[❌]()|

### Video Analysis
|Process               |References            |Colab                 |Anaconda              |
|----------------------|----------------------|----------------------|----------------------|
|Shot detection||[❌]()|[❌]()|
|Object tracking||[❌]()|[❌]()|

### Classification

|Process               |References            |Colab                 |Anaconda              |
|----------------------|----------------------|----------------------|----------------------|
|MLP Classification|[scikit learn](https://scikit-learn.org/stable/modules/neural_networks_supervised.html)|[❌]()|[❌]()|

### Storage

|Process               |References            |Colab                 |Anaconda              |
|----------------------|----------------------|----------------------|----------------------|
|Adding media to Arvest||[🟨](/colab/general/storage/adding_media_to_arvest.ipynb)|[❌]()|
|Batch adding media to Arvest||[🟨](/colab/general/storage/batch_adding_media_to_arvest.ipynb)|[❌]()|

### Scraping

|Process               |References            |Colab                 |Anaconda              |
|----------------------|----------------------|----------------------|----------------------|
|Web scraping||[❌]()|[❌]()|
|Nakala API||[❌]()|[❌]()|
|Heurist API||[❌]()|[❌]()|

## Workflows

### Distant viewing

|Process               |References            |Colab                 |Anaconda              |
|----------------------|----------------------|----------------------|----------------------|
|Image embedding projection using distant viewing toolkit|[dvt](https://github.com/distant-viewing/dvt)|[🟨](/colab/workflows/distant_viewing/image_embeddings_projection.ipynb)|[❌]()|