# My Personal Profile

A full-stack personal profile application built with React, Flask, and Supabase.

## Project Structure

```
my-personal-profile/
├── backend/                 # Flask Application
│   ├── app.py
│   ├── requirements.txt
│   └── .env                 # Local variables (gitignored)
├── frontend/                # React Application
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── .env                 # Local variables (gitignored)
├── .gitignore               # Ignores node_modules, __pycache__, and .env
└── README.md
```

## Getting Started

### Backend Setup

```bash
cd backend
python -m venv venv
venv\Scripts\activate  # On Windows
pip install -r requirements.txt
python app.py
```

### Frontend Setup

```bash
cd frontend
npm install
npm start
```

## Environment Variables

Create `.env` files in both `backend/` and `frontend/` directories with your Supabase credentials.