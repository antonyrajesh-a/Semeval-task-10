# EDiReF Shared Task at SemEval 2024

This repository contains the code and datasets for the EDiReF shared task at SemEval 2024. The shared task is an amalgamation of three subtasks:

1. Emotion Recognition in Conversation (ERC) in Hindi-English code-mixed conversations.
2. Emotion Flip Reasoning (EFR) in Hindi-English code-mixed conversations.


## Task Definitions

### ERC (Emotion Recognition in Conversation)
Given a dialogue, ERC aims to assign an emotion to each utterance from a predefined set of possible emotions.

### EFR (Emotion Flip Reasoning)
Given a dialogue, EFR aims to identify the trigger utterance(s) for an emotion-flip in a multi-party conversation dialogue.

## Directory Structure

- `Subtask1_mBERT_non_transliterated/`: Contains the Colab notebook and associated dataset text files for training the mBERT model for ERC.
- `Subtask2_EFR_Classifiers/`: Contains the Colab notebook and associated dataset JSON files for training the mBERT model for EFR.

## Instructions

### Subtask 1 - Emotion Recognition in Conversation (ERC)
1. Navigate to the `Subtask1_mBERT_non_transliterated/` directory.
2. Open the Colab notebook `mBERT_non_transliterated.ipynb`.
3. Follow the instructions in the notebook to train the mBERT model for ERC using the provided dataset text files.

### Subtask 2 - Emotion Flip Reasoning (EFR)
1. Navigate to the `Subtask2_EFR_Classifiers/` directory.
2. Open the Colab notebook `EFR_Classifiers.ipynb`.
3. Follow the instructions in the notebook to train the mBERT model for EFR using the provided dataset JSON files.

## Dataset
The dataset for both subtasks is not included in this repository due to size constraints. Please contact the organizers of the EDiReF shared task at SemEval 2024 to obtain the dataset.

## Contributors
- [Your Name](https://github.com/yourusername)

## License
This project is licensed under the [MIT License](LICENSE).
