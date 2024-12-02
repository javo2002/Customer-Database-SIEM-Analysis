# Real-World Customer Database Analysis

This project demonstrates how to manage customer data using a SQLite3 database and analyze it using Splunk's powerful indexing, reporting, and visualization tools. The project is designed to simulate real-world data handling and monitoring for a fictitious company, Koda.

## Features
- **Four-tier SQLite Database:** Organizes and processes customer data dynamically.
- **Real-time Simulation:** Batch data insertion with delays to mimic real-time operations.
- **Splunk Integration:** Logs forwarded to Splunk for indexing, visualization, and alerting.
- **Security Insights:** Analysis of database vulnerabilities and insights into incident response.

## Repository Structure
- **`src/`**: Contains Python scripts for database and Splunk operations.
  - `database/`: Database setup, insertion logic, and logs.
  - `splunk/`: Configuration and examples for integrating with Splunk.
- **`reports/`**: Documentation of project outcomes and data insights.
- **`diagrams/`**: Visual representation of the project architecture.
- **`dashboards/`**: Example configurations for Splunk dashboards.

## Project Objectives
1. Design and implement a four-tier SQLite database for customer data.
2. Simulate real-time data insertion and logging.
3. Forward logs to Splunk for analysis and visualization.
4. Utilize Splunk's features for reporting and alerting.

## How to Use
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/Koda-Customer-Database-Analysis.git
   cd Koda-Customer-Database-Analysis
