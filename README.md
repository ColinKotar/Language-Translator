# Language-Translator

A Recurrent Neural Network (RNN) with Long Short Term Memory (LSTM) cells learns how to translate from English to French using only a small subset of a massive 2GB dataset. This machine learning architecture makes connections along a time sequence, so it remembers why certain words come before or after others.

## Getting Started

Simply run the Jupyter Notebook dlnd_language_translation.ipynb or you can run the script language-translation.py

```
python language-translation.py
```

To translate a sentence, assign the variable translate_sentence a string.

```
translate_sentence = 'he saw a old yellow truck .'
```

### Prerequisites

You can install the required packages through Anaconda's environment manager using the machine-learning.yml file

```
conda env create -f machine-learning.yml
```

Then, activate the environment and run language-translation.py

```
activate machine-learning
```

Otherwise, check out the machine-learning.yml file for dependencies and their versions

## Running the tests

Simply add test cases to problem_unittests.py or run it

```
python problem_unittests.py
```

## Built With

* [TensorFlow](https://www.tensorflow.org/install/install_windows) - The machine learning framework
* [Anaconda](https://repo.continuum.io/archive/Anaconda3-5.1.0-Windows-x86_64.exe) - The environment manager
* [Jupyter Notebook](http://jupyter.org/install) - The code documentation
