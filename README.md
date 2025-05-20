# 📄 Document Summarizer Automation (n8n + Groq)

This project is an AI-powered automation that scans Google Drive for new documents, summarizes them using Groq LLM, and logs the result in a Google Sheet.

### ⚙️ Workflow Summary

1. **Google Drive Trigger** — Watches for new documents in a specific folder.
2. **Google Docs** — Fetches the full content of the newly added document.
3. **Groq LLM** — Summarizes the document text efficiently using chunked processing if needed.
4. **Google Sheets** — Logs the result with:
   - Document name
   - Summary
   - Google Drive link

### 🔧 Tools & Platforms

- **n8n** – Low-code automation platform
- **Groq LLM** – For fast and accurate text summarization
- **Google Drive & Docs** – To source new content
- **Google Sheets** – To save summaries in a structured format

### 🧠 Use Case

This automation is perfect for teams or individuals who want quick insights from documents without reading each one manually. Ideal for researchers, project teams, and productivity enthusiasts.

---

✅ **Self-hosted with free APIs where possible**  
📦 **Includes exported n8n workflow JSON**  
🧠 **AI Summary + Smart Logging**

