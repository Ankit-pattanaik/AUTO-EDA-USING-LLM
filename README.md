# AUTO-EDA-USING-LLM
A web-based tool for automated Exploratory Data Analysis (EDA) powered by Large Language Models (LLMs) and visualizations. Upload a CSV dataset to generate detailed data summaries, handle missing values, gain AI-driven insights, and visualize distributions and correlations interactively using Gradio.

🚀 Features
Automated Data Cleaning:
Fills missing values in numeric columns with the median.
Fills missing values in categorical columns with the mode.

Comprehensive Data Summary:
Generates statistical summaries for all columns (numeric and categorical).
Reports missing values after cleaning.
AI-Powered Insights:
Uses the deepseek-r1 model via Ollama to analyze data summaries and provide meaningful insights.

Data Visualizations:
Creates histograms with KDE for numeric columns.
Generates a correlation heatmap for numeric variables

Interactive Web Interface:
Built with Gradio for easy dataset upload and result exploration.
Displays EDA reports and visualizations in a user-friendly gallery format.

🛠️ Installation
Prerequisites
Python 3.8 or higher
Ollama installed and running with the deepseek-r1 model
A CSV dataset for analysis
