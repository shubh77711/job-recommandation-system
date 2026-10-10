# 🚀 GetProCV — Resume Analyzer & Job Recommendation System

An aesthetic, professional, and fully interactive **Resume Analyzer and Job Recommendation System** with modern SaaS design. Built with **React 19**, **Vite**, and **Tailwind CSS**.

---

## ✨ Key Features

- **🎨 Modern Aesthetic Design**:
  - Emerald mint green accent palette (`#10b981`), glassmorphism, and clean typography (*Plus Jakarta Sans*).
  - Clean hero section with radial circular score gauge (`92/100, 24 Issues`), ATS parse rate meter, and category breakdown.
  - **Zero Login Barrier**: 100% free with **no login or signup required**—immediate access to all features.

- **📄 Universal File Ingestion & Parsing**:
  - Drag-and-drop or file upload for **PDF (.pdf)**, **Word (.docx)**, and **Plain Text (.txt)**.
  - Direct **Paste Resume Text** option for instant pasting.
  - **1-Click Pre-Loaded Sample Resumes**:
    - *Alex Rivera (Senior Full Stack Engineer — 92 ATS Score)*
    - *Dr. Elena Rostova (AI & Machine Learning Scientist — 94 ATS Score)*
    - *Jordan Lee (Junior Web Developer — 62 ATS Score with highlighted fixes)*

- **🔍 27+ Crucial ATS Checkpoints Across 5 Pillars**:
  - **Content**: Quantifying Impact (detects numbers, %, $), Strong Action Verbs counter, Weak verb detection, Repetition & Buzzwords.
  - **Format & Brevity**: Word count, page-fit estimation, contact info detection (Email, Phone, LinkedIn, GitHub, Location).
  - **Style**: Cliches & overused buzzwords detection, professional tone check.
  - **Sections**: Summary/Objective, Experience, Education, Skills, Projects, and Certifications.
  - **Skills**: Detected Hard Skills, Soft Skills, and **In-Demand Missing Skills** for the candidate's detected domain.

- **💼 Job Recommendation Engine**:
  - Dynamic role classification (Full Stack, Data Science, Frontend, Backend, DevOps, Product Manager, UI/UX Designer).
  - Curated database of high-compensation roles at companies like **Stripe, OpenAI, Vercel, Figma, Datadog, GitLab, Linear, Airbnb, Spotify, Shopify**.
  - **Match Score % Calculation**: Visual match badges, matched skills (green pills), and missing skills to learn (amber pills).
  - Interactive Filters: Search query, Remote/Hybrid/On-site filter, Experience level, and Minimum match percentage.
  - **Interactive Quick Apply**: One-click application simulation with celebration confetti.
  - **Tailor Resume Generator**: 1-click tailored objective statements and keywords for any job.

- **🎯 Target Job Description (JD) ATS Matcher**:
  - Paste any job posting from LinkedIn, Indeed, or Greenhouse.
  - Computes ATS match score specifically for that posting.
  - Identifies missing keywords and generates a custom tailoring action plan.

- **✨ Bullet Point Rewriter (STAR Method)**:
  - Detects weak bullet points from the resume.
  - Generates 3 high-converting STAR method revisions with quantifiable metrics.
  - One-click copy to clipboard.

- **📝 Cover Letter & LinkedIn Bio Generator**:
  - Auto-generates personalized cover letters and LinkedIn summary bios based on candidate credentials.

- **🖨️ Export & Print ATS Audit Report**:
  - One-click formatted printable audit view ready for PDF export.

---

## 🛠️ Tech Stack

- **Frontend**: React 19, Vite 8, Tailwind CSS v4
- **Icons**: Lucide React
- **Document Extractors**: `pdfjs-dist`, `mammoth`
- **Effects**: `canvas-confetti`

---

## 🚀 Running the Project Locally

```powershell
# 1. Install dependencies (if not already installed)
npm install

# 2. Start the development server
npm run dev

# 3. Build for production
npm run build
```
