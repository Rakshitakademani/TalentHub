# TalentHub – Placement Management Portal

## 1. Project Overview

TalentHub is a placement management portal designed to simplify and organize campus placement activities. It provides a centralized platform for managing placement-related information and workflows.

## 2. Problem Statement

Campus placement activities often involve managing student details, company information, eligibility criteria, and placement updates through manual or disconnected processes.

TalentHub aims to provide a centralized platform that makes placement information easier to access, organize, and manage.

## 3. Objectives

- Centralize placement-related information.
- Organize student and company details.
- Simplify placement management activities.
- Improve accessibility of placement information.
- Reduce manual record management.

## 4. Key Features

- Student information management.
- Placement information management.
- Company and recruitment details.
- Placement activity tracking.
- User authentication.
- Centralized placement portal.

## 5. Technology Stack

| Component | Technology |
|---|---|
| Backend | Python |
| Backend Framework | FastAPI |
| ORM | SQLAlchemy |
| Data Validation | Pydantic |
| Database Driver | aiosqlite |
| Authentication | JWT |
| Password Security | Passlib / bcrypt |
| Server | Uvicorn |

## 6. System Architecture

The application follows a client-server architecture.

- **Frontend:** Provides the user interface.
- **Backend:** Handles application logic and API requests.
- **Database:** Stores application information.

## 7. Project Structure

```text
TalentHub/
│
├── backend/
│   ├── main.py
│   └── ...
│
├── frontend/
│   └── ...
│
├── requirements.txt
└── README.md
```

*Note: Actual project structure may contain additional files and folders.*

## 8. Installation and Setup

### Prerequisites

- Python 3.11 or above
- pip
- Node.js and npm (if required by the frontend)
- Git

### Step 1: Clone Repository

```bash
git clone https://github.com/Rakshitakademani/TalentHub.git
cd TalentHub
```

### Step 2: Create Virtual Environment

```bash
python -m venv venv
```

Activate on Windows:

```cmd
venv\Scripts\activate
```

### Step 3: Install Backend Dependencies

```bash
pip install -r requirements.txt
```

Run this command from the directory containing `requirements.txt`.

### Step 4: Configure Environment

Create a `.env` file if required and configure the necessary environment variables.

### Step 5: Run Backend

From the directory containing `main.py`:

```bash
uvicorn main:app --reload --port 8000
```

### Step 6: Run Frontend

If the frontend uses Node.js:

```bash
npm install
npm run dev
```

Use the actual scripts defined in the frontend's `package.json`.

## 9. API Documentation

If enabled, FastAPI Swagger documentation is available at:

```text
http://127.0.0.1:8000/docs
```

## 10. Security

- JWT-based authentication.
- Password hashing.
- Input validation.
- Secure environment configuration.

Never upload passwords, tokens, or secret keys to GitHub.

## 11. Expected Outcome

TalentHub aims to provide an organized and accessible placement management platform that simplifies placement-related activities and improves information management.

## 12. Project Information

**Project Name:** TalentHub – Placement Management Portal

**GitHub Repository:** https://github.com/Rakshitakademani/TalentHub

---

*TalentHub – Simplifying Campus Placement Management.*
