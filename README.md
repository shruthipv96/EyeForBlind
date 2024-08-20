# Eye For Blind
---
> This project is designed to empower visually impaired individuals by leveraging the power of machine learning . The aim is to improve the quality of life for the visually impaired by enhancing their independence and enabling them to interact more effectively with their surroundings. This project focuses on creating a model that can interpret and describe visual information, making the world more accessible to those with visual impairments.
---

## Dataset

The dataset used in this project is sourced from Kaggle. It includes a collection of 8,091 images, each accompanied by five distinct captions. These captions offer detailed descriptions of the key entities and events depicted in the images. You can access the dataset through the following link: [Flickr8k Dataset on Kaggle](https://www.kaggle.com/adityajn105/flickr8k).

## Project Pipeline:
1. **Data Understanding:** Load and interpret the dataset.
2. **Data Preprocessing:** Format both images and captions.
3. **Train-Test Split:** Prepare and split the data for training and testing.
4. **Model Building:** Construct the image captioning model, including the Encoder, Attention, and Decoder components.
5. **Model Evaluation:** Assess the model's performance using greedy search and beam search.

A sample output looks like:

![SamplePrediction](https://github.com/user-attachments/assets/ed711940-ea95-44cf-ad84-a3e6302b0086)

## Features

The application will include the following key features:

1. **Image Captioning**: Automatically generate descriptive captions for images, providing users with a detailed understanding of the visual content.
2. **Audio Feedback**: Convert the generated captions into speech, allowing users to receive information audibly.

## Technologies

The project leverages mainly the following technologies:

- **Python**: The core programming language used for the application.
- **TensorFlow/Keras**: For building and training machine learning models.
- **Pre-trained Models**: Such as those available from ImageNet, to extract features and aid in the caption generation process.
- **Gtts**: For text to audio conversion

## Contact
Created by [Shruthip Venkatesh](https://github.com/shruthipv96) - feel free to contact me!

