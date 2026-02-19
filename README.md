# ProfolioAI – AI Career Coach Platform

## 🚀 Overview
**ProfolioAI** is an AI-powered career coach platform that helps users build resumes, analyse their skills, and receive personalized career guidance. The platform uses LLMs to simplify career planning through smart recommendations and an interactive chat coach.

## 🎯 Key Features
- **AI Resume Builder** – Generates clean resume content based on user inputs.  
- **Skill Gap Analysis** – Highlights missing skills by comparing profiles with job roles.  
- **Career Path Suggestions** – Suggests suitable roles and learning paths.  
- **Portfolio Insights** – Gives recommendations to improve projects and GitHub profiles.  
- **Chat-Based Career Coach** – Provides interview prep, profile review, and tech support.

## 🛠️ Tech Stack
- **Frontend:** Next.js / React  
- **Styling:** Tailwind CSS  
- **Backend:** Node.js / API Routes  
- **AI Engine:** Gemini API + LLM prompt engineering  

## 🧩 Major Challenge Solved
One of the biggest challenges during development was **working with the Gemini API** and managing **prompt engineering**.  
The API initially returned inconsistent or overly generic outputs, so I spent time experimenting with prompt tone, structure, and context length.  
I also faced issues with authentication, response parsing, and maintaining stable output format.  
After multiple iterations, I built a clean prompt workflow and a reliable API integration that now delivers accurate and human-like career suggestions.  
This entire debugging and optimization process is described clearly here so future contributors can follow it if they expand the AI engine.

## 📦 Installation
```bash
git clone https://github.com/surabhisingh04/profolioai.git
cd profolioai
npm install
npm run dev
