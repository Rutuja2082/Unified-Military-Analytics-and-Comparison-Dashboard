# 🛡️ Unified Military Analytics & Comparison Dashboard

Web Scraping |Data pipeline | Analytics Project

## 📌 Project Overview

The Unified Military Analytics & Comparison Dashboard is a data-driven project designed to collect, process, and analyze global military information from GlobalFirepower.com.

This project transforms raw, unstructured web data into a clean, structured dataset that can be used for analytics, visualization, and strategic comparison.

The solution follows a multi-step data processing workflow, where raw web data is extracted, transformed, merged, and stored as a structured dataset ready for analytical use.

## 🎯 Project Objectives

📥 Collect military-related data from multiple web sources

🧹 Clean and standardize raw scraped data

🔄 Merge multiple datasets into one unified structure

📊 Prepare data for analytics and dashboard visualization

⚙️ Automate the entire data extraction and processing workflow

🗂 Organize processed data into a structured dataset for downstream analysis

### 🧠 What This Project Covers

✔ Country-wise military data
✔ Manpower & personnel strength
✔ Equipment and force categories
✔ Structured CSV output for analytics
✔ Automated data collection and processing workflow
✔ Modular scripts for scalable data processing

### 🧰 Tech Stack & Tools

| Tools / Technology | Purpose                        |
| ------------------ | ------------------------------ |
| Python             | Core programming language      |
| Requests           | Fetching web data              |
| BeautifulSoup      | Parsing HTML content           |
| Pandas             | Data cleaning & transformation |
| Git & GitHub       | Version control                |
| VS Code            | Development environment        |

### 🔄 Workflow Overview

1️⃣ Collect URLs
Store all GlobalFirepower metric URLs in a text file.

2️⃣ Scrape Data
Use Python + BeautifulSoup to extract data from each page.

3️⃣ Data Cleaning & Standardization
Remove symbols, normalize values, handle missing entries, and convert data into consistent formats.

4️⃣ Merge & Structure Data
Combine multiple extracted metrics into a unified tabular structure.

5️⃣ Generate Structured Dataset
Prepare a clean dataset suitable for analytical processing and visualization.

6️⃣ Export Output
Save the final processed data as a CSV file for reporting and dashboard creation.

### 📊 Sample Output (Preview)

| Country | Rank | Active Personnel | Reserve   | Equipment |
| ------- | ---- | ---------------- | --------- | --------- |
| India   | 4    | 1,455,550        | 1,155,000 | 4,000+    |
| USA     | 1    | 1,390,000        | 850,000   | 5,000+    |

### 🧠 Key Learnings

• Web scraping using real-world HTML structures
• Handling inconsistent and missing data
• Designing a structured workflow from raw web data to a usable dataset
• Writing clean and reusable Python scripts
• Managing version control using Git & GitHub
• Preparing datasets for analytical and visualization tools

### 👤 Author

Rutuja Sadik Ghodake

⭐ If you found this project helpful, feel free to explore or contribute.
