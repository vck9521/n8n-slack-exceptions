This workflow automation was created using n8n. As an automation engineer, I receive daily exception reports that are automatically generated from GCP & sent to my slack channel. 
These exception reports can span over numerous pages & can easily exceed over 1000 logs so in order to save time & not have to manually do this, I set up this workflow automation
that could read these reports & give a summary of the exceptions. 

The workflow connects to an AI Agent node powered by gpt-4o mini model & connects to Supabase vector DB to obtain relevant JIRA tickets that have already been created for certain
exceptions so the workflow can attach the ticket along with its summary.

Workflow: 

<img width="3429" height="1194" alt="Screenshot 2025-11-25 at 4 18 34 PM" src="https://github.com/user-attachments/assets/b69f96a6-c7b8-4156-8b84-681477cac899" />

Results:

<img width="352" height="229" alt="Screenshot 2025-11-25 at 4 20 08 PM" src="https://github.com/user-attachments/assets/890bc0a8-93e7-4161-b58f-f5b9951a085e" />

