# Fashion Catalog System

A full-stack fashion catalog management system developed as a **team-based university software design project**.  
The system includes a FastAPI backend, PostgreSQL database, and an administrative interface for managing products, categories, and users.

This repository is a **personal copy of the original group project**, maintained for portfolio and demonstration purposes.

---

## Project Context

- Type: University group project (Software Design)
- Collaboration: Multi-person team
- Focus: Designing and implementing a complete CRUD-based catalog system with clear separation between user-facing and administrative functionality

---

## My Contributions

My primary contributions focused on the **frontend and interface layer**, with supporting backend integration:

- Developed and styled **HTML and CSS** components for the user-facing portions of the application
- Implemented **JavaScript logic** for client-side interaction and data handling
- Integrated frontend components with backend API endpoints
- Assisted with overall system integration and testing
- Contributed to setup scripts and local development workflow support

This framing reflects a collaborative effort, with responsibilities shared across the team.

---

## What I Learned

- Designing and styling responsive interfaces using HTML and CSS in a larger, multi-file codebase
- Writing client-side JavaScript that interacts cleanly with backend API endpoints
- Coordinating frontend work with backend data models and API contracts in a team setting
- Reading and extending existing backend code to integrate new UI functionality
- Managing scope, responsibilities, and integration challenges in a collaborative project

---

## Tech Stack

- Backend: FastAPI (Python)
- Database: PostgreSQL
- ORM: SQLAlchemy
- Frontend: HTML, CSS, JavaScript
- Admin Interface: Tkinter (desktop GUI)
- Security: Password hashing with Passlib
- Testing: HTTP request test files (`.http`)
- Tooling: Bash (macOS) / Batch (Windows)

---

## Core Features

- Product, category, and user management via admin interface
- Image upload and product association
- Review and logging support
- Secure password handling
- Clear separation of admin and user workflows

---

## Project Structure
```
fashion-catalog-system/
├── fastApiProject/
│ ├── Admin_Main.py
│ ├── db_classes.py
│ ├── script.py
│ ├── db.sql
│ ├── flexwear_dump.sql
│ ├── test_main.http
│ └── run.sh
├── setup.bat
├── setup.sh
└── README.md
```

---

## Running the Project (Optional)

- Local setup using provided scripts
- Web app runs at: http://localhost:8000
- Admin GUI opens in a separate window
- Intended for local development and demonstration only

---

## Notes

- No deployment configuration included
- Sample data provided via SQL dump
- This repository represents a **portfolio version of a group project**

---

## License

MIT License (if included in this repository)
