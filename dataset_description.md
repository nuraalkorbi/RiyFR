# RiyFR

**RiyFR: An Arabic Fake Review Dataset for Review Authenticity Detection**

RiyFR is an Arabic fake review dataset collected from Google Maps reviews and developed to support research in fake review detection, review authenticity analysis, and Arabic Natural Language Processing (NLP). The dataset was created as part of the **Sidq Graduation Project**.

## Overview

Online reviews significantly influence customer decisions, making review authenticity an important research area. RiyFR provides a labeled Arabic dataset designed for developing, training, and evaluating machine learning and deep learning models for fake review detection.

## Dataset Information

| Attribute | Description |
|------------|------------|
| Dataset Name | RiyFR |
| Language | Arabic |
| Source Platform | Google Maps |
| Task | Fake Review Detection |
| Classification Type | Binary Classification |
| Format | CSV |
| Version | 1.0 |

## Dataset Statistics

- Raw Reviews Collected: 1,000
- Training Set Size: 850 reviews
  - Genuine Reviews: 704
  - Fake Reviews: 146
- Testing Set Size: 150 reviews
- Language: Arabic
- Source Platform: Google Maps
- Classification Type: Binary Classification
- Version: 1.0

## Labels

The dataset uses binary labels:

| Label | Meaning |
|---------|---------|
| 0 | Genuine Review |
| 1 | Fake Review |

## Applications

RiyFR can be used for:

- Fake review detection
- Review authenticity analysis
- Arabic text classification
- NLP research
- Machine learning experiments
- Deep learning model evaluation
- Trust and credibility analysis

## Dataset Structure

Example format:

```csv
review_text,label
"الخدمة ممتازة وسريعة",0
"أفضل مطعم في العالم وأنصح الجميع بزيارته يومياً",1
```

## Data Collection and Annotation

RiyFR was constructed from 1,000 Arabic reviews collected from publicly available Google Maps reviews.

The dataset was manually annotated according to predefined labeling guidelines developed by the project team. Reviews were categorized as either genuine or fake based on authenticity-related indicators and review characteristics.

The dataset was split into:

- Training Set: 850 reviews
  - 704 genuine reviews
  - 146 fake reviews

- Testing Set: 150 reviews

This split enables the training and evaluation of machine learning and deep learning models for Arabic fake review detection.

## Ethical Considerations

- The dataset is intended for research and educational purposes.
- Personally identifiable information (PII) should not be included in the released version of the dataset.
- Users of the dataset are responsible for complying with applicable laws, regulations, and platform policies.
- The authors do not endorse the use of the dataset for harmful, discriminatory, or unethical purposes.

## Limitations

- The dataset focuses on Arabic-language reviews collected from Google Maps.
- Models trained using RiyFR may not generalize perfectly to all review platforms or domains.
- Annotation decisions may be influenced by available contextual information and annotation guidelines.

## Authors

RiyFR was developed as part of the Sidq project by:

- **Norah Alkorbi** 
- **Remas Alkhibari**
- **Sara Alharbi**
- **Reem Almalki**
- **Maryam Alhamed**

## License

RiyFR is distributed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

You are free to:

- Share — copy and redistribute the dataset in any medium or format.
- Adapt — remix, transform, and build upon the dataset for any purpose.

Under the following condition:

- Attribution — appropriate credit must be given to the RiyFR authors.

Full license: https://creativecommons.org/licenses/by/4.0/

## Citation

If you use RiyFR in your research, please cite:

```text
Alkorbi, N., Alkhibari, R., Alharbi, S., Almalki, R., & Alhamed, M. (2026).

RiyFR: An Arabic Fake Review Dataset for Review Authenticity Detection.

GitHub Repository:
https://github.com/nuraalkorbi/RiyFR
```

## Acknowledgments

RiyFR was developed as part of the Sidq Graduation Project. The authors thank all contributors who participated in the collection, annotation, validation, and quality assurance of the dataset.

---

© 2026 The RiyFR Authors
