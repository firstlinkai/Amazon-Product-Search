# Automating Amazon Product Data Collection with n8n, BrightData, LangChain, and Google Sheets

Manual scraping of Amazon search results is slow, repetitive, and error-prone.  
We built a workflow that automates the entire process—turning raw HTML into clean, structured product data ready to use.  

## How It Works
- **Google Sheets** supplies and collects Amazon search URLs.  
- **BrightData** fetches the raw HTML from result pages.  
- A custom **n8n Function node** sanitizes the HTML, stripping noise like scripts and unwanted tags.  
- **LangChain (GPT-4 via OpenRouter)** parses product details into structured JSON:
  - name  
  - description  
  - rating  
  - reviews  
  - price  
- Results are written back into **Google Sheets** for immediate use.  

## Who Benefits from This Workflow?
- 🛒 **E-commerce analysts** tracking competitor prices and ratings  
- 📈 **Market researchers** monitoring product popularity  
- 🗄️ **Data teams** ingesting metadata into BI pipelines  
- 🔗 **Affiliate marketers** keeping catalogs updated  

## Why It Matters
- **End-to-end automation** – from URL lists to clean data in Sheets  
- **Accurate parsing** powered by GPT-4  
- **Scalable** – process thousands of URLs in batches  
- **Adaptable** – works for other platforms like Walmart or eBay  

---

⚡ If you need reliable, structured Amazon product data delivered straight into your spreadsheets, this workflow saves hours of manual effort.  
