# Insurance-Fraud-Detection-
# Patient Pre-Existing Disease (PED) Analysis

This project involves analyzing patient data to identify pre-existing diseases (PEDs) using natural language processing (NLP) techniques and Jaccard similarity for text comparison. The primary goal is to determine if a given disease is pre-existing in a patient's medical history.

## Features

- Preprocesses text data by tokenizing and removing common and unnecessary terms.
- Calculates Jaccard similarity between the input disease and patient condition descriptions.
- Identifies pre-existing diseases based on similarity thresholds.
- Handles specific text patterns and exclusions to enhance accuracy.

## Requirements

- Python 3.x
- pandas
- nltk
- An Excel file named `PED training data.xlsx` with patient data

## Setup

1. Clone the repository or download the script files.
2. Install the required Python packages:
    ```sh
    pip install pandas nltk
    ```
3. Ensure that `PED training data.xlsx` is in the same directory as the script.

## Usage

1. Run the script:
    ```sh
    python script_name.py
    ```
2. Follow the prompts to enter a patient ID and disease.

## Functions

### preprocess_text

```python
def preprocess_text(text, common_terms=None, exclude_terms=None):
```

### calculate_jaccard_similarity

```python
def calculate_jaccard_similarity(tokens1, tokens2):
```

### remove words after w_o

```python
def remove_words_after_w_o(text):
```

### check_ped

```python
def check_ped(patient_id, disease):
```

## Example

```python
Enter patient ID (type 'exit' to end): 12345
Enter disease for patient 12345: Diabetes
```  






