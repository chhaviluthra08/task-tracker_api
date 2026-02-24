#  Task Tracker API

A production-grade FastAPI application for task management with GitHub commit integration via webhooks.

##  Features

- **Task Management**: Full CRUD operations with relationships and dependencies
- **GitHub Integration**: Auto-link commits to tasks via webhooks
- **Authentication**: JWT-based auth with role-based access control
- **Real-time Updates**: WebSocket support for live task updates
- **Advanced Search**: Full-text search and filtering
- **Analytics Dashboard**: Task completion metrics and insights

## Tech Stack

- **Framework**: FastAPI (async Python)
- **Database**: PostgreSQL with SQLAlchemy ORM
- **Authentication**: JWT tokens with bcrypt hashing
- **External APIs**: GitHub API integration
- **DevOps**: Docker, Docker Compose
- **Testing**: pytest with async support

## Quick Start

### Prerequisites
- Python 3.11+
- Docker & Docker Compose
- PostgreSQL (or use Docker)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/task-tracker-api.git
cd task-tracker-api
```

2. **Set up environment variables**
```bash
cp .env.example .env
# Edit .env with your configuration
```

3. **Run with Docker**
```bash
docker-compose up --build
```

4. **Access the API**
- API: http://localhost:8000
- Docs: http://localhost:8000/api/v1/docs
- ReDoc: http://localhost:8000/api/v1/redoc

## API Documentation

Interactive API documentation is available at `/api/v1/docs` when running the server.

## Testing
```bash
pytest tests/ -v
```

## License

MIT License - feel free to use this project for learning!

## Author

Built by [Your Name] for campus placement preparation.
