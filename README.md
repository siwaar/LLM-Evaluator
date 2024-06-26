# LLM-Evaluator

This project was developped as a part of the 24+ hours [Mistral AI Paris Hackathon](https://mistralparishack.devpost.com/).
This event is hosted by Mistral AI, Cerebral Valley & Station F.
![alt text](img/header.png)

#  Comprehensive AI Chatbot Evaluation Platform 

Welcome to the MistralJudge repository! This project is designed to provide comprehensive evaluations for AI chatbots, customized for various industry use cases. MistralJudge leverages the power of Mistral AI models and provides an interactive user interface built with Streamlit.

![alt text](img/mistraljudge.png)

## Table of Contents

- [Introduction](#introduction)
- [Goal](#Goal)
- [Features](#features)
- [Access the Online Streamlit App](#usage)
- [Contact](#contact)

## Introduction

As AI becomes more integrated into customer interactions in travel, medical service, finance, and various other industries, ensuring its reliability, fairness, and effectiveness is a major challenge. MistralJudge addresses these issues by providing a platform that systematically assesses and improves AI chatbot models. This tool helps businesses deploy AI systems that deliver accurate, unbiased, and safe responses.

## Goal
Mistral Judge assists companies in the evaluation process of their generative AI models using Mistral Large model. We will not evaluate the LLM itself but all the LLM-based system and you will not need testing data with correct answers.
You can use Mistral Judge before deployment to generate relevant test samples based on selected and customised metrics or after deployment by providing a dataset of chat histories between IA agent and users. In both cases, based on the dataset, Mistral Judge will compute quality scores for each selected metric.


## Features

- **Customizable Evaluation Metrics:** Define and prioritize metrics such as accuracy, relevance, bias detection, and safety.
- **Automated Test Sample Generation:** Generate relevant test samples based on user-selected metrics.
- **Chat History Analysis:** Evaluate entire chat histories to assess human satisfaction and identify patterns.
- **Real-Time Feedback:** Continuous monitoring and immediate insights for rapid improvement.
- **Interactive Interface:** Streamlit application for easy configuration and detailed analysis.


## Usage 
### Access the Online Streamlit App
Open your web browser and navigate to the URL https://garkavem-mistral-genies-hackathon-main-lipp61.streamlit.app/.

After providing your Mistral API key, you can use the interactive interface to configure evaluation parameters, generate test samples, and view analysis results.
#### First part: 
![alt text](img/streamlit_interface1.PNG)

Based on the selected metrics, here are some examples of generated user inputs
![alt text](img/dataset_generation1.png)

#### Second part:
![alt text](img/Chatbot_Analysis1.PNG)
Example of evaluation:
![alt text](img/Chatbot_Analysis.PNG)


## What's next for MistralJudge?
We believe this area represents a significant and important task that will grow rapidly alongside the business's needs and expansion. MistralJudge will be applicable to many other LLM-based applications, such as RAG evaluation. Additionally, we can enhance our project by allowing users to add documents with guidelines, from which MistralJudge can extract relevant metrics. Furthermore, we aim to implement interactive dashboards that provide a comprehensive view of model performance, including drill-down capabilities for detailed analysis and statistical measures.

## Contact

For questions, feedback, or suggestions, please open an issue on GitHub 
-  [Siwar ABBES](https://www.linkedin.com/in/siwar-abbes/)
-  [Karina Ashurbekova ](https://www.linkedin.com/in/karina-ashurbekova/)
-  [Xinyu (Judy) LAI](https://www.linkedin.com/in/xinyu-lai-hec-paris/)
-  [Marie Garkavenko](https://www.linkedin.com/in/garkavenko-m/)