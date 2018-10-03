# Bicleaner

Trained classifiers for Bicleaner scripts: https://github.com/bitextor/bicleaner

# Usage

Download the desired language pack (i.e. English-Estonian)

Uncompress it with:

`tar -xzvf en-et.tar.gz`

This will create a folder for the language pack, containing the files needed for training and/or classifying:

In the given example, the new folder "en-et" will contain the following files:

* dict-en.gz: Probabilistic dictionary for English-Estonian (needed for training and classifying)
* dict-et.gz: Probabilistic dictionary for Estonian-English (needed for training and classifying)
* train.en-et: Training corpus  (needed for training)
* training.en-et.yaml: Training metadata (needed for classifying, generated on training)
* en-et.classifier: Classifier for English-Estonian  (needed for classifying, generated on training)

Please note that if you need a language pack that is not listed here, you can build it yourself by using [`bicleaner-train`](https://github.com/bitextor/bicleaner)
