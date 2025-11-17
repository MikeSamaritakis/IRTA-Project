
# 🧠 Intelligent Resume Tailoring Assistant (IRTA)

## 🚀 Project Summary

**IRTA** is an AI-powered web application that helps job seekers optimize their resumes to specific job descriptions using real-time NLP and LLMs. By extracting key requirements from job listings and analyzing user resumes, IRTA recommends customized edits that enhance alignment with ATS filters and recruiter preferences.

---

## 🌐 Live Demo
[Coming Soon — Deploy via Vercel or Netlify]

---

## 🎯 Core Features

- 🔍 **Job Description Scraper**: Paste a URL or raw text — IRTA auto-parses required skills and keywords.
- 🧾 **Resume Parser**: Upload your resume (PDF or .docx) — IRTA reads and structures it for comparison.
- 🤖 **LLM-Powered Suggestions**: Real-time resume rephrasing to mirror the job description language.
- ✅ **ATS Compatibility Score**: Dynamic score with tips to boost alignment.
- 💾 **Resume Versions Manager**: Save, edit, or revert tailored resumes.
- 📤 **Export Options**: Download optimized resumes in PDF or .docx.

---

## 🏗️ Tech Stack

| Layer | Technology |
|-------|------------|
| **Frontend** | React + TailwindCSS |
| **Backend** | Node.js + Express |
| **Database** | MongoDB |
| **AI/LLM** | OpenAI API / Ollama for local LLM (Mistral, GPTQ) |
| **Parsing** | `pdf-parse`, `mammoth.js`, `cheerio` |
| **Exporting** | `pdf-lib`, `docx` |
| **DevOps (Optional)** | Docker, Vercel, Netlify |

---

## 🧪 Sample Workflow (UX Flow)

1. **User uploads resume**
2. **User pastes job description or URL**
3. **System displays keyword diff + tailored suggestions**
4. **User edits suggested text inline (like Grammarly)**
5. **User clicks “Optimize” and downloads final version**

---

## 🧠 Potential Enhancements

- 📥 LinkedIn Job Scraper Integration
- 🗣 Voice Commands for UX accessibility
- 🔒 Local resume processing (privacy-first mode)
- 🧑‍💼 Recruiter Mode: Let recruiters validate job descriptions vs. resumes

---

## 📸 Sample Wireframe Sketch (Verbal)

**Header:**  
Logo | Upload Resume | Paste JD | Score Bar

**Main Panel (Split View):**  
📄 **Left Side**: Resume content (editable)  
🛠 **Right Side**: Tailoring suggestions, matched/missing keywords, improvement prompts

**Footer:**  
Buttons for Save Version, Export PDF/.docx
