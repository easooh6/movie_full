# 🎬 Cinema Ticket Booking System# 🎬 Cinema Ticket Booking System# 🎬 Cinema Ticket Booking System



![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=flat-square&logo=python&logoColor=white)

![FastAPI](https://img.shields.io/badge/FastAPI-0.104+-009688?style=flat-square&logo=fastapi&logoColor=white)

![React](https://img.shields.io/badge/React-18.2+-61DAFB?style=flat-square&logo=react&logoColor=black)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14+-316192?style=flat-square&logo=postgresql&logoColor=white)![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=flat-square&logo=python&logoColor=white)![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=flat-square&logo=python&logoColor=white)

![Redis](https://img.shields.io/badge/Redis-6+-DC382D?style=flat-square&logo=redis&logoColor=white)

![FastAPI](https://img.shields.io/badge/FastAPI-0.104+-009688?style=flat-square&logo=fastapi&logoColor=white)![FastAPI](https://img.shields.io/badge/FastAPI-0.104+-009688?style=flat-square&logo=fastapi&logoColor=white)

## 📋 Overview

![React](https://img.shields.io/badge/React-18.2+-61DAFB?style=flat-square&logo=react&logoColor=black)![React](https://img.shields.io/badge/React-18.2+-61DAFB?style=flat-square&logo=react&logoColor=black)

Modern full-stack web application for cinema ticket booking. Built with asynchronous Python backend and React frontend, featuring real-time seat selection, JWT authentication, and Redis caching for optimal performance.

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14+-316192?style=flat-square&logo=postgresql&logoColor=white)![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14+-316192?style=flat-square&logo=postgresql&logoColor=white)

## ✨ Features

![Redis](https://img.shields.io/badge/Redis-6+-DC382D?style=flat-square&logo=redis&logoColor=white)![Redis](https://img.shields.io/badge/Redis-6+-DC382D?style=flat-square&logo=redis&logoColor=white)

### For Users

- 🎬 Browse movie catalog with detailed information## About## About

- 📅 Select showtimes and view seat availability

- 💺 Interactive hall layout for seat selection

- 🛒 Shopping cart functionality

- 🔐 Secure JWT authentication with auto-refreshWeb application for automated cinema ticket booking. Users can browse movies, select showtimes, book seats through an interactive hall layout, and manage their cart. Admins have full control over movies, halls, seats, and sessions through a dedicated panel.Web application for automated cinema ticket booking. Users can browse movies, select showtimes, book seats through an interactive hall layout, and manage their cart. Admins have full control over movies, halls, seats, and sessions through a dedicated panel.



### For Admins

- 🎥 Complete movie management (CRUD)

- 🏛️ Hall and seat configuration## Tech Stack## Tech Stack

- 📊 Session scheduling and pricing

- 👥 User role management



### Technical Features**Backend:****Backend:**

- ⚡ Asynchronous architecture for high performance

- 🚀 Redis caching (20x speed improvement)- FastAPI - async web framework- FastAPI - async web framework

- 🔒 Role-based access control

- 📱 Responsive design- SQLAlchemy - async ORM for PostgreSQL- SQLAlchemy - async ORM for PostgreSQL

- 🧪 80%+ test coverage

- PostgreSQL - relational database- PostgreSQL - relational database

## 🛠️ Tech Stack

- Redis - caching system- Redis - caching system

### Backend

- **FastAPI** - High-performance async web framework- JWT - token-based authentication- JWT - token-based authentication

- **SQLAlchemy** - Async ORM with PostgreSQL

- **PostgreSQL** - Primary database- Alembic - database migrations- Alembic - database migrations

- **Redis** - Caching and session management

- **JWT** - Authentication with refresh tokens- Pytest - testing framework- Pytest - testing framework

- **Alembic** - Database migrations

- **Pytest** - Testing framework



### Frontend**Frontend:****Frontend:**

- **React** - UI library

- **Axios** - HTTP client with interceptors- React - UI library- React - UI library

- **CSS3** - Modern styling and animations

- Axios - HTTP client with interceptors- Axios - HTTP client with interceptors

## 🚀 Quick Start

- CSS3 - responsive design- CSS3 - responsive design

### Prerequisites

- Python 3.11+

- Node.js 16+

- PostgreSQL 14+## Key Features## Key Features

- Redis 6+



### Installation

- Real-time seat selection with interactive hall layout- Real-time seat selection with interactive hall layout

1. **Clone the repository**

```bash- JWT authentication with automatic token refresh- JWT authentication with automatic token refresh

git clone https://github.com/easooh6/movie_full.git

cd movie_full- Redis caching (20x performance improvement)- Redis caching (20x performance improvement)

```

- Role-based access control (admin/user)- Role-based access control (admin/user)

2. **Setup Backend**

```bash- Async architecture for high concurrency- Async architecture for high concurrency

cd pythonproject/back

- 3NF database normalization- 3NF database normalization

# Create virtual environment

python -m venv venv- 80%+ test coverage- 80%+ test coverage

source venv/bin/activate  # Windows: venv\Scripts\activate



# Install dependencies

pip install -r requirements.txt## Quick Start## Quick Start



# Setup database

alembic upgrade head

```bash```bash

# Run server

uvicorn src.main:app --reload# Clone# Clone

```

git clone https://github.com/easooh6/movie_full.gitgit clone https://github.com/easooh6/movie_full.git

3. **Setup Frontend**

```bashcd movie_fullcd movie_full

cd ../front



# Install dependencies

npm install# Backend# Backend



# Start development servercd pythonproject/backcd pythonproject/back

npm start

```python -m venv venvpython -m venv venv



4. **Access Application**source venv/bin/activatesource venv/bin/activate

- 🌐 Frontend: http://localhost:3000

- 🔌 API: http://localhost:8000pip install -r requirements.txtpip install -r requirements.txt

- 📚 API Docs: http://localhost:8000/docs

alembic upgrade headalembic upgrade head

## 📁 Project Structure

uvicorn src.main:app --reloaduvicorn src.main:app --reload

```

pythonproject/

├── back/                    # Backend application

│   ├── src/# Frontend# Frontend

│   │   ├── infrastructure/  # Database models & CRUD

│   │   ├── services/        # Business logiccd ../frontcd ../front

│   │   ├── presentation/    # API routes

│   │   ├── schemas/         # Pydantic modelsnpm installnpm install

│   │   └── tests/          # Test suite

│   └── alembic/            # Database migrationsnpm startnpm start

└── front/                  # Frontend application

    ├── src/``````

    │   ├── components/     # React components

    │   ├── pages/         # Page components

    │   └── TempData/      # API services

    └── public/            # Static assets**Access:****Access:**

```

- Frontend: http://localhost:3000- Frontend: http://localhost:3000

## 🗄️ Database Schema

- API: http://localhost:8000- API: http://localhost:8000

The application uses a normalized PostgreSQL database in 3NF:

- Docs: http://localhost:8000/docs- Docs: http://localhost:8000/docs

- **Users** → Authentication and roles

- **Movies** → Film catalog
- **Halls** → Cinema hall layouts  
- **Seats** → Individual seat configuration
- **Seances** → Movie sessions
- **Cart** → User shopping cart

## 🧪 Testing

```bash
# Run all tests
pytest

# Run with coverage
pytest --cov=src --cov-report=html

# Run specific tests
pytest src/tests/test_movie.py -v
```

## ⚡ Performance

- **Async Operations**: Non-blocking I/O for thousands of concurrent users
- **Redis Caching**: 200ms → 10ms response time improvement
- **Database Optimization**: Indexed queries and connection pooling
- **Frontend Optimization**: Token interceptors and state management

## 🔐 Security

- JWT authentication with refresh token rotation
- Bcrypt password hashing
- Role-based access control (RBAC)
- Input validation with Pydantic
- CORS configuration
- SQL injection prevention

## 🚀 Deployment

The application is designed for easy deployment:
- Stateless backend for horizontal scaling
- Redis for shared session storage
- Environment-based configuration
- Docker-ready architecture

