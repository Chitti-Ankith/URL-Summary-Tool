# URL-Summary-Tool
This URL summarization system aims to provide users with quick insights into the content of a webpage without having to read through the entire page.

This app is powered by EvaDB's Python API and ChatGPT UDF.

## Overview
The URL Summarization System leverages the capabilities of OpenAI's language model and EvaDB to automatically generate concise and informative summaries of web content linked by URLs. This system aims to provide users with quick insights into the content of a webpage without having to read through the entire page.

## Dependencies

This app is powered by EvaDB's Python API and ChatGPT UDF.

## Setup
Ensure that the local Python version is >= 3.8. Install the required libraries:

```bat
pip install -r requirements.txt
```

## Usage
Run script: 
```bat
python url_summary.py
```

## Example

```bat
🔮 Welcome to EvaDB! This app lets you summarize the content of any URL.

🔑 Enter your OpenAI API key: <API_KEY>
🔗 Enter the URL (press Enter to use our default URL) : <URL_here>

⏳ Loading URL data

⏳ Generating Summary (may take a while)... 

<GENERATED_SUMMARY_IN_250-300_WORDS>

✅ Session ended.
===========================================

```
