# LLM Web Content Analyzer

This project implements a domain-aware LLM pipeline that scrapes web content and performs context-grounded analysis using Google Gemini.

## Features
- Web content scraping and cleaning
- LLM-based summarization of long-form content
- Keyword extraction to identify important concepts
- Domain-aware question answering restricted to source context
- Hallucination control through strict context enforcement
- Confidence scoring to assess answer reliability
- Evidence grounding from the source content

## Tech Stack
- Python
- Google Gemini API
- Jupyter Notebook
- Web scraping using BeautifulSoup and Requests

## How It Works
1. Scrapes textual content from a given URL
2. Cleans and preprocesses the extracted data
3. Generates summaries and keywords using an LLM
4. Answers user questions strictly from the provided context
5. Evaluates grounding and confidence of generated responses

## Use Case
This project helps ensure trustworthy and explainable LLM outputs by verifying responses against source content. It is useful for research, content analysis, and studying hallucination behavior in large language models.

## Security Note
API keys are managed using environment variables and are not committed to the repository.
