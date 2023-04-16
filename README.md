# Music Genre Classification Based On Song Titles Using Long Short-Term Memory

This repo contains the code and dataset used for this publication: 

O. Sahin, "Music Genre Classification Based on Song Titles with Long Short-Term Memory," 2023 IEEE International Students' Conference on Electrical, Electronics and Computer Science (SCEECS), Bhopal, India, 2023, pp. 1-5, doi: 10.1109/SCEECS57921.2023.10063028.

https://ieeexplore.ieee.org/abstract/document/10063028



#Background
Classifying music into genres is a challenging task, but it becomes even more challenging when trying to do so based solely on the song title. Many titles only have three or four words, which may not clearly indicate the genre. This study aimed to explore whether deep learning models could accurately classify songs based on their titles alone.

#Dataset
The dataset used in this study was obtained from Kaggle and consisted of 50,000 songs and their attributes. The dataset was pre-processed to make it compatible with the deep learning models used in this study.

#Models
Several deep learning models were compared in this study, Recurrent Neural Networks (RNN), and Long Short-Term Memory (LSTM) networks. The models were trained using the pre-processed dataset, and their performance was evaluated based on accuracy.

#Results
The LSTM model with an extra layer and a dropout was found to be the most accurate, with an accuracy of 42.21%. This result is promising, considering the difficulty of the task, and suggests that deep learning models may be useful for music genre classification based on song titles.

#Conclusion
To the best of the authors' knowledge, this study is the first to explore music genre classification using song titles alone. The results demonstrate the potential of deep learning models for this task and provide a foundation for future research in this area.

#Contents
stemmed_titles_hiphop_jazz.csv : contains the pre-processed dataset used in the study. The song titles are in this format ['hello world'] and they are stemmed. The "remove_punct" function in the jupyter notebook is used to delete punctuation. The stemming process can be seen as a block comment in the jupyter notebook.

genre_title_seperated.ipynb : contains the jupyter notebook used for this study. This notebook contains all necessary code for the deep learning models and the data pre-processing. 

requirements.txt : contains all required libraries.

README.md: this file.
