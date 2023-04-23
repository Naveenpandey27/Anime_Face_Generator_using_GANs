# Anime_Face_Generator_using_GANs
The Anime Face generator is a deep learning model that generates anime-style faces using generative adversarial networks (GANs). It is trained on a large dataset of anime faces and can generate new faces with various attributes, such as gender, age, and emotions.


## Dataset
The dataset used in this code is "Anime Faces" dataset available on Kaggle. The dataset contains 21551 anime face images with size 64x64 pixels.

## Instructions
To run the code, follow the below instructions:

1 - Install Kaggle API by running !pip install -q kaggle

2 - Upload your Kaggle API token (kaggle.json) by running the code from google.colab import files files.upload()

3 - Create a directory for your Kaggle API token by running ! mkdir ~/.kaggle

4 - Copy your Kaggle API token to the new directory by running ! cp kaggle.json ~/.kaggle/

5 - Change the permission of the Kaggle API token by running ! chmod 600 ~/.kaggle/kaggle.json

6 - List the available datasets by running ! kaggle datasets list

7 - Download the "Anime Faces" dataset by running ! kaggle datasets download -d soumikrakshit/anime-faces

8 - Unzip the downloaded file by running !unzip anime-faces.zip

9 - Run the code to generate anime faces.
