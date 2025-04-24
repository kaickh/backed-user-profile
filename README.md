# Backed User Profile Service

Handles user signup, authentication, and value‐selection profiles.

## 🚀 Features

- Create / read / update / delete user profiles  
- Store email, full name, and “values” preferences  
- Built with FastAPI, SQLAlchemy, and Pydantic

## 📋 Prerequisites

- Python 3.11+  
- PostgreSQL (or replace `DATABASE_URL` with your DB)  
- [.env](.env.template) configured  

## 🛠️ Installation

```bash
git clone git@github.com:kaickh/backed-user-profile-service.git
cd backed-user-profile-service
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt

