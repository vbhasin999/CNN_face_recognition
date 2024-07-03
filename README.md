# Face Verification and Classification with ConvNext and ArcFace

Welcome to the repository for an advanced face verification and classification project on the VGG2 dataset, utilizing a modified ConvNext CNN architecture coupled with ArcFace loss.

## Project Overview

To achieve good performance on a verification task, the project follows the following procedure:

- **Face Classification**: A multi-class classification problem where the goal is to correctly identify a given face from a known set of identities. This allows us to train a model that can generate informative facial embeddings. We further fine tune the model using ArcFace loss to enhance the embeddings' discriminative power.
- **Face Verification**: Relating unknown identities to known ones based on the similarity in generated embeddings, a quintessential task in security and personalized services.

### Modified ConvNext CNN

We've adapted the ConvNext CNN architecture, modifying certain features for facial recognition tasks.

### ArcFace Loss

For verification, we've employed ArcFace loss, which enhances the discriminative power of the embeddings. It works by introducing an angular margin between classes by modifying the angle between the feature vector and the corresponding weight vector. This margin helps to make the decision boundaries more discriminative.

## Getting Started

Clone the repository and follow the instructions outlined in the notebook
