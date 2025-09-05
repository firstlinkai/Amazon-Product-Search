# Amazon-Product-Search
Amazon Product Search Scraper with BrightData, GPT-5, and Google Sheets

Manual scraping of Amazon search results is slow, repetitive, and error-prone. I've built a workflow that automates the entire process, turning raw HTML into clean, structured product data ready to use.

How it works:
Google Sheets supplies and collects Amazon search URLs.
BrightData fetches the raw HTML from result pages.
A custom n8n Function node sanitizes the HTML, stripping noise like scripts and unwanted tags.
LangChain (GPT-5 via OpenRouter) parses product details into structured JSON (name, description, rating, reviews, price).
Results are written back into Google Sheets for immediate use.

Who benefits from this workflow?
- E-commerce analysts tracking competitor prices and ratings
- Market researchers monitoring product popularity
- Data teams ingesting metadata into BI pipelines
- Affiliate marketers keeping catalogs updated

Why it matters:
End-to-end automation from URL lists to clean data in Sheets
Accurate product parsing using by GPT-5
Scalable enough to process thousands of URLs in batches
Adaptable for other platforms like Walmart or eBay

If you need reliable, structured Amazon product data delivered straight into your spreadsheets, this workflow saves hours of manual effort.
