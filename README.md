# Deep-Q-Learning-for-Emotional-Lighting

# Introduction

In this project, we use a pre-trained ResNet50 model and train the deep Q-learning algorithm to predict
human emotions based on facial expressions in real-time and then translate these predictions into
ambient lighting effects. The goal is to build a responsive environment that might get adjusted based on
the mood of its user, and therefore improve their user experience. The strategy includes early
processing of images to desire god and fine-tuning a deep Q-network on grey-scale colours alone that
can anticipate emotions at line, following by recreating the expected light colours with their assigned
feelings. Performance of the system is evaluated measuring different metrics.Results showed that our
light form hella emotional lighting. This reveals promising uses of this work in smart homes, therapy
spaces and interactive installations

# Problem
Facial expression emotion detection is a hard The one that is quite a challenging task and needs to be
dealt with highly resilient models, different examples of expressions, lighted circumstances and
individual differences. It often performs poorly on traditional methods leading to discrepancies in the
predictions.The project solution by leveraging the workhorse of the field:reinforcement learning with
deep Q-learning. Deep learning for improved predictive power of the mode emotions accurately. Further,translation of these real-time lighting adjustments from emotional predictions layered
complexity that needs to be smoothly executed combination of hardware and software modules.

# Objective
The main purpose of this research is to come up with a deep Q-learning model that can be used in
predicting human emotions using facial expressions. Moreover, the project seeks to link these forecasts
to lighting outcomes that would result in an adaptive environment. Accordingly, the tasks that will be
conducted include the pre-processing of data sets for uniformity, developing and training a deep Q- network based on a pretrained ResNet50 model and assessing its performance through extensive
metrics. Finally, this project aims at proving that deep reinforcement learning can be applied for
emotional lighting applications.

# Architecture and Working

The system design consists of a number of components. The first is the image preprocessing pipeline
that goes from ensuring image consistency (by removing ICC profiles and applying transformations
such as resizing, normalization and data augmentation), to the custom data set class, which handles
loading and processing images, converting them to grayscale, which is necessary in order for it to be
compatible with the deep Q-network training requirements. Following this is our model architecture
that is based on a pre-trained ResNet50 that was then modified to include a fully connected layer for
emotion classification. To further enhance the models robustness we applied data augmentation
techniques such as random rotations, flips and colour littering. Finally there is the emotion-data lighting
class, responsible for mapping predicted emotions to specific lighting colours thus achieving seamless
integration with IoT enabled lighting systems.

![image](https://github.com/Sriram8452/Deep-Q-Learning-for-Emotional-Lighting/assets/118708032/f45037ad-251b-4ec8-8b46-fbe709c29185)

The gadget layout is designed to make certain efficiency and actual-time response. It starts with
information preprocessing, in which pix are loaded, converted and superior earlier than being
dispatched to the deep Q network. Based on ResNet50, the Q-community tactics these pix and predicts
sensitivity. The expected sensitivities are then mapped to a particular light coloration the usage of the
default mapping module. The gadget has a control module that interfaces with an IoT-enabled lights
device, adjusting lighting fixtures in actual time primarily based on predicted temper This gadget
guarantees a glide from picture input to light output of the machine, with each element interacting
seamlessly to create a compliant and practical environment

![image](https://github.com/Sriram8452/Deep-Q-Learning-for-Emotional-Lighting/assets/118708032/0880de1c-3be5-4e44-86ed-f3bf8d4df1ed)

# Running instructions

1. Install all the packages mentioned in the 'Requirements' section for the smooth running of this project.
2. Organize your dataset with separate folders for training and testing images. Each folder should have subfolders named according to the labels of the images (e.g., "anger", "happiness").
3. Define a Deep Q-Network (DQN) with a few fully connected layers for reinforcement learning. This model is used to interact with the custom environment.
4. Create a custom environment class that simulates interactions. The environment provides state information, processes actions, and returns rewards and done flags.
5. Train the ResNet-50 model using a standard training loop with loss computation, backpropagation, and optimization.
6. Evaluate the trained ResNet-50 model on a test dataset to calculate accuracy.

# Sample Results

# Test Image

![Train](https://github.com/Sriram8452/Deep-Q-Learning-for-Emotional-Lighting/assets/118708032/4d1eecda-55d5-43ab-b19b-fa67e44a276a)

# Test Result

![image](https://github.com/Sriram8452/Deep-Q-Learning-for-Emotional-Lighting/assets/118708032/1ddbf6b0-78cd-476e-b7ec-3034aac60468)



