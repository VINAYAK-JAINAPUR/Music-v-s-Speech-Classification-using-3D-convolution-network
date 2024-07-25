# Music vs Speech Classification Using 3D CNN

## Overview

This project presents a novel approach for classifying audio signals as either music or speech using a three-dimensional Convolutional Neural Network (3D CNN). By leveraging 3D representations of mel-spectrograms, the model captures intricate temporal and spectral features, enhancing classification accuracy for applications in Automatic Speech Recognition (ASR) and Music Information Retrieval (MIR) systems.

## Abstract

In the context of rapid technological advancements, accurate classification of audio signals remains a significant challenge. This project introduces a 3D CNN-based model for the subtle classification of music versus speech. Unlike traditional methods, this model employs 3D representations of mel-spectrograms, demonstrating an innovative approach to capturing the complex temporal and spectral features inherent in audio signals.

## Keywords

- 3D Spectrogram
- Mel Spectrogram
- 3D CNN
- Convolutional Neural Network
- Audio Classification

## Introduction

The audio industry significantly impacts entertainment, telecommunications, and various other fields. Audio classification is crucial for ASR and MIR systems. This project aims to develop a robust model that can accurately classify audio signals into music and speech categories, thereby improving human-computer interaction through voice commands and enhancing music recognition models.

## Previous Works

Previous approaches to audio classification include:
- Feature-Based Approaches (e.g., Power Normalized Cepstral Coefficients)
- Time-Domain, Frequency-Domain, and Time-Frequency Domain Approaches
- Machine Learning and Deep Learning Methods (e.g., K-means clustering, Multi-Layer Perceptron, Empirical Mode Decomposition)

These methods have various levels of accuracy and computational complexity. The proposed 3D CNN model aims to address the limitations of traditional feature extraction methods and manual feature engineering.

## Proposed Methodology

The proposed methodology involves the following key steps:

1. **Data Collection**: 
   - Gtzan Music Genre Collection: 1,000 audio tracks representing 10 different music genres.
   - LibriSpeech: 1,000 hours of read English speech, randomly selected 1,000 audio files.

2. **Feature Extraction**:
   - Preprocessing audio data for uniformity and reduced computational overhead.
   - Computation of mel-spectrograms using the Python library Librosa.
   - Conversion of mel-spectrograms into 3D representations by segmenting them into multiple 2D arrays.

3. **Model Architecture**:
   - A 3D CNN model built using TensorFlow and Keras.
   - Consists of 2 convolution layers with batch normalization and dropout layers.
   - Fully connected layers followed by a softmax activation function for binary classification.

## Experimentation and Results

The proposed 3D CNN model was trained and validated on the combined dataset. The results demonstrated the model's ability to effectively classify audio signals as music or speech, showcasing the potential of 3D spectrograms in capturing spatiotemporal features for improved classification accuracy.

## Conclusion

This project highlights the effectiveness of using 3D CNNs and 3D mel-spectrograms for audio classification. The proposed model offers a significant improvement over traditional methods, providing a robust framework for future research and applications in ASR and MIR systems.

## References

1. Triantafyllos Afouras, Joon Son Chung, Andrew Senior, Oriol Vinyals, and Andrew Zisserman. Deep audio-visual speech recognition. IEEE transactions on pattern analysis and machine intelligence, 44(12):8717–8727, 2018.
2. Abdullah I Al-Shoshan. Speech and music classification and separation: a review. Journal of King Saud University-Engineering Sciences, 19(1):95–132, 2006.
3. Alessandro Bugatti, Alessandra Flammini, and Pierangelo Migliorati. Audio classification in speech and music: a comparison between a statistical and a neural approach. EURASIP Journal on Advances in Signal Processing, 2002:1–7, 2002.
4. David Doukhan and Jean Carrive. Investigating the use of semi-supervised convolutional neural network models for speech/music classification and segmentation. In The Ninth International Conferences on Advances in Multimedia (MMEDIA 2017):, 2017.
5. Arijit Ghosal, Bibhas Chandra Dhara, and Sanjoy Kumar Saha. Speech/music classification using empirical mode decomposition. In 2011 Second International Conference on Emerging Applications of Information Technology, pages 49–52. IEEE, 2011.
6. Harry Hollien, Patricia A Hollien, and Gea de Jong. Effects of three parameters on speaking fundamental frequency. The Journal of the Acoustical Society of America, 102(5):2984–2992, 1997.
7. Md Shamim Hussain and Mohammad Ariful Haque. Swishnet: A fast convolutional neural network for speech, music and noise classification and segmentation. arXiv preprint arXiv:1812.00149, 2018.
8. TL Li, Antoni B Chan, and AH Chun. Automatic musical pattern feature extraction using convolutional neural network. Genre, 10(2010):1x1, 2010.
9. Beth Logan et al. Mel frequency cepstral coefficients for music modeling. In Ismir, volume 270, page 11. Plymouth, MA, 2000.
10. Toru Nakashika, Christophe Garcia, and Tetsuya Takiguchi. Local-feature-map integration using convolutional neural networks for music genre classification. In Thirteenth Annual Conference of the International Speech Communication Association, 2012.
11. Julien Pinquier, J-L Rouas, and Régine André-Obrecht. A fusion study in speech/music classification. In 2003 IEEE International Conference on Acoustics, Speech, and Signal Processing, 2003. Proceedings.(ICASSP’03)., volume 2, pages II–17. IEEE, 2003.
12. Manoj Rajput, Krishna Chauhan, Girdhar Gopal, Arun Kishor Johar, Ashutosh Tripathi, and Tarun Varma. Speaker recognition using 3d convolutional neural network and gmm. In International Conference on Energy Systems, Drives and Automations, pages 549–558. Springer, 2021.
13. Mehdi Roopaei, Paul Rad, and Mo Jamshidi. Deep
