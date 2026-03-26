# AI-Case-Assistant
The objective of this project is to build an AI-assisted case management system within Microsoft Dynamics 365 Customer Service that automatically analyzes customer support cases and generates AI-powered summaries and insights to assist support agents in resolving issues more efficiently.
## Demo Steps

1. Create a Case
Open Customer Service App → Cases
Click New
Enter a description, for example:
Customer has been unable to login for 3 days and is very frustrated.
Save the record
2. Trigger AI Processing
Click the Generate AI button (or set AI Trigger = Yes)
This starts the Power Automate flow
3. AI Processing (Automatic)

The system performs:

AI Summary generation
Sentiment analysis
AI Recommendations
Case Category classification
AI Priority prediction
AI Email Draft generation
4. View Results
Open the AI Assist section/tab in the case form
Verify fields are populated:
AI Summary
Sentiment
AI Recommendations
AI Category
AI Priority
AI Email Draft
5. Use AI Output
Use recommendations to resolve the issue
Use AI-generated email to respond to the customer
## Sample Output

Sentiment → Negative
Category → Login Issue
Priority → High
Recommendations → Reset password, check account, escalate
Email Draft → Professional response

## GitHub Repository

This project is version-controlled and packaged as a Power Platform solution.
