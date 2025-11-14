# Text Sentiment Analysis using Azure

🚀 Project Overview

Sentiment Analysis is a powerful NLP technique used to determine the emotional tone behind text.
In this project, Azure Text Analytics API is used to analyze text at the edge, making it suitable for real-time or low-latency scenarios.

This project can be deployed on edge devices (like Raspberry Pi) or traditional systems connected to Azure.

📌 Features

✔ Reads any input text file

✔ Connects to Azure Text Analytics endpoint

✔ Performs sentiment analysis using AI models

✔ Classifies sentiment into: Positive, Neutral, Negative, or Mixed

✔ Displays confidence scores

✔ Saves the sentiment results to an output text file

✔ Simple and modular Python code

🧠 How It Works

The system loads an input text file containing text paragraphs or sentences.

The content is sent to Azure Text Analytics API.

Azure processes the text and returns:

Overall sentiment

Confidence scores for all sentiment types

The processed results are stored in an output file for easy visualization and documentation.

📦 Tech Stack
Component	Description
Azure Cognitive Services	Text Analytics (Sentiment Analysis API)
Python 3.x	Implementation language
Azure AI Language SDK	To communicate with Azure endpoint
Edge Device / Local Machine	Optional deployment target
🛠️ Requirements

Azure Subscription

Text Analytics Resource

Endpoint URL

API Key

Python 3.x

Required libraries (install with pip):
