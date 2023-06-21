# Health Misinformation Dataset

This repository contains a subset of the TREC Health Misinformation 2020 and CLEF eHealth 2020 datasets, specifically focusing on the indexing subset, training, and testing data. These datasets are valuable resources for research and development in the field of health misinformation detection and information retrieval.

# Introduction
The TREC Health Misinformation and CLEF eHealth competitions are held annually to promote the development of effective techniques for detecting health misinformation and improving information retrieval in the medical domain. These datasets consist of a large collection of documents related to health topics, along with various annotations and relevance judgments.


# Datasets
## TREC Health Misinformation 2020
The TREC Health Misinformation 2020 dataset focuses on identifying and assessing the credibility of health-related claims. It contains a collection of documents from Common Crawl. The dataset labels includes relevance such as Topicality, Answer and Credibility.

## CLEF eHealth 2020
The CLEF eHealth 2020 dataset is designed to facilitate research in medical information retrieval. The dataset provides relevance judgments for information retrieval tasks, allowing researchers to evaluate the effectiveness of their retrieval algorithms.


# Folder Structure

This repository follows a specific folder structure for TREC Health Misinformation 2020 and CLEF eHealth 2020 subset:

```
├── TREC
│   ├── indexing
│   │   ├── Trec2020_1M_docno.csv
│   └── train
│   │   ├── train_trec_qid.csv
│   └── test
│       ├── test_trec_qid.csv
├── CLEF
│   ├── indexing
│   │   ├── CLEF2020_1M_docno.csv
│   └── train
│   │   ├── train_clef_qid.csv
│   └── test
│       ├── test_clef_qid.csv
```


* The `indexing` folder contains the documents IDs for both TREC Health Misinformation 2020 and CLEF eHealth 2020 datasets, specifically used for the indexing phase.
* The `train` folder includes the training data for both datasets, which can be used to train models or develop algorithms.
* The `test` folder consists of the testing data for evaluation purposes.

Please note that this repository only contains a subset of the original datasets, focusing on the aforementioned subsets.

# License

The [TREC Health Misinformation 2020](https://trec-health-misinfo.github.io/2020.html) and [CLEF eHealth 2020](https://clefehealth.imag.fr/?page_id=185) datasets are typically released under specific licenses. Please refer to the original datasets' documentation and licensing terms for more information.

# Acknowledgements

We would like to acknowledge the organizers and contributors of the TREC Health Misinformation and CLEF eHealth competitions for providing the datasets and fostering research in health information retrieval and misinformation detection.

If you find this subset of datasets useful, consider referencing the original TREC Health Misinformation 2020, CLEF eHealth 2020 publications and giving credit to the respective organizers.


