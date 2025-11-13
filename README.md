

# Lead Scraper & Enrichment Workflow – n8n

This is a fully automated workflow built in **n8n** that allows you to:

- Scrape businesses from **Google Maps** (e.g., Morocco)
- Extract their **website**, **email**, **phone number**, and **type**
- Store them in a **Google Sheet**
- Avoid duplicates (checks if the company already exists)

---

##  Technologies Used

-  **n8n** – Visual automation platform
-  **JavaScript** – Logic in function nodes
-  **Google Maps** – Data source
-  **Browserless + Puppeteer** – For scraping websites
-  **Google Sheets API** – Store cleaned data
-  **AI Agent (ChatGPT)** – Interprets user queries

---

##  Key Features

- Accepts input like: “Find marketing agencies in Casablanca”
- Converts into structured Google Maps queries
-  Scrapes real data from websites
-  Cleans and formats phone numbers + emails
-  Filters only **professional emails**
-  Adds data to Google Sheets (only if not already added)

---

##  Setup

1. Install **n8n** (self-hosted)
2. Add your Google Service credentials (spreadsheet access)
3. Configure **Browserless** locally or via Docker
4. Set your Google Sheet headers to match: `Name`, `Type`, `Email`, `Phone`, `Site web`

---

##  Environment Variables (Optional)

```bash
BROWSERLESS_API=http://xxxxxxxxxxxxxxxxxxxxxx
GOOGLE_SHEET_ID=xxxxxxxxxxxxxxxxxxxxxx

 Author
Fred Kaseya
Entrepreneur | AI & Automation Developer | Based in Morocco 🇲🇦
Building smarter business systems across Africa 🚀

 License
MIT © 2025 Fred Kaseya
"""

Save to a Markdown file
readme_path = Path("/mnt/data/README.md")
readme_path.write_text(readme_content)

readme_path.name


