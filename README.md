# Text-Mining-on-Earnings-Conference-Call-Transcripts

## Overview

This repository is a companion to the Spring 2021 NLP research project at Columbia University, under supervision of Professor Patrick Houlihan. In this project, I did text analysis and text mining with regard to 188 earning call transcripts from 2016-2020. Sentiment analysis using both traditional and domain-specific dictionaries shows an overall positive sentiment across years though it falls entering the coronavirus pandemic. Five different topic extraction models are used, where LDA and LSI perform relatively better in the overall coherence and partitioning transcripts into different clusters that each focus on part of the business value chain. We also try several supervised learning models to predict profitable entry positions based on the text corpus, and the best model (random forest + bigrams TI-IDF) returns a quite satisfactory result.

In this repository, you will find three files: **sentiment analysis & exploratory text analysis**, **topic modeling**, and **research paper**, documenting our codes, outputs of modeling and analysis, and formal write-up in this text mining project.

## Project Roadmap
- **Text Preprocessing** 
Remove special characters, strip white spaces, lowercase, remove stopwords, lemmatization, remove short words, etc.<br>
- **Exploratory Text Analysis** 
For Apple, Amazon, and Google, each generate five wordclouds and five 2016-2020 time series of term-frequencies of four selected tokens<br>
- **Sentiment Analysis** 
Compare five sentiment lexicons/dictionaries/APIs while plotting 2016-2020 time series of polarities scores<br>
- **Topic Modeling** 
Compare five topic models in topic allocation<br>
- **Predictive Modeling** 
Compare five supervised models in predicting profitable entry positions<br>
