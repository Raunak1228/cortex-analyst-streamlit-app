# Cortex Analyst Streamlit App For AI Augmentated NLQ

Getting Started with Cortex Analyst
Conversational AI Meets Snowflake: Build Natural Language Analytics in Minutes

🧠 What Is Cortex Analyst?
Imagine asking your data questions like you’re chatting with a colleague — no SQL, no dashboards, just natural language.
Cortex Analyst makes that possible.

It’s a fully managed conversational AI service built into Snowflake Cortex AI, designed to:

💬 Turn questions into accurate SQL queries

📊 Return real-time results from structured Snowflake data

🔐 Respect RBAC, security, and governance rules you already have

🧩 Integrate seamlessly into your apps via REST APIs

Cortex Analyst empowers your business users to explore data freely, while keeping control in the hands of your data team.

🚀 What You'll Build in This Quickstart
With this project, you’ll go from 0 → deployed chatbot in your Snowflake environment:

✅ Step-by-step, you'll:
🧩 Define a Semantic Model over financial data

⚙️ Use Python or YAML to configure how data can be queried

🌐 Call the Cortex Analyst REST API to power your analytics chatbot

🎨 Build a sleek Streamlit-in-Snowflake (SiS) app

🔎 Enhance responses with Cortex Search for context-aware results

🔄 Enable multi-turn conversations and join support for rich, natural Q&A

And yes — this all runs inside Snowflake, using your existing cloud infrastructure.

🎯 Why Use Cortex Analyst?
“How much did we earn last quarter?”
“Which region saw the biggest growth in revenue?”
“Break down sales by product and customer segment.”

With traditional BI tools, answering these might take hours (or days) of waiting for someone to write SQL or update a dashboard.

With Cortex Analyst, it takes seconds.

✅ No SQL needed
✅ No dashboards to maintain
✅ Just ask, and get answers — fast

Perfect for:

📈 Analysts who want to move faster

🧑‍💼 Business teams tired of waiting for data

🛠️ Developers building custom analytics apps

🏢 Enterprises looking to modernize internal data tools

🧰 What's Inside This Repo?
File / Folder	Description
create_snowflake_objects.sql	Creates database objects and sample tables
load_data.sql	Loads sample financial data
revenue_timeseries.yaml	Semantic model definition file
cortex_analyst_sis_demo_app.py	Streamlit app with Cortex Analyst chat
cortex_search_create.sql	Setup script for Cortex Search
requirements.txt	Python dependencies
README.md	You’re reading it!

💡 Highlights
🧠 Semantic Layer: Define meaning behind your data for smarter responses

🛜 REST API Access: Integrate Cortex into any frontend or app

🔍 Search-Driven Insights: Boost answer relevance with search context

🔄 Multi-Turn Conversations: Keep context from previous questions

📊 Join-Aware: Ask cross-table questions using star schema logic

🌈 Beautiful UI: Streamlit app runs within Snowflake

🌍 Who Is This For?
Data Engineers: Set up semantic models and automate analytics

App Developers: Embed NL analytics into your tools

Business Users: Get real-time answers without needing SQL

Analytics Teams: Empower your org to be data-driven — at speed

🔓 Open Source & Extensible
This quickstart is open-source and built for experimentation. Feel free to fork it, extend it, and build your own conversational BI platform right inside Snowflake.

✨ Your data. Your logic. Now with the power of AI.
