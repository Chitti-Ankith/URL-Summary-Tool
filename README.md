# URL-Summary-Tool
This URL summarization system aims to provide users with quick insights into the content of a webpage without having to read through the entire page.

This app is powered by EvaDB's Python API and ChatGPT UDF.

If you don't have an OpenAI key, follow the instructions below:

- Login to [OpenAI](<https://openai.com/>) website and go to the API section. 
- Click the `Personal` tab on the top right of your screen, and navigate to `View API keys` section.
- Click on `Create new secret key` button, give a nickname and copy the API Key that shows up.
- Make sure to backup the key somewhere and keep it safe since OpenAI will not show you the complete key again.

Voila! You can now use your very own API key for using OpenAI API's within your applications.

**NOTE** : Free accounts have a 15$ API limit passing which you will either have to create a new account or take the premium subscription.

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
