# AI-Powered-News-Automation
An intelligent, end-to-end automation workflow designed to solve the problem of information overload. This agent autonomously fetches daily news, filters high-priority content using Natural Language Processing (NLP), and delivers concise AI-generated summaries directly to your inbox.

# Key Features
*  Automated News Aggregation: Periodically fetches latest updates from multiple tech and finance RSS feeds.

*  Intelligent Filtering: Uses NLP-based logic to score and filter news based on user-defined priority levels.

*  AI Summarization: Leverages LLMs to synthesize lengthy articles into 3-4 high-impact bullet points.

*  Seamless Email Delivery: Integrated email automation for instant delivery of priority updates.

# Tech Stack
* Orchestration: n8n (Workflow Automation)

* AI/NLP: OpenAI GPT / Llama 3 (via API)

* Data Format: JSON / RSS Feeds

* Delivery: Gmail / SMTP Node

# Project Structure
* news_agent_workflow.json: The main n8n workflow file (Import this into your n8n instance).

* assets/: Contains workflow screenshots and architectural diagrams.

# How to Setup
* Install n8n: Ensure you have a self-hosted or cloud instance of n8n.

* Import Workflow: Download the news_agent_workflow.json from this repo and import it via the n8n UI.

* Configure Credentials: Set up your API keys for the AI nodes (OpenAI/Groq) and Email nodes.

* Activate: Set the "Cron" or "Schedule" node to your desired interval (e.g., Daily at 9:00 AM).

# Impact
* 90% Improvement in information efficiency by eliminating manual news browsing.

* Reduces "Noise": Focuses only on high-priority technical intelligence.
