AI Website Sentiment Analyzer

An end-to-end AI-powered sentiment analysis system that ingests website data, processes text pipelines, performs multi-model sentiment classification (VADER + BERT), and visualizes actionable insights through interactive dashboards.

This project demonstrates how AI models can be integrated into automated data workflows for real-world monitoring, reporting, and business intelligence use cases.

🔎 System Overview

This tool follows a structured AI workflow:

User Input (URL / CSV)
        ↓
Web Scraping Layer (Selenium)
        ↓
Text Cleaning & Preprocessing Pipeline
        ↓
Dual Sentiment Engine (VADER + BERT)
        ↓
Aggregation & Scoring Logic
        ↓
Visualization & Reporting Layer
        ↓
CSV Export / Reusable Dataset


The architecture is modular, making it adaptable for API integration or automation pipelines.

🚀 Core Features
🌐 Website Scraping Engine

Extracts structured text content using Selenium

Handles dynamic pages

Designed for extensibility into larger ETL workflows

🧠 Hybrid Sentiment Engine

Rule-based sentiment detection (VADER)

Transformer-based contextual sentiment analysis (BERT)

Aggregation logic to compare and validate outputs

Structured output ready for downstream automation

📊 Insight Visualization

Sentiment distribution (pie charts & bar graphs)

Word cloud generation for keyword analysis

Data export for reporting and analytics workflows

🖥 Interactive GUI

Built using Tkinter

Allows non-technical users to run AI analysis

Demonstrates applied AI system usability

💼 Business Use Cases

This system can be adapted for:

Customer feedback monitoring

Brand sentiment tracking

Competitor analysis

Automated reputation monitoring

Social listening pipelines

Support ticket triaging (with API extension)

The modular design allows integration into CRM systems, reporting dashboards, or automation platforms.

🛠 Debugging & Optimization Work

Structured logging implemented for traceability

Handled scraping edge cases (dynamic content failures)

Implemented preprocessing safeguards for malformed input

Optimized inference workflow for reduced processing latency

Designed modular architecture for easier troubleshooting and upgrades

This project emphasizes independent debugging, model orchestration, and system-level integration.

📦 Installation
git clone https://github.com/Vaibhav5012/AI-Website-Sentiment-Analysis
cd AI-Website-Sentiment-Analysis


(Optional)

python -m venv venv
source venv/bin/activate


Install dependencies:

pip install -r requirements.txt

▶ Usage

Run:

python main.py


Inside the GUI:

Enter a website URL to scrape and analyze

Or load an existing CSV file for batch sentiment evaluation

Export processed results for reporting or further automation

🧩 Project Structure
.
├── main.py
├── sentiment_engine/
├── scraper/
├── visualizer/
├── requirements.txt
└── README.md


(Architecture is modular and can be extended into API-based systems.)

🧠 Technical Stack

Python

Selenium

VADER

BERT (Transformers)

Tkinter

Matplotlib / WordCloud

Pandas

🔮 Future Enhancements

REST API layer for integration with external systems

Webhook-based automation triggers

Batch processing support

Cloud deployment option

Database integration for persistent monitoring

License

MIT License
