Multilingual Text Intelligence Agent (WIP)
Overview

This repository hosts an ongoing project focused on multilingual text intelligence — combining exploratory data analysis, sentiment modeling, topic extraction, and early work on automated reporting agents.
The aim is to build an end-to-end pipeline that interprets large-scale multilingual text data with both statistical and generative methods.

Current Progress
1. Data Cleaning and EDA

Removed HTML tags, URLs, emojis, and excess punctuation.

Normalized text casing and spacing.

Conducted exploratory analysis on duplicates, language mix, and word frequency.

Produced a cleaned dataset for modeling.

2. Sentiment Analysis

Base model: cardiffnlp/twitter-xlm-roberta-base-sentiment.

Multilingual coverage (English, French, Arabic).

Implemented batch inference via Hugging Face pipeline.

Outputs:

sent_label: sentiment class

sent_score: model confidence

3. Topic Modeling

Implemented BERTopic for cross-language topic discovery.

Used multilingual embeddings (Sentence-Transformers).

Preliminary exploration of topic distribution and interpretability.

Work in Progress

Building an agentic reporting layer to generate structured summaries and insights.

Refining multilingual text normalization and translation alignment.

Improving sentiment calibration across mixed-language datasets.

Integrating all stages into a reproducible analysis pipeline.
