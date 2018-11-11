# Documentation

## Team members

- Jo - data analytics, R, python
- Lora - javascript
- Quynh - javascript, nodejs, python
- [Eddie Jaoude](http://github.com/eddiejaoude) - devops, fullstack javascript

## Agenda

1. Discuss the challenge
2. Look at the sample data (github account shared for challenge)
3. Pick technologies
4. How to present the data

## Notes

1. Compare before/after images 
2. Data is very large - there is geo data supplied but images do not seem to have gps
3. -
4. Idea: heatmap on percentage damage

## Actions

| Who | Action | Result |
| :-- | :-- | :-- |
| Jo | - | - |
| Quynh | Research resource on the subject matter | - |
| Lora | Compare different GPU solutions | - |
| Eddie | Geo data on a map | - |

## Resources

- Intro to CNN (Convolutional Neural Network) https://skymind.ai/wiki/convolutional-network
- 
## Training Data Models Research Summary (Google Colab vs Kaggle etc) (Lora) 
I considered the following options to get started with modeling our data set and training it: 

1. Google Colab (https://colab.research.google.com/notebooks/welcome.ipynb#recent=true)
2. Kaggle (https://www.kaggle.com/sallora44/kernel35742956a0/edit) 
3. AWS Sage Maker (https://aws.amazon.com/sagemaker/)
4. Paperspace (https://www.paperspace.com/ml)
5. TensorFlow JS (https://js.tensorflow.org/)


The 1-3 options require us to train the model in Python (my undersatnding is that we are trying to avoid python as it will slow us down - unless Joanna got it covered?) 


Individual summaries: 

1. Google Colab (https://colab.research.google.com/notebooks/welcome.ipynb#recent=true)

- Using only Python within Jupiter Notebook 
- Built in integration with Tensorflow 
- Easy for version control / collaborative work 
- Stored on Google Drive 
- Provides some prebuilt ML models to built on 
- Free of charge 

2. Kaggle (https://www.kaggle.com/sallora44/kernel35742956a0/edit) 

- Using Python or R within Jupiter Notebook 
- Looks like some Kernels (or Keras..not very clear yet) are linked with Tensorflow 
- Also seemed a little clamsy and hard to setup account
- Free of charge 

3. AWS Sage Maker (https://aws.amazon.com/sagemaker/)

- Using only Python within Jupiter Notebook 
- Pre-configured to run TensorFlow
- Provides a lot of pre-built ML models including most algorithms (like regression etc) 
- Seems like an easy solution if we were to use S3 to store the large datasets 
- Not free.. so wil only work if Eddie is willing to use his account.. 

4. Paperspace (https://www.paperspace.com/ml)

- Use Gradient notebook, also Python https://www.paperspace.com/gradient
- Seems like they have a JS api (https://paperspace.github.io/paperspace-node/#programmatic-access-via-paperspace-node) but is also under construction 
- Pre-configured to run TensorFlow
- Powerful GPU (following reviews) 

5. TensorFlow JS (https://js.tensorflow.org/)

- This option allows us to build and train models in JS (example here https://www.youtube.com/watch?v=XdErOpUzupY)
- However, Tensorflow JS is still in development and might not be as robust / reliable just yet - direct quote: "TensorFlow.js has an API similar to the TensorFlow Python API, however it does not support all of the functionality of the TensorFlow Python API. We are working hard to achieve API parity where it makes sense but also strive to provide an idiomatic JS API."
- Another example of liner regression in TF JS https://www.youtube.com/watch?v=NZR-N_dhK2M




