# Fine-Grained Arabic Named Entity Recognition

## Introduction
This project explores various deep learning approaches for fine-grained Arabic named entity recognition (NER). The research aims to tackle the unique linguistic challenges of the Arabic language, such as complex morphology, ambiguity, and dialectal variations, to develop robust and accurate NER systems.

## Dataset
The study utilizes the Wojood-Fine corpus, a new version of the Wojood dataset, which consists of 550K tokens and 75K entity mentions covering 92 entity types in the train set and 84 entity types in the validation set.

## Preprocessing
The input text undergoes extensive preprocessing steps, including:
1. Stop word removal
2. Diacritic and elongation removal
3. Stemming
4. English word removal
5. Lemmatization
6. Removing non-alphanumeric characters

These preprocessing steps help to normalize the input text and improve the performance of the NER models.

## Models
The researchers explored and evaluated the following model architectures:

1. **Pretrained Transformer Models**:
   - AraBERT
   - XLM-RoBERTa
   - GPT-2

2. **Implemented Models from Scratch**:
   - Bidirectional LSTM

After thorough evaluation, the researchers chose the Bidirectional LSTM model as the preferred approach for the inference task, as it demonstrated robust performance in capturing the sequential dependencies within the input text and better integration with the dataset-specific preprocessing steps.

## Conclusion
This project presents a comprehensive investigation of deep learning approaches for fine-grained Arabic NER. The researchers have successfully developed and evaluated various models, contributing to the advancement of Arabic language processing and its real-world applications.

## Contact
For more information or inquiries, please contact the research team:

- Mohamed Orfy: mohamedehaborfy@gmail.com
- Rahma Abdelhamid: rahmarizk410@gmail.com
- Mazen Gaber: mazen9gaber@gmail.com
- Salma Yousry: salmaelzohari3@gmail.com
