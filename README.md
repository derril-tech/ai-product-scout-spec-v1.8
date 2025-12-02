# 🔍 ProductScout
**AI-Powered Competitive Intelligence Platform**

🌐 **Live Demo**: [https://ai-product-scout-spec.vercel.app](https://ai-product-scout-spec.vercel.app)

> **Discover competitors, analyze features, and uncover market opportunities in seconds. Transform product research from hours of manual work into instant, actionable insights.** ⚡

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![Next.js](https://img.shields.io/badge/Next.js-15-black.svg)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.2-61DAFB.svg)](https://react.dev/)
[![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4.1-412991.svg)](https://openai.com/)
[![Railway](https://img.shields.io/badge/Backend-Railway-blueviolet.svg)](https://railway.app/)
[![Vercel](https://img.shields.io/badge/Frontend-Vercel-black.svg)](https://vercel.com/)

---

## ✨ What It Does

ProductScout is an intelligent research assistant that transforms how founders, PMs, and strategists analyze competitive landscapes. Enter a product category, and watch as AI agents work together to:

- 🔎 **Fetch competing products** from Product Hunt and search APIs
- 🧠 **Extract key features** using GPT-4.1-mini analysis
- 📊 **Build comparison matrices** with normalized feature data
- 💡 **Generate strategic insights** identifying market gaps and opportunities

---

## 🎯 Key Features

### 🤖 **AI-Powered Analysis**
- **Intelligent Feature Extraction** — GPT-4.1-mini analyzes product descriptions to identify key capabilities, pricing signals, and differentiators
- **Strategic Insight Generation** — AI identifies market gaps, underserved segments, and positioning opportunities
- **Deep Product Analysis** — Click any product for comprehensive AI-powered SWOT analysis

### 🎨 **Modern React 19.2 Experience**
- **Single-Page Application** — Smooth state-driven transitions, no page reloads
- **Live Pipeline Visualization** — Watch AI agents process your query in real-time
- **Typing Effect** — ChatGPT-style streaming text for engaging results
- **Dark Mode Default** — Beautiful, eye-friendly interface

### 📊 **Professional Output**
- **Comparison Matrix** — Side-by-side feature comparison across competitors
- **Visual Charts** — Bar charts, radar charts, and feature matrices
- **Export Options** — Download results as JSON, CSV, or Markdown
- **Query History** — Access past analyses instantly

### 🔐 **Enterprise-Ready**
- **User Authentication** — Secure sign-in with Supabase Auth
- **Saved Projects** — Organize and revisit your research
- **Custom Prompts** — Tailor analysis focus to your specific needs
- **Real-time Streaming** — Server-Sent Events for live updates

---

## 🏗️ Architecture

### **Backend** — Python FastAPI on Railway
```
┌─────────────────────────────────────────────────────────────┐
│                    LangGraph Pipeline                        │
├─────────────┬─────────────┬─────────────┬──────────────────┤
│   Product   │   Feature   │             │     Insight      │
│   Fetcher   │  Extractor  │  Comparator │     Writer       │
│             │             │             │                  │
│ Product Hunt│   OpenAI    │  Normalize  │    OpenAI        │
│  + SerpAPI  │  GPT-4.1    │   Matrix    │   GPT-4.1        │
└─────────────┴─────────────┴─────────────┴──────────────────┘
```

- **FastAPI** — High-performance async Python web framework
- **LangGraph** — Orchestrates multi-step AI agent workflows
- **OpenAI SDK** — GPT-4.1-mini for intelligent analysis
- **Supabase** — PostgreSQL database with real-time capabilities
- **Upstash Redis** — Serverless caching and job queue

### **Frontend** — Next.js 15 on Vercel
- **React 19.2** — Latest React with concurrent features
- **Next.js 15** — App Router with server components
- **TypeScript** — Full type safety throughout
- **Tailwind CSS** — Utility-first responsive styling
- **shadcn/ui** — Beautiful, accessible component library

---


## 📖 User Guide

### Running an Analysis

1. **Enter a Category** — Type a product category like "AI note-taking tools" or "project management for startups"

2. **Watch the Pipeline** — See the animated visualization as AI agents process your query:
   - 🔍 ProductFetcher → Gathers competitor data
   - 🧠 FeatureExtractor → AI analyzes features
   - 📊 Comparator → Builds comparison matrix
   - 💡 InsightWriter → Generates opportunities

3. **Explore Results**
   - **Summary** — AI-generated competitive landscape overview
   - **Comparison Matrix** — Feature-by-feature comparison
   - **Visual Charts** — Interactive bar and radar charts
   - **Opportunities** — Actionable strategic insights

4. **Deep Dive** — Click any product for comprehensive AI analysis including strengths, weaknesses, target audience, and recommendations

5. **Export** — Download your analysis in JSON, CSV, or Markdown format

### Customization

- **Analysis Focus** — Select predefined focuses (Pricing, Features, UX, Technical, Market Position) or write custom prompts
- **Saved Projects** — Save analyses for later reference
- **Query History** — Quick access to recent searches

---

## 🎨 Design System

ProductScout features a carefully crafted design system:

- **Color Palette** — Teal primary (#177A8C), orange accent (#ED8A23)
- **Typography** — Inter for UI, JetBrains Mono for code
- **Dark Mode** — Default theme optimized for extended use
- **Animations** — Subtle micro-interactions and smooth transitions
- **Mobile-First** — Fully responsive with 44px touch targets

---


## 👨‍💻 Creator

**Derril Filemon**

- Building AI-powered tools that solve real problems
- Passionate about clean architecture and great UX
- Always exploring the latest in React, Python, and AI

---

## 🙏 Acknowledgments

- **OpenAI** — GPT-4.1-mini for intelligent analysis
- **Supabase** — Database and authentication
- **Upstash** — Redis caching
- **Railway** — Backend deployment
- **Vercel** — Frontend hosting
- **shadcn/ui** — Beautiful components

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

<div align="center">



[Live Demo](https://ai-product-scout-spec.vercel.app) 

Made with ❤️ and ☕ by [Derril Filemon](https://github.com/derril-tech)

</div>
