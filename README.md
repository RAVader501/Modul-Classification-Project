# Modul-Classification-Project

This project consist of two trained modules for SDG NLP classiffication.
1. First one being a Bert module, which was imported and trained in the "BertModel" Jupyter Source File. Training and Validation both were performed in the same file.

2. Second is Lama-2 specifically nous-hermes2 language model. In the file "LamaModel" we have an API call to the Workspace at Gradient.ai, where the model is stored. The file has also ready code to create and train new models who will also be stored in the workspace and can be accessed with the ID provided in the Jupyter Source File upon creation.

Both of the models use "German_cleaned_combined2.csv" file as training/fine-tuning Data Set. Both of them format the Data in their own source file differently for training.

Other files are:
  - data2 is a  JSON file, generated in the "LamaModel" running process, consisting of formated data from our Dataset.
  - my_bert_model is our last stored Bert model instance 
