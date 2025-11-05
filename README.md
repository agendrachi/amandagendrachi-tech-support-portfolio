🧩 Amanda Gendrachi – Technical Support Portfolio

Welcome!
This portfolio highlights a few of my practical projects demonstrating technical troubleshooting, scripting, and system management skills. Each example showcases my ability to work with Python, SQL, Linux command-line tools, and basic cybersecurity practices — the same core skills I bring to a Technical Support Analyst role.

🧹 1. CSV Data Cleaner (Python)

Skills demonstrated:
Python scripting · Data cleaning · Automation · Pandas library

This simple project loads a raw CSV file, removes duplicates and empty values, and standardizes text formatting. It then exports a clean version of the data — automating what would normally be a manual data-prep task.

Key features:

Reads and writes CSV files using pandas

Handles missing or inconsistent values

Normalizes text fields for uniform formatting

Sample command:

python3 clean_data.py


Result: A cleaned dataset saved as client_data_cleaned.csv ready for analysis or import into other systems.

🧠 2. SQL Order Analytics (SQLite)

Skills demonstrated:
SQL queries · Database design · Data aggregation · Logical analysis

Using a small SQLite database, this project stores mock customer order data and retrieves insights with SQL queries.

Highlights:

Created and populated tables directly in SQLite

Queried total spending per customer

Practiced grouping, ordering, and filtering results

Example query:

SELECT customer, SUM(price) AS total_spent
FROM orders
GROUP BY customer
ORDER BY total_spent DESC;


Result: Clear summaries of customer purchase data, demonstrating database navigation and SQL command fluency.

💻 3. Linux CLI Practice

Skills demonstrated:
Command-line navigation · File management · Permissions · Environment setup

This project records a series of Linux terminal commands showing file handling, permissions, and environment setup for Python projects.

Tasks included:

Creating and editing files using CLI commands

Managing directories and logs

Setting file permissions securely (chmod 600, chmod 700)

Initializing a Python virtual environment and installing packages

Result: A documented workflow showing familiarity with Linux shell, directory structure, and secure setup practices.

🔒 4. Secure Script Execution (Python + Linux)

Skills demonstrated:
Environment variables · Security practices · Safe configuration management

This project demonstrates reading environment variables securely rather than hardcoding credentials inside scripts.

Example code:

import os

api_key = os.getenv("API_KEY")

if not api_key:
    raise ValueError("API key not found! Set API_KEY in environment variables.")
else:
    print("✅ Secure environment variable loaded successfully.")


Why it matters:

Prevents sensitive data exposure

Demonstrates awareness of basic cybersecurity principles

Follows best practices for secure development environments

Result: A working script that validates secure configuration handling in Python.

⚙️ 5. About This Portfolio

This collection of projects reflects my technical support foundation — troubleshooting systems, writing scripts to solve problems, and following security-conscious practices.

I created these examples to demonstrate:

Problem-solving through automation

Comfort with technical tools and command-line environments

A proactive, continuous-learning approach

I’m always expanding my technical skills and enjoy finding efficient, practical solutions to complex problems.

Contact:
📧 agendrachi92@gmail.com

🌍 LinkedIn
 (Add your link once ready)
