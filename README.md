# Vantager Technical Assessment

This repository contains Li Yao's solution for the Vantager Technical Assessment. After exploring various NLP techniques, we successfully identified 22 needles from the given haystack, with an inference time of only 15-20 seconds. 

## Table of Contents

├── README.md
├── input-datasets  # NOT UPLOAD TO GITHUB
│   └── haystack.txt
├── companies.csv   
├── deliverable.ipynb
└── presentation.ipynb 

## Deliverables
* `companies.csv`: This CSV file contains all the needles extracted from the provided haystack.
* `deliverable.ipynb`: This notebook implements the core functionality required for the task.
* Recorded presentation can be found here [Presentation](https://console.cloud.google.com/home/dashboard)

Note: `presentation.ipynb` illustrates the intermediate steps of `deliverable.ipynb`, and is intended for presentation purposes.

## Comments
 To address this task, we used the OpenAI API to transform unstructured data into structured data. To replicate the results, you'll need your own OpenAI API key, which can be obtained here: [OpenAI](https://platform.openai.com/settings/profile?tab=api-keys)
