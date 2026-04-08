# Velox API

<div align="center">

**A lightweight REST API built with FastAPI**

![Python](https://img.shields.io/badge/Python-3.11%2B-blue?logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-0.111-green?logo=fastapi)
![License](https://img.shields.io/badge/License-MIT-blue)

</div>

---

A minimal REST API for user authentication and resource management. No unnecessary dependencies, no bloat.

## Installation

```bash
git clone https://github.com/yourname/velox-api.git
cd velox-api
pip install -r requirements.txt
uvicorn app.main:app --reload
```

API runs at `http://localhost:8000` · Docs at `/docs`

## Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/auth/login` | Obtain JWT token |
| GET | `/users/me` | Get current user |
| GET | `/items/{id}` | Retrieve item |
| POST | `/items` | Create item |
## Markdown Cheat-Sheet

| Element | Syntax |
|---|---|
| Überschrift H1 | `# Text` |
| Überschrift H2 | `## Text` |
| Fett | `**Text**` |
| Kursiv | `*Text*` |
| Code inline | `` `code` `` |
| Codeblock | ` ```sprache ... ``` ` |
| Tabelle | `\| Spalte \| Spalte \|` |
| Trennlinie | `---` |
| Zentrieren (GitHub) | `<div align="center">...</div>` |
| Badge/Shield | `![Label](https://img.shields.io/badge/...)` |

## Project Structure

```bash
velox-api/
├── app/
│   ├── main.py          # Entry point
│   ├── routers/         # Route definitions
│   ├── models/          # Database models
│   └── schemas/         # Pydantic schemas
└── requirements.txt
```

## Contributing

Fork → branch → commit → pull request. Issues welcome.
