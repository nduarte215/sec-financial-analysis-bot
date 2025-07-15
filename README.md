# SEC Financial Chatbot 

A conversational AI chatbot designed to extract, analyze, and summarize financial data from SEC 10-K filings. This project leverages Natural Language Processing (NLP) and data parsing techniques to make SEC reports more accessible and user-friendly.

## 💼 Use Case

Manually analyzing lengthy SEC filings can be time-consuming and error-prone. This project automates the extraction of meaningful financial data—revenues, expenditures, liquidity, and operational details—from SEC-formatted documents. It's ideal for:
- Accountants reviewing corporate reports
- Financial analysts looking for key metrics
- Consultants building dashboards or reports
- 
##  Features

-  **Financial Data Extraction**: Parses key financial metrics (Revenue, Net Income, etc.) from 10-K reports.
-  **Chatbot Interface**: Answers natural language questions about company performance using extracted data.
   **LLM Integration**: Utilizes large language models to interpret and summarize financial text.
-  **Structured Output**: Saves results to Excel for further analysis or reporting.

##  Project Structure
.
├── sec.Financial_Data_Extraction.ipynb # Data extraction notebook
├── sec_Financial_Chatbot (1).ipynb # Chatbot interaction notebook
├── sec_financial extractions.xlsx # Extracted financial data
├── README.md # This file
├── requirements.txt # Python dependencies
└── LICENSE # Project license

##  How It Works

1. **Data Extraction**:
   - Parses raw SEC 10-K filings (via EDGAR or local input).
   - Identifies key sections using regular expressions and section headers.
   - Stores data in structured format.

2. **Chatbot Module**:
   - Loads extracted financial data.
   - Accepts user queries (e.g., "What was the net income in 2022?").
   - Returns contextually relevant answers using NLP logic.

3. **LLM Enhancement** *(optional)*:
   - Can be extended with OpenAI/GPT APIs for deeper insights.

##  Sample Questions

- “How did the company’s revenue change in 2022?”
- “What are the main expenses reported?”
- “Summarize the risk factors section.”

##  Future Improvements

- Integrate real-time EDGAR scraping using API
- UI/UX for non-technical users
- Multilingual chatbot capability
- Add RAG model integration for better document comprehension
- Deploy a Streamlit chatbot to answer financial questions
- Build APIs to pull real-time SEC filings
- Translate insights into Time-series visualizations & dashboards


** Author**
I'm an AI + finance consultant leveraging automation to simplify complex workflows for small businesses and accounting teams. This project reflects my mission to empower others with tools that save time and increase accuracy.
Developed by Nasly Duarte — AI Student & Financial Operational Accounting
Contact: www.linkedin.com/in/naslyduarte

##  Requirements

Install dependencies:

```bash
pip install -r requirements.txt

##  Requirements

Install dependencies using:

Include all the packages used in both notebooks:

```txt
pandas
openai
tiktoken
langchain
numpy
scikit-learn
nltk
spacy
python-dotenv
```bash
pip install -r requirements.txt


