# Fake News Classification Dataset

## Overview

The **Fake News Classification Dataset** is a comprehensive English-language dataset containing over 45,000 unique news articles. Each article is classified as either true (1) or false (0), making it an invaluable resource for researchers and practitioners in the field of fake news detection, particularly using Transformers-based models. This dataset is specifically designed to support text classification, fact-checking, and intent classification tasks.

---

## Dataset Summary

- **Title**: Fake News Classification Dataset
- **Language**: English (en-US)
- **Size**: 45,000+ news articles
- **Labels**: Binary (0 = Fake, 1 = True)
- **Supported Tasks**: 
  - Text Classification
  - Fact-checking
  - Intent Classification

---

## Dataset Structure

The dataset comprises 40,587 records with the following fields:

### Key Fields

- **Title**: The title of the news article.
- **Text**: The content of the news article.
- **Label**: A binary classification indicating whether the news is fake (0) or true (1).

### Example Instance:

```json
{
  "id": "1",
  "title": "Palestinians switch off Christmas lights in Bethlehem in anti-Trump protest",
  "text": "RAMALLAH, West Bank (Reuters) - Palestinians switched off Christmas lights at Jesus' traditional birthplace in Bethlehem on Wednesday night in protest at U.S. President Donald Trump's decision to recognize Jerusalem as Israel's capital...",
  "label": "1"
}

---

### Data Splits

The dataset is split into three phases to support supervised learning methodologies:

Train: 24,353 instances
Validation: 8,117 instances
Test: 8,117 instances

---

## Dataset Creation

This dataset is constructed using Python and the Pandas library as the primary data processing tool. It incorporates a mix of multiple fake news datasets sourced from Kaggle to ensure comprehensiveness and diversity.

Version: 1.0.0
Focus: Supervised learning with modern Transformers-based models in NLP.

## Source Data

The dataset is compiled from multiple fake news datasets available on Kaggle, ensuring that it is both extensive and high-quality for machine learning tasks.

## Considerations for Using the Data

This dataset is structured for use in three key phases of a machine learning workflow:

Training Phase: To train NLP models effectively.
Validation Phase: To validate model performance and ensure there is no overfitting.
Testing Phase: To evaluate model accuracy and identify fine-tuning needs.

## Repository

All processes and code used to create this dataset are available in the repository:
Fake News Detection Repository

## License

Please check the repository for licensing information.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to open a pull request or raise an issue for discussion.

## Acknowledgments

Special thanks to Kaggle for providing access to the source datasets.

## Contact

For any inquiries or issues, please contact me through my email address 'sayamk565@gmail.com'.

