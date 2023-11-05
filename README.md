# Face Verification and Classification with ConvNext and ArcFace

Welcome to the repository for an advanced face verification and classification project on the VGG2 dataset, utilizing a modified ConvNext CNN architecture coupled with ArcFace loss.

## Project Overview

This project addresses two significant challenges in computer vision:

- **Face Classification**: A multi-class classification problem where the goal is to correctly identify a given face from a known set of identities.
- **Face Verification**: Relating unknown identities to known ones based on the similarity in generated embeddings, a quintessential task in security and personalized services.

### Modified ConvNext CNN

We've adapted the cutting-edge ConvNext CNN architecture, tuning it specifically for the nuances of facial recognition tasks. This modified network is tailored to capture the intricate features and distinctions in human faces, making it highly effective for classification purposes.

### ArcFace Loss

For verification, we've employed ArcFace loss, which enhances the discriminative power of the embeddings. It works by mapping facial features into an embedding space where geometrically, the angle between different faces represents their similarity.


## Features

- **High Accuracy**: Achieve precise classifications (>90%) and verifications with our fine-tuned model.
- **Robust Embeddings**: Generate robust facial embeddings that can be used for a variety of applications.
- **Scalability**: Our solution scales gracefully with your dataset size, maintaining performance.

## Getting Started

Clone the repository and follow the instructions outlined in the notebook
