# CiteVal

### Introduction
Our dataset is specifically designed for citation verification, it contains manual annotations labeling citations as ``Correct``, ``Incorrect`` or ``Unrelated``. For citations labeled ``Incorrect``, we further define five detailed sub-categories to characterize the nature of the inaccuracy. Each data sample is structured as a pair, consisting of the **citation context** from the citing paper and the corresponding **evidence passage** from the cited paper that justifies the label.

### File stuctures
- **Few_shot_matrix** contains confusion-matrix figures of each benchmarking model with few-shot prompt.
- **Results_cleaned** contains benchmarking results of all the models with zero-shot and few-shot prompts in tsv format.
- **Zero_shot_matrix** contains confusion-matrix figures of each benchmarking model with zero-shot prompt.
- **experiment_dataset.tsv** is the file that we use as input for benchmarking models
- **Qasa_annotated.tsv** is the file that contains details of annotations and modifications we made with Qasa dataset. This file preserves the original QASA dataset IDs.