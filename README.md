# Sign Language Translation System Proposal

202403_Intro to Computer Vision_CSCI_6527_10_Final Project

## Acknowledgment 

This blog post was done by Ritwika Das (GWID: G30941802) and Aditi Vyas (GWID: G40802010) under the guidance of Professor Robert Pless for the course Introduction to Computer Vision (CSCI 6527_10).

## Objective
The goal of this project is to develop an assistive technology that translates American Sign Language (ASL) into text, with an optional feature to convert this text into speech. This system aims to facilitate communication for individuals who are deaf or hard of hearing and potentially assist those who are visually impaired.

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
