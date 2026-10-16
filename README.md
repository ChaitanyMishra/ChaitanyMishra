<h1 align="center">Chaitany Mishra</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&pause=900&color=A259FF&center=true&vCenter=true&width=640&lines=Entry-Level+Python+Backend+Developer;FastAPI+%2B+PostgreSQL+%2B+Celery+%2B+Redis;Regex+%2B+LLM+Hybrid+Parsing;Applied+AI%3A+LLM+APIs+%2B" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/chaitany-dev-hash/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:chaitany.mishra.tech@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

## 👋 About Me

I'm an entry-level backend developer from Kanpur, India. Over the last few months I've been building backend systems from scratch: FastAPI + PostgreSQL services, async batch pipelines with Celery + Redis, and hybrid parsing that pairs deterministic regex with LLM fallback for the fields regex can't handle reliably.

I care about what happens under the hood: data modeling, idempotent writes, retries, and failure handling. These separate a working demo from a system you can trust.

**Looking for my first Python Backend / Applied AI role at a startup. Open to relocating anywhere in India.**

---

## 🔧 Currently Building

### [Invoice Parser API](https://github.com/ChaitanyMishra/invoice-receipt-parser)

A backend service that turns uploaded invoices and receipts into structured data.

- **Hybrid parsing:** multi-pattern regex for the 6 fields with consistent labels, LLM (Groq → Gemini) only for vendor name, address and line items
- **Fast and accurate:** ~0.001 s per regex parse versus 4-30 s LLM-only, 100% accuracy on 10 test invoices
- **Reliable:** format + cross-field validation, idempotent writes, retries with exponential backoff, and regex results still returned if every LLM provider fails
- **Async:** batch uploads processed by Celery + Redis workers, with the API returning a `batch_id` immediately

`Python` · `FastAPI` · `PostgreSQL` · `SQLModel` · `Celery` · `Redis` · `pdfplumber`

**Status:** working end-to-end. Next: multi-invoice PDF splitting, Docker, pytest suite.

---

## 🛠️ Tech Stack

**Backend**

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![SQLModel](https://img.shields.io/badge/SQLModel-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://sqlmodel.tiangolo.com/)
[![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)](https://docs.celeryq.dev/)
[![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)](https://redis.io/)

**Applied AI**

![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)

**Tools**

[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)
[![Linux Mint](https://img.shields.io/badge/Linux_Mint-87CF3E?style=for-the-badge&logo=linuxmint&logoColor=white)](https://linuxmint.com/)

---

## 🚀 Featured Projects

| Project | Stack | What It Does | Repo |
|---|---|---|---|
| **Invoice Parser API** | Python, FastAPI, PostgreSQL, SQLModel, Celery, Redis | Turns invoices into structured data using regex + validation, with a Groq → Gemini fallback and async batch processing | [Repo](https://github.com/ChaitanyMishra/invoice-receipt-parser) |
| **Plant Disease Identification** | Python, MobileNetV2 (CNN), Gemini API | Classifies plant diseases from leaf images, with an LLM fallback when model confidence is low | [Repo](https://github.com/ChaitanyMishra/plant_disease_identification) |

---

## 📚 Learning Roadmap

**Solid**
- [x] Python fundamentals, OOP
- [x] FastAPI: routing, Pydantic, file uploads, error handling
- [x] PostgreSQL + SQLModel: relationships, sessions, CRUD, idempotency
- [x] Regex: multi-pattern extraction, validation, edge cases
- [x] LLM integration: prompts, fallback chains, rate-limit handling
- [x] Celery + Redis: async tasks, retries, worker orchestration
- [x] Git + GitHub workflows

**In progress**
- [ ] Docker + docker-compose
- [ ] Deployment (Render / Railway)
- [ ] pytest test suite
- [ ] JWT authentication + per-user data isolation
- [ ] Structured logging

**Planned**
- [ ] Alembic migrations
- [ ] Async database sessions
- [ ] OCR for scanned PDFs (Tesseract)
- [ ] AWS basics, then SAA-C03

---

## 📈 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ChaitanyMishra&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="49%" />
  <img src="https://streak-stats.demolab.com?user=ChaitanyMishra&theme=tokyonight&hide_border=true" width="49%" />
</div>

---

## 📫 Let's Connect

Happy to talk about backend architecture, LLM integration, or anything I'm building.

- 📧 [chaitany.mishra.tech@gmail.com](mailto:chaitany.mishra.tech@gmail.com)
- 🔗 [LinkedIn](https://www.linkedin.com/in/chaitany-dev-hash/)
- 💻 [GitHub](https://github.com/ChaitanyMishra)

---

<p align="center"><i>"Understanding the system beats copying the code."</i></p>
