# Project Name: Hand Gesture Recognition for a Smart TV Interaction System

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
- Developed a smart TV interaction system that leverages AI-powered hand gesture recognition to enable touch-free control of smart televisions.
- The system recognizes five distinct gestures:
  1. **Thumbs Up:** Increase the volume
  2. **Thumbs Down:** Decrease the volume
  3. **Left Swipe:** Jump backwards 10 seconds
  4. **Right Swipe:** Jump forward 10 seconds
  5. **Stop:** Pause the movie
- The project involves processing video data where each video (2-3 seconds long) is segmented into multiple frames. A custom data ingestion pipeline was built to preprocess these frames (cropping, resizing, normalization) ensuring consistency for model training.
- Various deep learning architectures were explored, including 3D Convolutional Networks and a CNN-RNN stack, to effectively capture both spatial and temporal features necessary for accurate gesture recognition.

## Technologies Used
- **Python** – Core programming language
- **TensorFlow/Keras** – Deep learning frameworks for model development
- **OpenCV** – For video frame processing and image manipulation
- **Pandas & Numpy** – Data handling and numerical computations
- **Matplotlib & Seaborn** – Data visualization
- **Custom Data Generator** – For efficient ingestion and preprocessing of video data

## Conclusions
This hand gesture recognition system, powered by a MobileNet + GRU model, achieved a high accuracy of 99.37% on training and 98% on validation data, demonstrating its strong performance and generalization capability. It marks a significant step toward enabling natural, touchless human-computer interaction for Smart TVs. By enhancing user convenience, accessibility, and interaction experience, the system showcases the potential of combining lightweight deep learning architectures with sequential modeling. Leveraging accessible hardware and open-source tools, this approach lays the groundwork for cost-effective, scalable smart home solutions. With further refinement and integration, such systems could become a standard feature in future smart living environments.

## Acknowledgements
- This project was a collaborative case study by Ritwik Raj and Ritesh Kumar.
- The work was inspired by advancements in AI-driven human-computer interaction and gesture recognition.
- Special thanks to the Upgrad IIIT Bangalore PG program on ML and AI for providing the learning resources and guidance.

## Contact
Created by Ritwik[@RitwikRaj24] & Ritesh[@ritesh4aiml] – feel free to reach out for any queries or collaboration!
