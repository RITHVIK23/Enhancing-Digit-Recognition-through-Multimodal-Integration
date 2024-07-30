# Enhancing-Digit-Recognition-through-Multimodal-Integration

## Abstract

This project addresses the task of digit recognition by integrating visual and auditory
data, leveraging the unique properties of each modality to enhance model
performance. It utilizes the multimodal MNIST dataset, which contains handwritten
digit images paired with corresponding spoken digit recordings. Separate
encoder models were developed for processing these images and audio files, and
their embeddings were merged to construct a comprehensive representation of the
data. Utilizing dimensionality reduction via t-SNE (t-distributed Stochastic Neighbor
Embedding), the multimodal embeddings were visualized in a two-dimensional
space. Further analysis was conducted through the application of k-means clustering
to the embeddings, evaluating how naturally the data grouped according to
the digit labels. The results indicate that the combined embeddings show clearer
separation and more distinct clustering by digit compared to individual modality
embeddings, demonstrating the advantage of multimodal systems in complex
recognition tasks. This study confirms the potential of integrating auditory and
visual data to improve the accuracy and robustness of machine learning models in
recognizing and classifying digits.
