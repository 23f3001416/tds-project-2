# Data Analyst Agent 
> Efficient and accurate analysis of your datasets using Generative AI and Python.


---

##  What Is This?
Data Analyst Agent 2.0 is an AI-powered assistant designed to streamline data processing.

Upload your dataset and queries to quickly obtain:

Visual reports

AI-generated insights

Automated workflows

Suitable for:

Analysts

Researchers

Startups and businesses

Anyone seeking to convert raw data into actionable information

---

##   Highlights  

| Feature                  | Use  |
|---------------------------|----------------------|
|  AI-Powered Insights    | Uses Google’s Generative AI to “understand” your data |
|  Rich Visualizations    | Generates plots with **Seaborn & Matplotlib** |
|  Web Scraper Mode       | Fetch live data directly from URLs |
|  Multi-Format Friendly  | Accepts CSV, Excel, JSON, Parquet, or TXT |
|  Ask Many at Once       | Batch processing for multiple questions |
|  Simple-to-Use Interface | Beginner friendly, no steep learning curve |
|  Super-Fast Execution   | Optimized for speed + real-time feedback |

---

##  Getting Started  

###  Clone the Repo  - git clone https://github.com/your-username/data-analyst-agent.git

cd data-analyst-agent

###  Install Requirements 

- pip install -r requirements.txt

###  Configure API Keys  

Create a `.env` file inside the root folder:  
GEMINI_API_KEY=your_google_api_key
LLM_TIMEOUT_SECONDS=240


###  Start the Application  - python -m uvicorn app:app --reload

Now open [**http://localhost:8000/**](http://localhost:8000/) in your browser 



##  Techstack  

### Backend  
- FastAPI  → High-performance web server  
- LangChain  → Orchestrates LLM interactions  
- Google Generative AI  → Core AI engine  
- Pandas + NumPy  → Data wrangling made smooth  
- Seaborn + Matplotlib  → Clean, insightful charts  



---

##  API Blueprint  

| Method | Endpoint  | Purpose |
|--------|-----------|----------|
| `GET`  | `/`       | Access web app |
| `POST` | `/api`    | Submit dataset + questions |
| `GET`  | `/summary`| App diagnostics & summaries |

---




---

##  License  

Licensed under **MIT** – free for personal & commercial use. 





  
