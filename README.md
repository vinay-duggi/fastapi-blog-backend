# FastAPI Production Web Application Backend (In Progress)

A comprehensive, production-ready web application and REST API built with Python and FastAPI. This repository demonstrates modern backend architecture, from initial route creation and strict data validation to cloud storage integration and dual-strategy deployment. 

## 🚀 Features

* **API & Routing:** Clean architecture using FastAPI routers, supporting a programmatic JSON API
* **Data Validation & Schemas:** Strict request and response validation utilizing Pydantic models.
* **Authentication & Security:** Secure user registration and login workflows using argon2 password hashing and JWT (JSON Web Tokens) for route protection.
* **Database Management:** Complete CRUD operations managed via SQLAlchemy ORM, with Alembic handling robust database migrations.
* **Cloud Storage & File Handling:** Secure file uploads, with storage scaled from local disk to AWS S3 using Boto3.
* **Asynchronous Processing:** Fully async route execution and background task management for workflows like password reset emails.
* **Pagination:** Efficient data retrieval and payload management for high-volume database queries.
* **Comprehensive Testing:** Automated test suite implemented with Pytest to ensure API reliability.
* **Production Deployment:** Configured for two distinct production environments:
  1. **VPS Deployment:** Ubuntu Linux, Nginx reverse proxy, and Let's Encrypt SSL certificates.
  2. **Cloud-Native:** Containerized with Docker for serverless platform deployment.

## 🛠️ Tech Stack

* **Core Framework:** FastAPI (Python), Uvicorn
* **Database:** PostgreSQL (migrated from SQLite), SQLAlchemy, Alembic
* **Security:** JWT, Argon2
* **Cloud & Storage:** AWS S3, Boto3
* **Testing:** Pytest
* **Deployment:** Docker, Nginx, Linux (Ubuntu)
