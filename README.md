# 🥣 Recipace-AI

![Recipace-AI Logo](logo.png)

**Recipace-AI** is a Streamlit-powered web app that leverages Google’s Gemma 3-27B model to auto-generate richly detailed, one-of-a-kind recipes for YouTube food creators. In one click you’ll get:

- **Full Recipe**: Title, ingredients, cooking method, step-by-step guide  
- **Chef’s Insights**: Pro tips, plating suggestions, common pitfalls to avoid  
- **YouTube Script**: Ready-to-use intro, narration, and outro  
- **Grocery List**: Shopping list organized by category  
- **Timers**: Prep & cook step estimates  
- **Nutrition Facts**: Macro & micro breakdown  
- **Substitutions**: Flexible ingredient swaps  
- **Scaling & Conversion**: Adjust servings; switch between Imperial/Metric  
- **Save & Download**: Export as `.txt` or richly formatted `.docx`  
- **Session Library**: Save favorites for later  
- **One-click Tweet**: Share a snippet on Twitter  

---

## 📖 Table of Contents

1. [Project Overview](#project-overview)  
2. [Tech Stack](#tech-stack)  
3. [Screenshots](#screenshots)  
4. [Installation & Setup](#installation--setup)  
   - [Prerequisites](#prerequisites)  
   - [Clone & Virtual Environment](#clone--virtual-environment)  
   - [Dependencies](#dependencies)  
   - [Environment Variables](#environment-variables)  
5. [Usage Guide](#usage-guide)  
   - [Generate Tab](#generate-tab)  
   - [Saved Recipes Tab](#saved-recipes-tab)  
   - [About Tab](#about-tab)  
6. [Parameter Configuration](#parameter-configuration)  
7. [Advanced Features & Workflow](#advanced-features--workflow)  
   - [Prompt Engineering](#prompt-engineering)  
   - [DOCX Export Format](#docx-export-format)  
8. [Project Structure](#project-structure)  
9. [Troubleshooting](#troubleshooting)  
10. [Contributing](#contributing)  
11. [License](#license)  
12. [Contact & Follow](#contact--follow)  

---

## 🧐 Project Overview

Recipace-AI addresses the creative overhead for food content creators by auto-drafting complete, broadcast-ready recipes **and** accompanying materials in seconds. No more hours spent writing ingredient lists, calculating timers, or scripting your on-camera dialogue—focus on cooking (and filming) instead.

---

## 🛠 Tech Stack

- **Frontend/UI**: Streamlit  
- **LLM Backend**: Google Generative AI (Gemma 3-27B) via `google-generativeai` client  
- **Environment**: Python 3.8+ (venv)  
- **Data**: `recipace.json` for parameter definitions  
- **Document Export**: `python-docx` for Word (.docx) output  
- **Config**: `python-dotenv` for secret management  

---

## 📸 Screenshots

1. **Header & Logo**  
   ![Header](docs/screenshots/header.png)  
2. **Parameter Accordion**  
   ![Parameters](docs/screenshots/parameters.png)  
3. **Generated Recipe & Extras**  
   ![Recipe](docs/screenshots/recipe.png)  
4. **DOCX Export Preview**  
   ![DOCX](docs/screenshots/docx_preview.png)  

---

## ⚙️ Installation & Setup

### Prerequisites

- Python 3.8 or higher  
- `git`, `pip`  

### Clone & Virtual Environment

```bash
git clone https://github.com/your-username/recipace-ai.git
cd recipace-ai
python3 -m venv venv
# macOS/Linux:
source venv/bin/activate
# Windows (PowerShell):
.\venv\Scripts\Activate.ps1
