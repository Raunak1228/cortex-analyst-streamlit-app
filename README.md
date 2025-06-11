# 📊 Conversational Analytics with Cortex Analyst  
**Unlocking Natural Language Insights in Snowflake**

---

## 🧾 Project Summary

This project demonstrates the development of an **end-to-end conversational analytics solution** using **Cortex Analyst**, a managed natural language querying service from **Snowflake Cortex AI**. It enables business users to interact with structured financial data using plain English, delivering real-time, accurate insights — no SQL required.

---

## ✅ What I Did

### 🛠️ 1. Environment Setup & Data Provisioning
- Created Snowflake objects: databases, schemas, tables, and stages
- Loaded a realistic financial dataset representing revenue by time, region, and product

### 🧠 2. Semantic Model Definition
- Created a semantic layer using `revenue_timeseries.yaml`
- Mapped business-friendly column names, types, and relationships
- Supported **joins** for star schema querying

### 🗣️ 3. Cortex Analyst Integration
- Connected to the **Cortex Analyst REST API**
- Translated natural language into executable Snowflake SQL
- Handled user input, feedback controls, and token limit responses

### 🔄 4. Multi-turn & Join Support
- Enabled **multi-turn Q&A** to carry context across user queries
- Implemented support for cross-table joins with semantic guidance

### 🔍 5. Cortex Search Enhancement
- Integrated **Cortex Search** for more accurate query matching
- Created metadata definitions for improved intent understanding

### 🎨 6. Streamlit in Snowflake (SiS) App Development
- Built an interactive chat interface using **Streamlit in Snowflake**
- Developed `cortex_analyst_sis_demo_app.py` for a clean user experience
- Displayed real-time query results with graceful error handling

---

## 🧩 Technologies Used

| Tool / Platform     | Purpose                                              |
|---------------------|------------------------------------------------------|
| **Snowflake**        | Cloud-based data warehouse                          |
| **Cortex Analyst**   | Natural language to SQL interface                   |
| **Cortex Search**    | Semantic enhancement for query accuracy             |
| **Streamlit (SiS)**  | Frontend for interactive app inside Snowflake       |
| **Python**           | Logic, API integration, and optional local tools    |
| **YAML**             | Semantic model configuration                        |
| **SQL**              | Data loading, modeling, and transformation          |

---

## 🎯 Project Goals

- ✅ Enable business users to ask data questions in natural language  
- ✅ Build a modern, low-code analytics app fully within Snowflake  
- ✅ Improve accuracy and flexibility of NL-to-SQL conversions  
- ✅ Deliver scalable, secure, and user-friendly data access

---

## 📌 Key Outcomes

- ⚡ Reduced time to insights from hours/days to seconds  
- 🤝 Empowered non-technical users to explore data independently  
- 🔒 Maintained full RBAC, data security, and governance in Snowflake  
- 🧱 Created a modular, extensible foundation for future analytics projects

---

## 📁 Project Structure

```bash
├── cortex_analyst_sis_demo_app.py     # Streamlit app for conversational analytics
├── cortex_analyst_streaming_demo.py   # Optional demo with streaming support
├── revenue_timeseries.yaml            # Semantic model definition
├── create_snowflake_objects.sql       # Creates required Snowflake objects
├── load_data.sql                      # Loads sample financial data
├── cortex_search_create.sql           # Setup for Cortex Search enhancement
├── requirements.txt                   # Python package dependencies
└── README.md                          # Project documentation (you are here)
