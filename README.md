Quick Start Guide: Agents for Amazon Bedrock Test UI
This guide helps you quickly set up and run the Streamlit UI for testing Amazon Bedrock Agents.

✅ Step 1: Prerequisites

Install AWS CLI
Install Python 3


✅ Step 2: Install Dependencies
Run:
Shellpip install -r requirements.txtShow more lines

✅ Step 3: Configure Environment Variables
Set the following (directly or via .env using .env.template as a reference):


Required:

BEDROCK_AGENT_ID → Your agent ID
BEDROCK_AGENT_ALIAS_ID → Agent alias ID (defaults to TSTALIASID)
AWS credentials with permissions to invoke the Bedrock agent



Optional:

BEDROCK_AGENT_TEST_UI_TITLE → Custom page title
BEDROCK_AGENT_TEST_UI_ICON → Custom favicon (e.g., :bar_chart:)
LOG_LEVEL → Logging level (or use logging.yaml for advanced config)




✅ Step 4: Run the App
Start the Streamlit app:
Shellstreamlit run app.py --server.port=8080 --server.address=localhost
