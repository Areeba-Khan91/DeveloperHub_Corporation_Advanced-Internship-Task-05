🎫 Task 5: Auto-Tagging Customer Support Tickets Using LLMs

🎯 Objective

To automate the classification of free-text customer support tickets into:

Technical

Billing

Account Access

🛠 Methodology / Approach

Framework: Google Gemini 2.5-Flash

Techniques:

Compared Zero-Shot Learning vs Few-Shot Learning

Ranking Strategy:

Prompt structured to return Top 3 most probable tags for each ticket

Optimization:

Implemented Batch Processing to process multiple tickets per API call

Successfully mitigated 429 rate-limit errors

📊 Key Results & Observations

Accuracy: Few-Shot Learning significantly improved classification of ambiguous tickets

Insight: Prompt engineering offers a fast and effective alternative to traditional fine-tuning for business-focused NLP tasks
