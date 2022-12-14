# Music classifier by genres using CNN and KNN models

The goal of this project is to build machine learning models that process audio files (in wav format for this particular case) and classify them into the correct music genre.

Different types of machine learning algorithms and solutions are capable of solving this problem, from simple and supervised machine learning algorithms that can be used to solve classification and regression problems such as KNN, to convolutional neural networks (CNN). For this particular project, we focused on building a CNN and KNN that can accurately predict the genre of different audio files.

## Slides, Report and video

- [Slides](https://github.com/vanelozano7312/MusicGenreClasifier/blob/main/Music%20classifier%20by%20genres%20using%20CNN%20and%20KNN%20models%20Slides.pdf)

- [Report](https://github.com/vanelozano7312/MusicGenreClasifier/blob/main/ProyectoFinal.pdf)

- [Video](https://youtu.be/V0mP8Ccc2IQ)

## How to use it
### KNN
In order to use the .ipynb file we need to download the *DataFeatures*, *ExampleAudio* and *Data* folder and put it in the google collab folder. The *Data* file is big so it'll work better if you upload it in your drive and use it from there in the google collab. 
We recomend to download the .zip of this repository, then you just have to extract the files, install the requirements and open it in your favorite code editor. 


- code: 
	- jupyter notebook: `KNN_for_Music_Genre_Classification.ipynb`
	- python file: `GenreFeatureData.py` 
	- python file: `testKNN.py`
	
Run `GenreFeatureData.py` file if you want to reload the database or test the accuracy, you can also run `testKNN.py` to try the model with some of our examples.

### CNN

In order to use the .ipynb file we need to download the *Data CNN* and *Data* folder and put it in the google collab folder. The *Data* file is big so it'll work better if you upload it in your drive and used from there in the google collab, changing the "DATASET_PATH = "/content/Data/genres_original" rute" for your drive rute and uncomment # save_mfcc(DATASET_PATH, JSON_PATH, num_segments=10) line of the code. Then in the "DATA_PATH = "/content/Data CNN/data_10.json"" you put the rut of the json file that is already created in you google collab. And that's it. This collab will take a lot of minutes, around 30, but it will give the best results.

- code: 
	- jupyter notebook: `CNN_for_Music_Genre_Classification_Test.ipynb`
- models: pre-trained models

### Code 
In this repository we provide the scripts to fine-tune the pre-trained model and a quick music genre prediction algorithm using our own weights. 

Currently the genres supported are the [GTZAN dataset](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwi0w9v6ndv7AhW2RzABHV9IBWUQFnoECBMQAQ&url=https%3A%2F%2Fwww.kaggle.com%2Fdatasets%2Fandradaolteanu%2Fgtzan-dataset-music-genre-classification&usg=AOvVaw3TTtu7nUZPCc-fNioZPjzz) tags:

- blues
- Clasic
- Country
- Disco
- Hip hop
- jazz
- Metal
- Pop
- reggae
- Rock

