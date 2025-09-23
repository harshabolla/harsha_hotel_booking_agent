Quick Start Guide: Agents for Amazon Bedrock Test UI
✅ Step 1: Prerequisites

Install AWS CLI
Install Python 3


✅ Step 2: Install Dependencies
Run:
pip install -r requirements.txt


✅ Step 3: Configure Environment Variables


Required:

BEDROCK_AGENT_ID → Your agent ID
BEDROCK_AGENT_ALIAS_ID → Agent alias ID (defaults to TSTALIASID)
AWS credentials with permissions to invoke the Bedrock agent



Optional:

BEDROCK_AGENT_TEST_UI_TITLE → Custom page title
BEDROCK_AGENT_TEST_UI_ICON → Custom favicon (e.g., :bar_chart:)
LOG_LEVEL → Logging level (or use logging.yaml for advanced config)




✅ Step 4: Run the App
Run the following command in your terminal:
streamlit run app.py --server.port=8080 --server.address=localhost

✅ Setup Flow Diagram
Here’s a visual representation of the setup process:
!Setup Flow Diagram

<img width="1024" height="1536" alt="Designer" src="https://github.com/user-attachments/assets/c77b7b91-e8a6-40f2-8f2f-daeb66f676c6" />

