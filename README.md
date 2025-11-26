# 🧠 LLMDevPro.com - LLM Architecture & Technical Hub

## 🎯 Project Goal
This is the **technical authority site** of the DevPro network. Our mission is to provide senior developers and researchers with accurate, deep, and structured information on LLMs, focusing on technical specifications, architecture patterns, and strategic deployment.

---

## 🛠️ Technology Stack (Performance Focused)
* **Framework:** Hugo (Static Site Generator) - *Optimized for fast delivery of long-form technical content.*
* **Data Management:** YAML Files (`data/models.yaml`)
* **Styling:** Tailwind CSS (or your chosen framework)
* **Deployment:** Cloudflare Pages / Vercel

## 📁 Core Data Structure
### **1. Model Data (Technical Directory)**
All model listings are managed via the **`data/models.yaml`** file.

| Field (Key) | Example Value | Description |
| :--- | :--- | :--- |
| `name` | GPT-4o | Model identifier |
| `developer` | OpenAI | Vendor name |
| `context_window` | 200k Tokens | **Critical technical metric (used for filtering)** |
| `access_type` | API / Self-Hosted | How the model is accessed |
| `official_api_url` | API Documentation Link | Direct link for developers |

### **2. Architecture Guides (High-Value Content)**
In-depth technical articles (e.g., RAG Implementation, LLMOps Strategy) are stored as standard Hugo Markdown files:
* `/content/architecture/rag-implementation.md`
* `/content/models/gemini-pro-analysis.md`

### **Local Development**
```bash
hugo server -D
