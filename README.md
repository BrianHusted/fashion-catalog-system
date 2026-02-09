# Fashion Catalog System

A full-stack fashion catalog management system built as a **team-based software design project**, featuring a FastAPI backend, a PostgreSQL database, and a desktop-based admin interface (Tkinter).

This repository is a **personal copy** of the original group project, maintained for portfolio and demonstration purposes. The work was completed collaboratively, and this README is written to be transparent about that.

---

## Project Context (Group Project)

- Type: University group project (Software Design)
- Collaboration: Multi-person team
- Goal: Deliver a working catalog system with clean data modeling, CRUD workflows, authentication, and admin tooling

### My Contributions (High-Level)
I contributed to the project in areas including:
- Backend API development (FastAPI endpoints and request/response handling)
- Database schema + relationships (PostgreSQL + SQLAlchemy models)
- Admin workflows and integration (admin GUI interactions with backend/database)
- Setup and run scripts support (local developer experience)
- Testing via `.http` request files

(If you want this section to be exact, paste your commit summary or list of files you personally worked on and I’ll tighten it to only what you did.)

---

## Tech Stack

- Backend: FastAPI (Python)
- Admin GUI: Tkinter
- Database: PostgreSQL
- ORM: SQLAlchemy
- Password hashing: Passlib
- Testing: HTTP requests via `.http` files
- Scripts: Bash (macOS) / Batch (Windows)

---

## Features

### Admin (Desktop GUI)
- Create / edit / delete products, categories, and users
- Upload and associate images with products
- View product reviews and system logs
- Admin actions are recorded in the database for auditing

### User / API Capabilities
- Browse products and categories
- Product variations (size/color) support (where applicable in dataset/schema)
- Reviews and ratings support (where applicable in dataset/schema)

### Security
- Password hashing using Passlib
- Basic admin authentication flows (project-level implementation)

---

## Project Structure

fashion-catalog-system/
├── fastApiProject/
│ ├── Admin_Main.py # Tkinter-based Admin GUI
│ ├── db_classes.py # SQLAlchemy ORM models
│ ├── script.py # FastAPI backend
│ ├── db.sql # Initial DB schema
│ ├── flexwear_dump.sql # Sample data dump
│ ├── test_main.http # HTTP test routes
│ └── run.sh # Run server and open browser (macOS)
├── setup.bat # Windows setup script
├── setup.sh # macOS setup script
└── README.md


---

## Quick Start (Local)

### Prerequisites
- Python 3.11+
- PostgreSQL (local)

Note: Some scripts assume a default local PostgreSQL setup. If your environment differs, update the connection settings accordingly.

---

### Windows (Setup Script)
1. Install Python 3.11+ (ensure “Add Python to PATH” is enabled)
2. Install PostgreSQL (port 5432)
3. Run:
   - Double-click `setup.bat`
4. Follow prompts
5. Admin credentials are printed in the terminal when the application starts

---

### macOS (Setup Script)
1. Install Python 3.11+
2. Install Homebrew (recommended)
3. Run:

4. Admin credentials are printed in the terminal when the application starts

---

## Running the App

After setup:
- Web app: http://localhost:8000
- Admin GUI: opens in a separate window (Tkinter)
- Admin credentials: printed in the terminal output on startup

To stop:
- Press Ctrl+C in the terminal, or close the terminal window.

---

## Testing

Basic API testing is supported via:
- `fastApiProject/test_main.http`

You can run these requests using an editor that supports `.http` files (e.g., VS Code REST Client / JetBrains HTTP client).

---

## Troubleshooting

PostgreSQL connection issues:
- Confirm PostgreSQL is running
- Confirm port 5432 is free
- Confirm credentials / connection settings match your local config

If the admin GUI does not open:
- Check terminal output for errors
- Ensure Tkinter is installed and available in your Python distribution

If port 8000 is in use:
- Stop the conflicting service, or configure the app to use a different port

---

## Notes

- Intended for local use (no deployment configuration included)
- Sample dataset is included via SQL dump file(s)
- This repo is a portfolio copy of a group project; credit is shared across team members

---

## License

MIT License (if a LICENSE file is included in this repository)

