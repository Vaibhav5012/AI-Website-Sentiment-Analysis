# AI Website Sentiment Analyzer

This project is an AI-powered tool that scrapes text data from websites, analyzes sentiment using both VADER and BERT models, and visualizes the results through charts and word clouds. It also includes a GUI for easy interaction.

## Features

- **Website Scraping:** Extracts text content from web pages using Selenium.
- **Sentiment Analysis:** Combines VADER and BERT models for more accurate sentiment detection.
- **Data Visualization:** Generates pie charts, bar graphs, and word clouds to represent sentiment distribution.
- **CSV Export & Analysis:** Saves scraped data to a CSV file and analyzes existing CSV files.
- **Interactive GUI:** Built with Tkinter for user-friendly operation.

## Debugging & Optimization Work

- Resolved model convergence instability
- Reduced inference time by X%
- Handled edge-case input failures
- Implemented logging for traceability


## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Vaibhav5012/AI-Website-Sentiment-Analysis
   cd ai-website-sentiment-analyzer
   ```

2. Create a virtual environment (optional but recommended):

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the application:

   ```bash
   python main.py
   ```

2. In the GUI:

   - **Scrape Website & Save CSV:** Enter a URL to scrape and analyze its content.
   - **Load and Analyze CSV:** Load an existing CSV file for sentiment analysis.

## Project Structure

```
.
├── main.py             # Main application code
├── README.md           # Project documentation
└── requirements.txt    # List of Python dependencies
```

## Requirements

Ensure you have Python 3.7+ installed.

## Dependencies

See `requirements.txt` for the full list of libraries.

## Contributing

Feel free to fork the repo, submit pull requests, or open issues for improvements or bug fixes.

## License

This project is licensed under the MIT License.

---

Happy coding! 🚀


