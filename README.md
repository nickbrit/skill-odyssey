# Skill Odyssey Data 🧭

**Skill Odyssey Data** is the official data repository for [Skill Odyssey](https://skillodyssey.com) — an open-source project helping people navigate realistic, AI-aware career transitions.

This repo contains all structured data used on the site, including:

- 📌 High-risk jobs and safer alternatives (`jobs.yml`)
- 🔄 Detailed transition guides between roles (`transitions/*.yml`)
- 🧠 Ethical and psychological resources related to AI and employment (`ethics.yml`)

---

## 📁 Repository Structure

### `jobs.yml`

A list of real-world jobs with automation risk levels and realistic alternative career options.

```yaml
- title: "Customer Service Representative"
  riskLevel: "High Risk"
  description: "AI chatbots and virtual assistants are increasingly handling routine customer inquiries."
  alternatives:
    - "Customer Experience Strategist"
    - "AI Training Specialist"
    - "Complex Problem Resolution Expert"
```

Other examples include:

- Data Entry Clerk → Process Automation Specialist  
- Bookkeeper → Financial Systems Specialist  
- Paralegal → Legal Technology Specialist  
- Radiologist → AI-Assisted Diagnostics Specialist  
- Software Developer → Prompt Engineer  
- Teacher → AI-Enhanced Curriculum Developer  

---

### `ethics.yml`

A curated list of trusted, well-explained resources related to:

- AI ethics and responsibility  
- Coping with job loss anxiety  
- Myths and misconceptions about AI  
- Human-centric design and values alignment

Example:

```yaml
- title: "AI Won’t Replace Humans — But Humans With AI Will"
  description: "Harvard Business Review explains how AI augments human work and why adaptation matters more than resistance."
  link: "https://hbr.org/2023/08/ai-wont-replace-humans-but-humans-with-ai-will-replace-humans-without-ai"
```

---

### `transitions/*.yml`

Each file describes a full career transition — from a vulnerable role to a more future-proof one.  
Example: `transitions/customer_support_to_prompt_engineer.yml`

Includes:

- `from` and `to` titles
- Role overviews and responsibilities
- Reasons why the transition makes sense
- Transferable skills
- Multi-phase roadmap with resources
- Required technical & soft skills
- Certifications
- Job market and salary expectations
- Recommended communities, books, and learning content

```yaml
from: "Customer Support Specialist"
to: "AI Prompt Engineer"
description: >
  A comprehensive guide to transitioning from Customer Support to Prompt Engineering,
  highlighting transferable skills, structured learning paths, and career opportunities.

transferable_skills:
  - name: "Communication Skills"
    description: "Ability to understand user intent, clarify ambiguous requests, and communicate clearly."
```

---

## 🤝 Contributing

We welcome contributions of all kinds.

### ➕ Add a new job

1. Open `jobs.yml`
2. Add a new entry following the existing structure:
    - `title`
    - `riskLevel`: `"High Risk"`, `"Medium Risk"`, or `"Low Risk"`
    - `description`
    - `alternatives`: 2–3 future-ready roles

### ➕ Add a new transition

1. Create a new file in the `transitions/` directory.
2. Name the file like this:  
   `from_job_to_new_job.yml`  
   Example: `teacher_to_curriculum_designer.yml`
3. Use an existing file as a template, or [request one](https://github.com/nickbrit/skill-odyssey/issues).

### ➕ Add a new ethical resource

1. Open `ethics.yml`
2. Append an entry with:
    - `title`
    - `description`
    - `link`

Please keep language clear, respectful, and accurate.

---

## 🌐 Related Project

- **Main Site**: [SkillOdyssey.com](https://skillodyssey.com)
- **Built with**: React, Next.js, React Flow, Tailwind CSS

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE).  
You are free to use, modify, and distribute this content — with credit appreciated.

---

## ✨ Community

This project is maintained by [@nickbrit](https://github.com/nickbrit) and the Skill Odyssey community.  
We believe in a calm, ethical, and hopeful approach to navigating the age of AI — together.

---

> Ready to contribute? Fork this repo, make your changes, and open a pull request 🙌
