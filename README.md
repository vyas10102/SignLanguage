# Sign Language Translation System Proposal

202403_Intro to Computer Vision_CSCI_6527_10_Final Project

## Acknowledgment 

This blog post was done by Ritwika Das (GWID: G30941802) and Aditi Vyas (GWID: G40802010) under the guidance of Professor Robert Pless for the course Introduction to Computer Vision (CSCI 6527_10).

## Objective
The primary goal of this project is to develop a sophisticated assistive technology system that translates American Sign Language (ASL) into text. The system will facilitate effective communication for individuals who are deaf or hard of hearing, allowing them to convey messages to those who do not understand sign language. Additionally, as an exploratory objective, we will attempt to implement a feature that converts the translated text into speech. This optional feature aims to further extend the system's utility by making information accessible to individuals who are visually impaired, thus enhancing inclusivity across multiple sensory disabilities. The successful implementation of both components would represent a significant advancement in assistive technologies, bridging communication gaps in everyday interactions, educational settings, healthcare environments, and other areas critical to quality of life and integration.


## Project Description
### Inputs and Outputs
- **Inputs:** User-uploaded videos via the system interface, capturing real-time ASL gestures.
- **Outputs:** Primary output will be text displayed on-screen. An optional output, synthesized speech, will be explored based on feasibility and implementation success.

### Target Audience
This system is designed for individuals who are deaf or hard of hearing. The optional speech output feature also aims to serve individuals who are visually impaired, along with educators, healthcare providers, and public service workers who interact with these communities.

## Proposed Approach
### High-Level Approach
We plan to use computer vision and machine learning techniques, particularly convolutional neural networks (CNN), to recognize and classify ASL gestures from video inputs into text. We will also explore the feasibility of extending this system to include a text-to-speech (TTS) conversion.

### Datasets
The training and validation will utilize the Sign Language MNIST dataset, which includes images derived from video frames of ASL gestures.

### Challenges
Key challenges include the accurate interpretation of ASL gestures and the potential text-to-speech conversion. Environmental variables in video data such as lighting and background can also complicate gesture recognition.

## Input/Output Data
- **Input:** Video data uploaded by users.
- **Output:** Text display and, if feasible, speech output.

## Training Data
The primary dataset for this project will be the Sign Language MNIST dataset.

## Evaluation Plan
The model’s performance will be evaluated through accuracy metrics on a test set. User feedback and trial implementations will help ensure practical usability. The optional text-to-speech feature will undergo separate feasibility and effectiveness assessments.

## Impact
This project could significantly enhance communication accessibility, promoting inclusivity in education, healthcare, and public services. It may also serve as an educational tool for learning ASL.

## Tools and Resources
### Data Sources
- **Sign Language MNIST dataset**

### Software and Tools
- **Programming Language:** Python
- **Libraries:** TensorFlow, Keras (for machine learning), potential text-to-speech libraries.

### Inspirational Sources
- Previous research and projects in sign language recognition and assistive technology.
