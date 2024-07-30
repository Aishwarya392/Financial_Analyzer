
https://github.com/user-attachments/assets/16e0c2ba-de8b-4329-a033-9af584475d67
# Financial_Analyzer
The Financial Analyzer is a tool that analyzes trade history data from a provided document with specific columns. It calculates various metrics and insights related to the trades, helping users understand patterns, performance, and potential areas for improvement. This documentation offers a detailed explanation of the project, covering its functionalities and the underlying code structure. The tool aims to assist users in making informed financial decisions based on their trade history analysis.
## Features

- **Analyze Trade History:** Input trade data to calculate metrics like Compound Annual Growth Rate (CAGR), Sharpe Ratio, Win/Loss Ratio, Maximum Drawdown, Calmar Ratio, and Sortino Ratio.
- **Visualizations:** Generate plots for cumulative returns, daily returns, continuous returns, and ROI over time.
- **Insights and Ratings:** Receive insights based on your trading data using ChatGPT.
- **Input Options:** Manual input, CSV file upload, and planned support for other file formats and API integrations.

## Installation

To set up the Financial Analyzer, follow these steps:

1. **Clone the Repository:**
   \`\`\`bash
   git clone https://github.com/sudhanshu8833/Financial_Analyzer.git
   \`\`\`

2. **Install Dependencies:**
   Navigate to the project directory and install the required packages:
   \`\`\`bash
   pip3 install -r requirements.txt
   \`\`\`

3. **Run the Server:**
   Start the application by running:
   \`\`\`bash
   python3 manage.py runserver
   \`\`\`

## Usage

1. **Prepare Trade History Data:**
   Ensure your CSV file has the following columns in this exact order:
   - \`datetime\`
   - \`stock\`
   - \`ordertype\`
   - \`price\`
   - \`quantity\`
   - \`exchange\`

2. **Upload Data:**
   Upload your trade history CSV file through the web interface or use the 'Upload Random Data' feature to test the tool.

3. **View Results:**
   The tool will analyze the data, calculate the metrics, and display the results along with visualizations and insights.

## Input Options

- **Manual Input:** Enter trade data directly through the web interface.
- **File Formats:** (Future) Support for Excel, JSON, and database integrations.
- **API Integration:** (Future) Directly connect to brokerage APIs to fetch trade history.

## Code Overview

The project is structured into several sections:

1. **Imports:** Necessary libraries like \`pandas\`, \`numpy\`, and \`matplotlib\`.
2. **Function Definitions:** Calculations for financial metrics.
3. **Data Processing:** Loading and preparing data for analysis.
4. **Financial Analysis:** Applying functions to generate results.
5. **Plotting:** Visualizations for various financial metrics.

## Dependencies

The Financial Analyzer relies on the following dependencies:

- \`pandas\`
- \`numpy\`
- \`matplotlib\`
- \`openai\`

Install these dependencies using:
\`\`\`bash
pip3 install -r requirements.txt
\`\`\`

## Conclusion

The Financial Analyzer is a valuable tool for traders and investors, providing detailed insights into trading performance. By calculating essential metrics and visualizing data, it helps users make informed decisions and optimize their trading strategies.



