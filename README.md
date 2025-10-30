# AIGharStore
# HamaroGharaStore

A Django-based web application featuring a **recommendation system** (small AI feature) that suggests relevant items to users. Built with a clean, modular structure so you can experiment with ranking strategies and models.

## ✨ Features

- 🧭 Core e-commerce flows (browse, detail, cart, etc.) *(customize based on your project)*
- 🤖 **Recommendations**: Top-K item suggestions using a pluggable engine
- 🔐 Auth & sessions (Django default)
- 🗃️ SQLite by default; easily switch to Postgres via `DATABASE_URL`
- 🧪 Basic test scaffolding (optional)

## 🧱 Tech Stack

- **Backend**: Django (Python)
- **DB**: SQLite (dev), Postgres (optional)
- **AI/Reco**: Pluggable engine (e.g. content-based / popularity / hybrid)
- **Env**: `python-dotenv` (optional), `dj-database-url` (optional)



