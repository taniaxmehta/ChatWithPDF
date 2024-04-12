# ChatWithPDF App

## Introduction

ChatWithPDF is a Python application where you can communicate and ask questions regarding the information present in the PDFs that the LLM is using. Developed for LLM and IR practices.

## How It Works

1. PDF Loading: Reading the PDF documents, extracting text content.

2. Text Chunking: Text is broken down into 'chunks'

3. Language Model: Language model develops vector representations of the chunks

4. Similarity Matching: Question is compared to text chunks, and similar chunks are matched.

5. Response Generation: Selected chunks are passed to language model, and response is generated

## Installation

Install dependencies:

```
pip install -r requirements.txt
```

Get API key from OpenAPI

```commandline
OPENAI_API_KEY=your_secrit_api_key
```

## Usage

Run

```
streamlit run app.py
```

Load your PDFs

Ask away!
