# AI Marketing Agent (n8n Multi-Agent Workflow)

An automated end-to-end marketing content generation, market research, and campaign strategy pipeline built on **n8n** using sequential Anthropic AI agents and Google Sheets integration.

## 🎯 Use Purpose

The primary purpose of this project is to automate end-to-end marketing content generation, market research, and campaign strategy by routing form submissions through a multi-agent AI pipeline and logging outputs directly into Google Sheets.

## 🛠️ Tools & Tech Stack

* **Workflow Automation Platform:** [n8n](https://n8n.io/)[cite: 7]
* **AI Models:** Anthropic Chat Models (Multi-agent configuration with memory and tools support)[cite: 7]
* **Trigger Source:** Form submission webhooks[cite: 7]
* **Database / Storage:** Google Sheets (via Append row in sheet node)[cite: 7]

## ✨ Features

* **Form Submission Trigger:** Instantly kicks off the pipeline whenever a new marketing request or campaign brief is submitted via the web form[cite: 7].
* **Multi-Agent Sequential Pipeline:** 
  * **AI Agent (Research & Strategy):** Processes initial inputs using the Anthropic Chat Model to analyze target demographics and build campaign hooks[cite: 7].
  * **AI Agent 1 (Copywriting & Messaging):** Drafts tailored marketing copy, ad scripts, or email campaigns based on the strategy[cite: 7].
  * **AI Agent 2 (Optimization & Refinement):** Reviews generated copy for SEO alignment, brand tone, engagement optimization, and clarity[cite: 7].
  * **AI Agent 3 (Final Review & Formatting):** Formats all outputs into structured marketing assets ready for execution[cite: 7].
* **Automated Data Logging:** Automatically logs compiled campaign strategies and copy into Google Sheets without requiring manual coordination[cite: 7].

## 📂 Project Structure

```text
ai-marketing-agent/
├── workflow.json           # Main n8n workflow export file
├── documentation.md        # Detailed operational documentation
└── README.md               # Repository documentation and guide
