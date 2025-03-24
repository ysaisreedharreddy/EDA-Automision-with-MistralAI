Overview of the Automated EDA Tool Using Gradio
This application leverages Gradio, an open-source Python library, to create a web-based interface that automates the exploratory data analysis of uploaded datasets. It's designed to simplify data analysis tasks by providing instant visualizations and insights without needing manual scripting.

Key Features:
Automated Data Cleaning: The application automatically handles missing values by filling them with the median for numeric columns and the mode for categorical columns.
Data Summarization: Generates a comprehensive summary of the dataset, including statistics like mean, median, mode, and standard deviation.
AI-Powered Insights: Utilizes an AI model (from Ollama) to analyze the dataset summary and provide higher-level insights, enhancing the analytical process by predicting potential trends and anomalies.
Dynamic Visualizations: Automatically generates histograms for numeric columns and a correlation heatmap to visualize relationships between variables.

Technical Stack:
Python for backend processing.
Pandas for data manipulation.
Matplotlib and Seaborn for generating statistical graphics.
Gradio for creating the web interface that users interact with.

How It Works:
The user uploads a CSV file through the Gradio interface.
The backend processes this file, cleans the data, and generates statistical summaries.
AI-driven insights are derived from the summary.
Visualizations are created for both distribution of individual variables and correlations among them.

The results, including textual insights and visual plots, are displayed on the web interface
