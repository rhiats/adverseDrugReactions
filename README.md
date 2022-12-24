# Pharmacovigilance: Identify Adverse Drug Effects from Real-World Data: Medical Case Reports, Discharge Notes and User-Generated Content

The aim is to leverage three types of Real-World Data to contribute to the automated identification of Adverse Drug Reactions.

## Medical Case Reports and Biomedical Literature: 

PHEE Datasource 5,000 annotated events from medical case reports and biomedical 
literature, making it the largest such public dataset to date. The dataset is extracted from MEDLINE case reports and each sentence features two levels of annotations: coarse-grained and fine-grained. The coarse-grained annotations contain event trigger word/phrase, event type and text spans indicating the event’s associated subject, treatment, and effect. The fine-grained annotations contain patient demographic information, the context information about the treatments including drug dosage levels, administration routes, frequency, and attributes relating to events (Sun, 2022). The train, development and test sets are to be recreated with stratified sampling using the demographic information, then try three models: Sequence Labeling, Extractive QA, Generative QA to classify pertinent information in the dataset.



