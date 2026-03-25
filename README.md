# Auto-Sales-Ranker--Automate-Your-Emails-Of-Sub-Companies-Sales-
Automated Python system to generate, rank, and analyze sales data from multiple companies, create a priority list of top performers, and send customized emails using an end-to-end pipeline.
📌 AutoSalesRanker

An end-to-end Python automation pipeline that simulates, analyzes, ranks, and communicates with top-performing sub-companies based on sales data.

🚀 Overview


Managing and evaluating the performance of hundreds of sub-companies manually is inefficient and error-prone.

In large organizations, sub-companies regularly report their sales data via email or other channels. Identifying top-performing companies, prioritizing them, and communicating recognition requires significant manual effort.

This project aims to solve the problem by:

Automatically collecting or simulating company sales data
Ranking companies based on performance
Generating a priority list of top performers
Sending automated, customizable emails to selected companies

The goal is to build a fully automated, scalable system that reduces manual intervention and improves decision-making efficiency.


Solution :-


AutoSalesRanker is designed for organizations managing multiple sub-companies. It automates the process of:

Generating or ingesting company sales data
Ranking companies based on performance
Creating a priority list of top performers
Automatically sending customized congratulatory emails

This project demonstrates how business intelligence and automation can be combined into a single workflow.

🧩 Features

✅ Generate dataset of 200–300 companies
✅ Rank companies by total sales
✅ Create Top-N priority list (default: Top 50)
✅ Export results (CSV / Excel)
✅ Automated email system
✅ User-defined email content
✅ Fully compatible with Google Colab

⚙️ Tech Stack
Python
Pandas
SMTP (Email Automation)
Google Colab
🏗️ Project Architecture
               Data Generation → Data Processing → Ranking → Priority Selection → Storage → Email Automation
📊 Workflow
Generate or collect company sales data
Sort and rank companies by sales
Extract top 50 companies
Save priority list
Send automated emails to selected companies
🖥️ Installation & Usage
1. Clone the Repository
2. Run in Google Colab
Open the notebook in Colab
Run all cells step-by-step
3. Provide Inputs

You will be prompted for:

Email Subject
Email Message
Sender Email
App Password
📁 Output
priority_list.csv → Top 50 companies
priority_list.xlsx → Excel version
Automated emails sent to selected companies
⚠️ Security Notes
Use App Passwords, not your real email password
Do not expose credentials in code
Consider using environment variables in production
🚀 Future Improvements
📥 Real email parsing using IMAP
🤖 AI-based data extraction (via OpenAI APIs)
☁️ Cloud deployment (AWS / GCP)
📊 Dashboard integration
⏱️ Scheduled automation
💡 Use Cases
Corporate performance tracking
Sales analytics automation
Multi-branch business management
Executive reporting systems
👤 Author

Md Mofid Umar (Developer)

⭐ Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

📜 License

MIT License
