# Prototype MCP Server (FastAPI + SQLite)

A minimal **FastAPI** server with **SQLite** database and **Model Context Protocol (MCP)** integration.  
This project is for learning to convert FastAPI servers into MCP servers.

---

##Features

- FastAPI web server
- SQLite database using SQLAlchemy ORM
- Create and Read routes for `User`
- MCP integration via `FastApiMCP`
- Interactive API docs with Swagger UI (`/docs`) and ReDoc (`/redoc`)

---

## 📦 Installation

Clone the repo and set up a virtual environment:

```bash
git clone https://github.com/paolochan/Prototype-mcp.git
cd Prototype-mcp

python3 -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows

pip install -r requirements.txt
```

---

## 🛜 Remote use
```bash
uvicorn main:app
ngrok http 8000
```
Add URL/mcp to connector 
