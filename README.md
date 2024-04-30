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

- `Subtask1/code/`: Contains the Colab notebook for ERC mBERT model training.
- `Subtask1/data/`: Contains associated dataset text files for training the mBERT model for ERC.
- `Subtask2/code/`: Contains the Colab notebook for EFR model training.
- `Subtask1/data/`: Contains associated dataset JSON files for training the classifiers for EFR.

## Instructions

### Subtask 1 - Emotion Recognition in Conversation (ERC)
1. Navigate to the `Subtask1/code/` directory.
2. Open the Colab notebook `mBERT_non_transliterated.ipynb`.
3. Run the notebook in T4 GPU Runtime.

### Subtask 2 - Emotion Flip Reasoning (EFR)
1. Navigate to the `Subtask2/code/` directory.
2. Open the Colab notebook `EFR_Classifiers.ipynb`.
3. Run the notebook in T4 GPU Runtime.



