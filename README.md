# NER-Based Crime Report Analysis

## Overview
This project focuses on developing an AI-driven system using DistilBERT for Named Entity Recognition (NER) to extract key information from crime reports. The system identifies suspect names, crime locations, and organizations, improving investigative efficiency and assisting law enforcement in data organization.

## Dataset
The project utilizes the [CoNLL-2003 dataset](https://huggingface.co/datasets/conll2003) for training the NER model. This dataset contains labeled entities for persons, locations, and organizations, making it suitable for crime-related entity extraction.

## Features
- Fine-tuned DistilBERT model for NER tagging.
- Extracts named entities such as suspects, crime locations, and organizations.
- Enhances crime report analysis by structuring unstructured data.

## Implementation Steps
1. **Preparing the Data** - Formatting and preprocessing the dataset for training.
2. **Loading the DistilBERT Model** - Utilizing the HuggingFace Transformers library.
3. **Fine-Tuning the Model** - Training DistilBERT on crime-related NER data.
4. **Evaluating the Model** - Measuring accuracy and efficiency in extracting named entities.

## Technologies Used
- Python
- HuggingFace Transformers
- DistilBERT
- NLTK
- CoNLL-2003 Dataset

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone <repository-link>
   cd <repository-folder>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the model:
   ```bash
   python ner_crime_analysis.py
   ```

## Results
- The fine-tuned model effectively extracts relevant entities from crime reports.
- Improved investigative efficiency by structuring crucial details.

## References
- [HuggingFace Transformers](https://huggingface.co/transformers/)
- [CoNLL-2003 Dataset](https://huggingface.co/datasets/conll2003)


