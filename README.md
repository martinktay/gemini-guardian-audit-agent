# gemini-guardian-audit-agent
An autonomous AI Governance Auditor powered by Gemini 3 Pro. Utilizes high-horizon reasoning and multimodal forensics to detect implicit bias and regulatory non-compliance in machine learning models and system logs.

🛡️ Gemini Guardian: Autonomous AI Governance Auditor
Built for the 2026 Gemini 3 Global Hackathon

Gemini Guardian is a next-generation "Agentic Auditor" designed to solve the growing complexity of AI regulatory compliance. By leveraging the Gemini 3 Pro model family, it moves beyond simple keyword monitoring to perform deep forensic analysis of AI decision-making logs against global frameworks like the EU AI Act and NIST AI RMF.

🚀 Key Gemini 3 Integrations
High-Horizon Reasoning: Utilizes thinking_level="high" to identify "Implicit Proxy Bias"—detecting when variables like zip codes act as surrogates for protected characteristics.

Thought Signatures: Surfaces the model's internal reasoning traces directly in the UI, providing a transparent and verifiable audit trail.

Multimodal Forensics: Ingests CSV logs, architectural diagrams, and PDF regulations simultaneously using Gemini 3's 1M+ Context Window.

Agentic Code Execution: Autonomously writes and executes Python scripts to calculate disparate impact ratios and verify statistical bias found during the audit.

📊 The COMPAS Case Study
As a proof of concept, Gemini Guardian was tested against the COMPAS Recidivism Dataset. The agent successfully identified systemic discrepancies in risk attribution (e.g., Marcu Brown vs. Michael Lux) and generated a structured JSON remediation plan—tasks that typically require weeks of manual legal and data science review.

🛠️ Tech Stack
Core: Gemini 3 Pro (API)

Backend: FastAPI / Python (with google-genai SDK)

Frontend: React / Tailwind CSS (Mission Control UI)

Tools: Google Search Grounding & Agentic Code Execution

🏁 Quick Start
Clone the repo: git clone https://github.com/[Your-Username]/gemini-guardian

Install dependencies: pip install -r requirements.txt

Add your GOOGLE_API_KEY to the .env file.

Launch the Mission Control dashboard: npm run dev
