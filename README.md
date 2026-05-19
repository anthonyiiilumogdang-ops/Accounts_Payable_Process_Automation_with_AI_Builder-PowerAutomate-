# Accounts_Payable_Process_Automation_with_AI_Builder-PowerAutomate-

Automated Accounts Payable pipeline built with Microsoft Power Platform and AI Builder.

## What It Does
- Detects new invoices uploaded to SharePoint
- Extracts invoice data (vendor, amount, due date, line items) using AI Builder
- Saves structured data to a Dataverse queue with status tracking
- Routes invoices through an approval workflow
- Finance team manages the queue via a Power Apps dashboard

## Tech Stack
| Tool | Purpose |
|---|---|
| Power Automate | Workflow automation |
| AI Builder | Invoice data extraction (prebuilt model) |
| Dataverse | Invoice queue & storage |
| Power Apps | Queue management dashboard |
| SharePoint | Invoice file storage |

## Architecture
![Flow Diagram](docs/architecture.png)

## Screenshots
### Invoice Queue Dashboard
![App Screenshot](docs/app-screenshot.png)

## How to Import This Solution
1. Download `solution/APAutomation.zip`
2. Go to make.powerapps.com → Solutions → Import
3. Upload the zip and follow the prompts
4. Configure your SharePoint site connection

## Skills Demonstrated
- AI/ML integration (AI Builder - Invoice Processing)
- Process automation (Power Automate)
- Database design (Dataverse)
- Low-code app development (Power Apps)
- AP business process knowledge
