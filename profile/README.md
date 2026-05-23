# NP-Tennis

![Status](https://img.shields.io/badge/status-active-success?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)
![Architecture](https://img.shields.io/badge/architecture-distributed-6f42c1?style=flat-square)
![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Textual](https://img.shields.io/badge/Textual-FFD700?style=flat-square&logo=python&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

A distributed tennis court booking ecosystem. Three services — a **REST API backend**, a **terminal-based customer frontend**, and a **terminal-based admin client** — work together to let users browse, book, and manage tennis courts in real time.

## Ecosystem

| Repository | Purpose | Primary Tech Stack |
|---|---|---|
| [`/frontend`](https://github.com/Nazvu-prydumayemo/frontend) | Customer-facing terminal app for browsing courts and placing bookings | Python, Textual, httpx |
| [`/backend`](https://github.com/Nazvu-prydumayemo/backend) | REST API — courts, orders, auth, and scheduling | Python, FastAPI, PostgreSQL, SQLAlchemy |
| [`/admin`](https://github.com/Nazvu-prydumayemo/admin-frontend) | Terminal-based admin panel for managing courts, orders, and users | Python, Textual, httpx |

## Links & Resources

| Resource | Location |
|---|---|
| Frontend Documentation | https://nazvu-prydumayemo.github.io/frontend/ |
| Backend Documentation | https://nazvu-prydumayemo.github.io/backend/ |
| Admin Documentation | https://nazvu-prydumayemo.github.io/admin-frontend/ |

## License

[MIT](LICENSE)
