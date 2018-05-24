# Bicleaner

Trained models for Bicleaner scripts: https://github.com/bitextor/bicleaner

# Usage

Create a "lang" folder inside your sources path:


`cd src`

`mkdir lang`

Uncompress the desired language pack (i.e. English-Estonian) in the "lang" folder:

`tar -xzvf en-et.tar.gz`

This will create a folder for the language pack (i.e. en-et), containing the files needed for training and/or classifying:

In the given example, the content of this folder is as follows:

* dict-en.gz: Probabilistic dictionary for English (needed for training and classifying)
* dict-et.gz: Probabilistic dictionary for Estonian (needed for training and classifying)
* train.en-et: Training corpus  (needed for training)
* training.en-et.yaml: Training metadata (needed for classifying)
* en-et.classifier: Classifier for English-Estonian  (needed for classifying)
