ContentGuard AI
AI-Powered Academic & Content Integrity Scanner

Protecting originality with intelligent automation

🚀 Overview

ContentGuard AI is a full-stack AI-powered evaluation system that analyzes assignments, essays, and blog content for:

Academic quality

Plagiarism

AI-generated content

Originality and structure

It solves two major real-world problems:

🎓 For Teachers & Institutions

Manually reviewing assignments for plagiarism, AI usage, and quality is time-consuming and error-prone.

🌐 For Bloggers & Website Owners

AI-written or plagiarized content can cause SEO penalties, loss of trust, and reputation damage.

👉 ContentGuard AI delivers accurate, automated evaluations within seconds.

🌐 Live Demo

🔗 Live Website:
https://contentguardai.lovable.app/

✨ Key Features
🧠 Academic Quality Evaluation (AI Scoring)

Powered by Gemini AI, the system evaluates:

Content depth

Structure

Grammar

Critical thinking

Formatting

Outputs:

Overall score

Strengths & weaknesses

Personalized feedback

📑 Plagiarism Detection

Duplicate content detection

Plagiarism percentage

Matched sources count

List of matching URLs

🤖 AI Content Detection

AI-generated content percentage

Human-written content percentage

Total AI-written words

📊 Document Statistics Extraction

Automatically extracts:

Word count

Sentence count

Reading time

Token count

Cleaned text

🎨 Front-End Interface (Lovable)

Drag & drop PDF upload

Animated AI chatbot

Real-time processing animation (n8n connected)

Last 20 evaluations saved locally

Downloadable full PDF report

🔄 Automated Workflow (n8n)

The backend pipeline performs:

PDF reception

Text extraction

Document statistics generation

Plagiarism scan

AI content detection

Gemini AI scoring

Result merging & formatting

JSON response sent back to frontend

👥 Target Users
🎓 Teachers & Educational Institutions

Detect AI-written assignments

Identify plagiarism instantly

Provide structured feedback

Save significant review time

📝 Bloggers & Website Owners

Verify originality

Avoid SEO penalties

Maintain content quality standards

🏗️ System Architecture

Frontend (Lovable)
→ n8n Webhook
→ PDF Extraction
→ AI Content Detection
→ Plagiarism Check
→ Document Statistics
→ Gemini AI Evaluation
→ Result Merge
→ JSON Response

🧠 Technology Stack
Frontend

Lovable (AI Web Builder)

HTML, CSS, JavaScript

PDF Report Generator

Local Storage History

Backend

n8n Workflow Automation

Gemini Language Model

Plagiarism Detection API

AI Content Detection API

PDF Text Extraction

Infrastructure

Hostinger VPS

HTTPS-secured domain

Self-hosted n8n instance

📥 Input & Output
Input

PDF documents (assignments, essays, blog posts)

Output (JSON Example)
{
  "score": 82,
  "content_score": 25,
  "structure_score": 18,
  "grammar_score": 19,
  "critical_thinking_score": 10,
  "formatting_score": 9,
  "plagiarism_status": "duplicate_content_found",
  "plagiarism_percentage": 100,
  "ai_content_percentage": 96.51,
  "total_words": 215
}

💰 Cost Analysis (Operational)

Estimated cost per document:
➡️ 0.013 – 0.016 USD (1.3 – 1.6 cents)

Monthly Estimates

1,000 documents: $13 – $16

10,000 documents: $133 – $163

50,000 documents: $665 – $815

100,000 documents: $1,330 – $1,630

(Actual costs may vary in production.)

🎥 Demo Video

🎬 Full Project Walkthrough:
Revolutionizing Content Evaluation with ContentGuard AI

⚙️ Installation & Setup
Prerequisites

Self-hosted n8n instance

API keys for:

Plagiarism API

AI Content Detection API

Gemini AI

Steps
git clone https://github.com/yourusername/ContentGuardAI.git
cd ContentGuardAI


Configure n8n Webhook:

https://n8n.srv1038989.hstgr.cloud/webhook/home_work_grader

🚀 Future Roadmap

Cloud-based history storage

User authentication

Teacher dashboard

Bulk PDF evaluation (up to 100 files)

Automated email reports

PDF similarity index

Assignment rubric generator

AI-assisted rewrite suggestions

👨‍💻 Founder

Usman Sabir
Founder & Developer — ContentGuard AI
AI Automation Specialist | Workflow Engineer | Full-Stack Developer
Instructor: Sir Zafar Iqbal
