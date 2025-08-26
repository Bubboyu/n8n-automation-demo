# AIS Cloud PC Customer Feedback Automation (n8n Workflow)

This n8n workflow automates the collection, processing, and analysis of customer feedback data for AIS Cloud PC from public social media platforms. The goal of this workflow is to streamline feedback aggregation and provide actionable insights to improve product marketing strategies.

## Workflow Overview

1. **Data Collection**  
   - Automatically fetches customer feedback data from specified social media sources at regular intervals.

2. **Data Processing**  
   - Cleans and organizes raw feedback for analysis.  
   - Splits large datasets into manageable batches.

3. **Analysis & Insights**  
   - Processes feedback using AI (Google Gemini Chat model) to categorize, summarize, and extract key insights.  
   - Outputs processed results into structured formats like Google Sheets or Airtable for further review.

4. **Automation**  
   - The workflow runs automatically based on a schedule.  
   - Includes batching, waiting, and looping nodes to handle large datasets efficiently.

## Key Features

- Workflow automation for customer feedback collection and analysis.  
- Integration with AI models for intelligent insights.  
- Output to spreadsheets and databases for easy visualization and reporting.  
- Modular design for easy updates and customization.

## Technologies Used

- [n8n](https://n8n.io/) (Workflow automation)  
- Google Gemini Chat Model (AI processing)  
- Google Sheets & Airtable (Data storage & reporting)  

## How to Use

1. Import the `n8n-workflow.json` file into your n8n instance.  
2. Adjust the data source nodes to point to your desired social media platforms or APIs.  
3. Configure the AI processing node if needed.  
4. Activate the workflow and let it run according to the schedule.

---

This workflow demonstrates automation, data handling, and AI-powered insights in a marketing context, making it a strong portfolio project for process automation, analytics, and generative AI applications.
