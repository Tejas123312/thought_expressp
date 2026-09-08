# Thought Expresso

A fully functional, asynchronous Thought Expresso blog application featuring user authentication, post creation, and AWS S3-backed profile image uploads.

## Features
- **User Authentication**: Secure JWT-based login and registration.
- **AWS S3 Integration**: High-performance profile picture uploads and processing via `boto3`.
- **Database**: Asynchronous SQLAlchemy with SQLite (configurable to Postgres).
- **Email Notifications**: Password resets sent asynchronously via SMTP.
- **Frontend**: Fully server-side rendered using Jinja2 templates and Bootstrap.

## Setup
1. Clone the repository.
2. Install dependencies using `uv`.
3. Configure your `.env` file with AWS credentials and database details.
4. Run migrations using Alembic.
5. Start the server using Uvicorn.

