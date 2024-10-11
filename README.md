
# smartSense Assessment

## Goal: 
Design and implement a system to streamline email management for HODs at a university ensuring that emails
from various sources (students, corporates and researchers) are categorized, processed and handled efficiently.

**Note:** This repo contains only the finetuning the existing model for categorization part

## Instructions:
- Install the required libraries
```bash
!pip install torch transformers scikit-learn pandas numpy
```

- Run the notebook given in src file

## Pretrained model used for finetuning

**BERT**(Bidirectional Encoder Represenations from Transformers) is used for the task because of the following:

- Commonly used in text classification.
- BERT considers the context of both preceding and following words, enabling it to better understand the nuances of language.
- BERT is based on the transformer architecture, which is highly effective for processing sequential data.
- BERT is pre-trained on a massive amount of text data without any specific task in mind. 
