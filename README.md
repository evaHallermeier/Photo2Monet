# Photo2Monet

# Deep learning final semester Project - Kaggle competition: add Monet style to a photo

The project is separated in three notebooks:

## Notebook1 - Training Model 1- of cycleGAN-with different experiment
DO NOT RUN IT!! because it will take few hours to get all output


link of the colab notebook: https://colab.research.google.com/drive/1UBufJiyDc4_NaPOWSkX7kp_2YFD58E8P?usp=sharing


### Table of content:

      -Description of the project
            -Architecture of CYCLE GAN
      -Import librairies
      -Load Dataset from drive
      -Preprocessing methods
      -Visualize data methods
      -Monet selection algorithm definition
            -Methods for selecting subset of Monet Paintings
      -Cycle GAN methods to define the architecture
            -Discriminator structure: patch GAN
            -Generator structure
            -Training methods
      -Visualize data:photo and Monet painting
            -Monet paintings exemples
            -Photos exemples
      -Experiment 1:Running cyclegan with specific architecture and specific hyper parameters
            -Global variables and hyper parameters
            -Architecture of cycleGAN
                  -Generator structure for experiment 1
                  -Discriminator structure for experiment 1
                  -Building cycleGAN:create instances
            -Build dataset for the experience: loading and preprocessing
                  -Select 30 Monet paintings for training
            -TRAINING
                  -Performance of the model in training:plot loss
            -Save model
            -Show results of the model trained with 5 photos
                  -Select photos and preprocessing
                  -Image generation:transform photo to Monet style image
      -Experiment 2
            -Hyperparameters
            -Training for experience 2
            -Show results of the model trained with 5 photos
                  -Select photos and preprocessing
                  -Image generation:transform photo to Monet style image
      -Kaggle submission: generate photos 256X256




## Notebook 2 - Training of second model : Neural style transfer with different experiments
DO NOT RUN IT!!
link of the colab notebook: 
https://colab.research.google.com/drive/1WoIo7P7S2vVl7XVmZsKQIPQHeYJt-D1s?usp=sharing

### Table of content:
- Description
- Architecture
- Import Liberies
- Hyper parameters
- Helper functions
- Load and preprocess a single image
- The model
- The Optimizer
- Step definition
- Training loop
- 1st Experiment
      - Finding the most similar painting
      - Preperation
      - Loss over time
- 2nd Experiment
      - Loss over time



## Notebook 3 TEST-

https://colab.research.google.com/drive/1iMD9sCEPMLV7qHi53t0e0P8kmBg0T2au?usp=sharing

### Table of content

- Load model
- Upload a photo from your computer
- Test
      
 ## Installation:
 The notebook TEST :run the notebook and at the cell of UPLOAD PHOTO: you can upload a photo of your choice, and the model will generate the Monet style version image.
 
 
 
 The team: Eva Hallermeier and Noam Koren
