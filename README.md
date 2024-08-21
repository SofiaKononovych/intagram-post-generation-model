## Instagram posts generating AI-model

Link to the model : https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.2

## To launch UI and test locally:
Log in to your Hugging Face profile

Go to Settings/Access Tokens/New token\

Generate a new token with some name of type Read and !save! it somewhere

Open this notebook in Google Colab

Go to variable HF_TOKEN, and pass your generated token as its value

Grant access to this notebook by swiping the corresponding Notebook access slider

Go to Runtime/Change runtime type, and choose the T4 GPU option there

Go to Files/Upload to session storage, and upload the scraped Instagram data there

Run the notebook and keep calm: it may take some time.

## Tools and techniques:
Mistral-7B-v0.2 text-generation model, Apify, torch, gradio
