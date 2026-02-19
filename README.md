# Ollama_VisionaryEDA

An AI-integrated Exploratory Data Analysis (EDA) application that automates dataset understanding using Large Language Models (LLMs). Upload a CSV file and instantly get statistical summaries, visualizations, and AI-generated insights.

## -Features

📂 Upload any CSV dataset

🧹 Automatic missing value handling

📈 Descriptive statistics generation

📊 Histogram plots for numeric features

🔥 Correlation heatmap visualization

🤖 AI-powered insights using Gemma 2B (via Ollama)

🌐 Interactive web interface built with Gradio

## -Tech Stack

Python

Pandas

Matplotlib

Seaborn

Gradio

Ollama (Gemma 2B LLM)

##  -Installation
1️⃣ Clone the Repository
git clone https://github.com/your-username/LLM-Powered-EDA-App.git
cd LLM-Powered-EDA-App

2️⃣ Install Required Libraries
pip install gradio pandas matplotlib seaborn ollama

3️⃣ Install and Run Ollama

Download Ollama from:
👉 https://ollama.com/download

Pull the Gemma model:

ollama pull gemma:2b


Make sure Ollama is running locally.

## -Run the Application
python app.py


After running, a local Gradio link will open in your browser.

## -How It Works

Upload a CSV dataset.

The system:

Cleans missing values (median/mode)

Generates statistical summaries

Creates visualizations

The LLM analyzes the summary and provides human-readable insights.

Results are displayed in the web interface.

## -Output

EDA Report (Statistics + Missing Values)

AI-Generated Insights

Histogram Plots

Correlation Heatmap

## -Project Objective

To enhance traditional Exploratory Data Analysis by integrating Large Language Models that convert raw statistical outputs into meaningful insights, improving efficiency and accessibility in data analysis workflows.
