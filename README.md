# MOOC_Submission_n8n_maahin

## JSON Import and n8n Workflow Setup

### Overview
This project demonstrates how to import a JSON file, modify it by doubling the `chatInput` value and adding an `outfile` field with mock data, and set up an n8n workflow to process it. The workflow can be run locally using the `npx n8n start` command.

### Prerequisites
- **Node.js**: Ensure Node.js is installed (v16 or later recommended).
- **n8n**: Install n8n globally or use npx to run it locally.
- **JSON File**: A sample input JSON file to work with.

### Setup Instructions

1. **Make changes for input by double clicking on input tab**
   ```json
   {
     "chatInput": "Based on query answer to me"
   }

2. **Run by clicking on chat bot by asking question**
