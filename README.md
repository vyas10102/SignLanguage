# Sign Language Translation System Proposal

202403_Intro to Computer Vision_CSCI_6527_10_Final Project

## Acknowledgment 

This blog post was done by Ritwika Das (GWID: G30941802) and Aditi Vyas (GWID: G40802010) under the guidance of Professor Robert Pless for the course Introduction to Computer Vision (CSCI 6527_10).

## Objective
The overarching goal of this project is to develop an innovative assistive technology that translates American Sign Language (ASL) into text. This transformative system aims to bridge communication gaps for individuals who are deaf or hard of hearing, enabling seamless interaction with those unfamiliar with ASL. Moreover, we are aspiring to incorporate an advanced feature that converts the text output into speech. This ambitious extension seeks to make communications accessible not only to the hearing impaired but also to individuals who are visually impaired, thereby fostering greater inclusivity. If successful, this dual functionality will significantly enhance daily communications across diverse environments such as educational institutions, healthcare facilities, and public services, fundamentally improving accessibility and integration for those with sensory disabilities.

## Project Description

### Inputs and Outputs
- **Inputs:** The system will accept user-uploaded videos through a dedicated interface.
- **Outputs:** The primary output will be immediate text displayed on-screen. An exploratory secondary output, synthesized speech, will be pursued based on technical feasibility and effectiveness.

### Target Audience
This system is meticulously designed for individuals who are deaf or hard of hearing. The potential speech output feature is additionally intended to serve individuals who are visually impaired, along with educators, healthcare providers, and public service workers who interact regularly with these communities.

## Proposed Approach

### High-Level Approach
Utilizing state-of-the-art computer vision and machine learning techniques, particularly convolutional neural networks (CNN), this project will recognize and classify ASL gestures from the video into precise text. We will explore the feasibility of a supplementary text-to-speech (TTS) conversion, enhancing the system's utility by providing auditory communication options.

### Datasets
The system's development and validation phases will employ the Sign Language MNIST dataset, which comprises detailed images extracted from video frames of ASL gestures, meticulously labeled for accurate training.

### Challenges
The project confronts significant challenges, including the intricate interpretation of ASL's nuanced gestures and the environmental variability in video data such as variable lighting and background disturbances. The prospective text-to-speech conversion also presents a complex technological hurdle that we aim to address.

## Evaluation Plan
The system's effectiveness will be rigorously evaluated using precision accuracy metrics against a controlled test set. Additionally, we will engage our target audience in feedback sessions to refine usability and functionality. The optional speech conversion component will undergo a distinct set of evaluations to assess its viability and integration with the primary system.

## Impact
This pioneering project promises to revolutionize communication access for people with hearing and visual impairments, significantly increasing inclusivity across crucial societal sectors. Beyond its immediate benefits, the system could also serve as a vital educational resource for learning ASL and understanding communication barriers.

## Tools and Resources

### Data Sources
- **Primary Dataset:** Sign Language MNIST dataset

### Software and Tools
- **Programming Languages:** Python
- **Libraries:** TensorFlow, Keras for machine learning development; potential incorporation of text-to-speech libraries if the secondary output is viable.

### Inspirational Sources
- Cutting-edge research in sign language recognition and existing assistive technologies have informed our approach, providing a solid foundation for innovative developments.
