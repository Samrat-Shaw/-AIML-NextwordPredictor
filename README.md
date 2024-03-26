# -AIML-NextwordPredictor
INTRODUCTION

Next-word prediction technology is a cutting-edge advancement in natural language processing (NLP) that aims to enhance user experience and productivity across various digital platforms.In this project we are using LSTM (i.e long short -term memory model ) to train our datasets.At its core, next-word prediction relies on vast datasets of textual information to train predictive models. These models analyze patterns in language usage, including syntactic structures, semantic relationships, and contextual cues, to anticipate the most likely words to follow a given sequence of words or characters.

Libraries Used
1)	Numpy 
2)	Tensorflow
3)	tensorflow.keras.preprocessing.text.Tokenizer
4)	tensorflow.keras.preprocessing.sequence.pad_sequences
5)	tensorflow.keras.models.Sequential
6)	tensorflow.keras.layers.Embedding
7)	tensorflow.keras.layers.Dense

Requirements For Execution Of The Code
1.	Make  sure u have google account if not make one by clicking on 
2.	Good internet connection
3.	 Google colab : Welcome To Colaboratory - Colaboratory (google.com)
4.	Git bash installed in your laptop or system

Steps to execute

Google colab
1.	To run the code in google colab go to the link specified in requirements
2.	Then select github option located at the lefthand side  of the table 
3.	Then  copy and paste thIS link https://github.com/Samrat-Shaw/-AIML-NextwordPredictor  
4.	All the code  required to execute  will be imported from the github repository
5.	To download the dataset  click  download on IndiaUS.txt present in this respo 
6.	Then click on the file symbol present at the lefthandside in google cloab . Make sure your internet connection is proper 
7.	 upload the dataset file in google cloab  by clicking at upload symbol present at left hand side (it has a symbol of  file and a arrow pointing upwards)  
8.	Then right click on the file and copy its path and paste it on code snippet 
“ with open("copy paste the path here ", 'r', encoding='utf-8') as myfile:
    mytext = myfile.read()”
9.	And run the cell from one by one  
10.	At the end  the output console will ask you to enter the words to predict so make sure to copy paste the words from the IndiaUS.txt
and press on enter.
11.	The model will predict the next 6 words 
