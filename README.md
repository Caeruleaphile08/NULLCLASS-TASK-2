# NULLCLASS TASK-2 (Word Checker)

This project is a simple Python script that checks whether a given word is available in a dataset and provides suggestions for similar words if the word is not found.

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/Caeruleaphile08/NULLCLASS-TASK-2.git
    ```

2. Install the required dependencies:

    ```
    pip install pandas
    pip install numpy
    ```

## Problem Statement
Creating a feature to throw an error if we enter the wrong word. For example if we enter a word which is not available the program should throw an error saying like this “word is not available” and provide some suggestion related to the word which is incorrect . If the user enter continuously 2 wrong word it should show list of wrong words which we enter so far in the error notification as well as it should give some suggestions related with wrong word.


## Usage

1. Run the cells:

2. Follow the prompts to enter words to check. Type 'stop' to end the program.

## Features

- Checks whether a word is available in a dataset.
- Provides suggestions for similar words if the word is not found.
- Handles consecutive wrong entries and provides error messages.

## Dataset

The dataset used for word checking is loaded from a CSV file containing word frequencies. You can find the dataset in kaggle.
```bash
https://example.com/dataset.csv](https://www.kaggle.com/datasets/rtatman/english-word-frequency?rvi=1
```

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.
