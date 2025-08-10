📄 ADGM-Compliant Corporate Agent – Document Intelligence

Overview:
This project is an AI-powered Corporate Agent designed to review, validate, and help prepare documentation for business incorporation and compliance within the Abu Dhabi Global Market (ADGM) jurisdiction.
The agent uses Retrieval-Augmented Generation (RAG) with official ADGM references to ensure accuracy and compliance.

Key Features:
Upload & Parse Documents (.docx)

Document Checklist Verification based on ADGM rules

Red Flag Detection for legal issues

Inline Comments with law references

Downloadable Reviewed .docx with highlights/comments

Structured JSON/Python Report of findings

How It Works
Upload

User uploads one or more .docx files.

Document Parsing

System reads and identifies document type (e.g., Articles of Association, MoA, Board Resolution).

Checklist Verification

Compares uploaded files against ADGM-required documents for the detected legal process.

Notifies user of missing documents.

Red Flag Detection

Identifies issues such as incorrect jurisdiction, missing clauses, ambiguous language, missing signatures, or non-ADGM compliance.

Inline Commenting

Inserts contextual comments directly into the .docx file citing relevant ADGM regulations.

Output Generation

Reviewed .docx with comments and highlights.

Structured JSON/Python report summarizing:

Process type

Documents uploaded vs. required

Missing documents

Issues found

Tech Stack
Frontend/UI: Streamlit / Gradio

AI Model: RAG-enabled LLM (OpenAI, Gemini, Claude, Ollama, etc.)

File Processing: python-docx

Data Handling: Python, JSON

Legal Reference: Official ADGM documentation
