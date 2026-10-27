Text Annotation and Quality Review Project

Overview

A self-directed portfolio project involving manual annotation of customer-service text samples. The project demonstrates sentiment classification, intent labeling, escalation decisions, and annotation quality review.

Objectives

- Classify customer messages by sentiment.
- Identify the primary intent of each message.
- Determine whether an issue requires escalation using defined rules.
- Write concise rationales for annotation decisions.
- Review labels for consistency and completeness.

Dataset

The dataset contains 20 manually annotated customer-service text samples created for practice. It is a small, illustrative dataset and is not a real customer dataset.

Annotation Categories

- Sentiment: Positive, Negative, Neutral, Mixed
- Intent: Feedback, Complaint, Product Inquiry, Refund Request, Technical Support, General Inquiry
- Escalation: Yes or No
- Rationale: Short explanation supporting the annotations

Tools

- Google Sheets
- CSV
- GitHub

Methodology

1. Defined annotation labels and guidelines.
2. Manually labeled the text samples.
3. Reviewed labels and rationales for consistency.
4. Applied corrections based on the documented rules.
5. Prepared the dataset and quality report for publication.

Quality Assurance

The dataset was reviewed against self-defined guidelines. No independent annotator or gold-standard reference set was used, so objective annotation accuracy and inter-annotator agreement have not been established.

Repository Contents

- "text_annotation_dataset.csv" — labeled text samples
- "annotation_guidelines.md" — label definitions and decision rules
- "annotation_quality_report.md" — quality review and limitations

Limitations

This is a small educational portfolio project. The examples are self-created and do not represent professional annotation experience or production-scale AI evaluation.

Future Improvements

- Expand the dataset with more varied examples.
- Have a second annotator independently label a subset.
- Compare independent labels and investigate disagreements.
- Measure agreement using an appropriate metric.