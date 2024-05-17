# Question Answering with Retrieval Augmented Generation

This repository contains an implementation of a Retrieval Augmented Generation (RAG) system for question answering using the CRAG dataset and the Llama3 8B instructed model.

## Overview

The RAG system combines a retrieval component and a language model to generate accurate and contextually relevant answers to questions. The retrieval component searches a corpus of documents to find relevant passages related to the input question. These retrieved passages are then used to condition the language model during the generation process, providing the necessary context to produce a well-informed response.

## Dataset

The CRAG (Comprehensive RAG) Dataset is utilized for building the RAG. This dataset includes question-answer pairs spanning five domains: Finance, Sports, Music, Movies, and Open Encyclopedia. The diverse domains cover a spectrum of information change rates, from rapid (Finance and Sports) to gradual (Music and Movies) and stable (Open Encyclopedia).

## Components

The project consists of the following main components:

1. **RAG Pipeline**: The core implementation of the Retrieval Augmented Generation system is contained in the `RAG_pipeline_final.ipynb` Jupyter Notebook. This notebook includes the retrieval and generation stages, utilizing Llama3, Faiss, and SentenceTransformers for efficient retrieval and context-aware generation.

2. **Data Cleaning Pipeline**: The `data_cleaning_pipeline.ipynb` Jupyter Notebook handles the data cleaning and preprocessing steps required for the CRAG dataset.

## Setup

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/RavicharanN/CRAG-Benchmark.git