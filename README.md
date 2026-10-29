# RiyFR

**RiyFR: An Arabic Fake Review Dataset for Review Authenticity Detection**

RiyFR is an Arabic fake review dataset collected from Google Maps reviews and developed to support research in fake review detection, review authenticity analysis, and Arabic Natural Language Processing (NLP). The dataset was created as part of the Sidq Graduation Project.

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

The dataset was collected from publicly available Arabic Google Maps reviews and manually annotated according to predefined labeling guidelines developed by the project team.

The annotation process focused on identifying potentially deceptive and authentic reviews based on linguistic and behavioral indicators established during the project development phase.

## Authors

RiyFR was developed by:

- **Norah Alkorbi** 
- **Remas Alkhibari**
- **Sara Alharbi**
- **Reem Almalki**
- **Maryam Alhamed**

## Ethical Considerations

- The dataset is intended exclusively for research and educational purposes.
- Personally identifiable information (PII) should not be included in the released version of the dataset.
- Researchers using RiyFR are responsible for complying with applicable platform policies and regulations.

## License

RiyFR is licensed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

Under this license, users may:

- Share — copy and redistribute the dataset.
- Adapt — remix, transform, and build upon the dataset.

Provided that appropriate attribution is given to the RiyFR authors.

Full license:
https://creativecommons.org/licenses/by/4.0/

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
