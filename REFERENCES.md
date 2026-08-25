# Tutorial References

====================================================================================================
PYTHON FASTAPI TUTORIAL SERIES - COREY SCHAFER
Playlist URL: https://www.youtube.com/playlist?list=PL-osiE80TeTsak-c-QsVeg0YYG_0TeyXI
Master Repository: https://github.com/CoreyMSchafer/FastAPI-Full-Course
Full 14-Hour Single Video: https://www.youtube.com/watch?v=iukOehU5aF4
====================================================================================================

## Progress Tracker
- [x] Part 01 - Getting Started
- [x] Part 02 - Templates
- [ ] Part 03 - Path Parameters   <-- CURRENTLY WORKING ON THIS
- [ ] Part 04 - Pydantic Schemas
- [ ] Part 05 - Database
- [ ] Part 06 - Complete CRUD
- [ ] Part 07 - Async Await
- [ ] Part 08 - Routers
- [ ] Part 09 - Frontend Forms
- [ ] Part 10 - Authentication
- [ ] Part 11 - Authorization
- [ ] Part 12 - File Uploads
- [ ] Part 13 - Pagination
- [ ] Part 14 - Password Reset / Background Tasks
- [ ] Part 15 - Postgres + Alembic
- [ ] Part 16 - AWS S3 Image Uploads
- [ ] Part 17 - Testing
- [ ] Part 18 - Deployment VPS
- [ ] Part 19 - Deployment Docker/GCR

[Part 01] Getting Started - Web App + REST API
- Description: Setting up FastAPI, creating initial endpoints, returning JSON responses, and exploring automatic Swagger documentation.
- YouTube: https://www.youtube.com/watch?v=7AMjmCTumuo
- GitHub:  https://github.com/CoreyMSchafer/FastAPI-01-Getting-Started

[Part 02] HTML Frontend for Your API - Jinja2 Templates
- Description: Rendering dynamic HTML pages using Jinja2 templates, serving static assets (CSS/JS), and building UI layouts.
- YouTube: TODO (paste the Part 2 video URL here)
- GitHub:  https://github.com/CoreyMSchafer/FastAPI-02-Templates

[Part 03] Path Parameters - Validation and Error Handling
- Description: Working with dynamic URL path parameters, type conversions, automatic validation, and raising custom HTTP exceptions.
- YouTube: https://www.youtube.com/watch?v=WRjXIA5pMtk
- GitHub:  https://github.com/CoreyMSchafer/FastAPI-03-Path-Parameters

[Part 04] Pydantic Schemas - Request and Response Validation
- Description: Defining data contracts with Pydantic BaseModel, validating request payloads, filtering sensitive response data, and nested models.
- YouTube: https://www.youtube.com/watch?v=9GHxnttXxrA
- GitHub:  https://github.com/CoreyMSchafer/FastAPI-04-Pydantic-Schemas

[Part 05] Adding a Database - SQLAlchemy Models and Relationships
- Description: Setting up SQLite with SQLAlchemy ORM, creating database models, defining foreign keys and relationships, and session dependency injection.
- YouTube: https://www.youtube.com/watch?v=NvOV3ig2tGY
- GitHub:  https://github.com/CoreyMSchafer/FastAPI-05-Database

[Part 06] Completing CRUD - Update and Delete (PUT, PATCH, DELETE)
- Description: Implementing full CRUD functionality, understanding PUT vs. PATCH for updates, handling deletions, and status codes.
- YouTube: https://www.youtube.com/watch?v=VyoGAoxQhxM
- GitHub:  https://github.com/CoreyMSchafer/FastAPI-06-Complete-Crud

[Part 07] Sync vs Async - Converting Your App to Asynchronous
- Description: Comparing synchronous vs. asynchronous execution, understanding event loops, and migrating SQLAlchemy to async/await sessions.
- YouTube: https://www.youtube.com/watch?v=2JPDt-Jp6fM
- GitHub:  https://github.com/CoreyMSchafer/FastAPI-07-Async-Await

[Part 08] Routers - Organizing Routes into Modules with APIRouter
- Description: Splitting large monolithic apps into clean modular routers using APIRouter, route prefixes, and tags.
- YouTube: TODO (paste the Part 8 video URL here)
- GitHub:  https://github.com/CoreyMSchafer/FastAPI-08-Routers

[Part 09] Frontend Forms - Connecting JavaScript to Your API
- Description: Building browser-based forms with JavaScript Fetch API, updating UI without page reloads, and displaying feedback modals.
- YouTube: https://www.youtube.com/watch?v=vqjZOyT4QRs
- GitHub:  https://github.com/CoreyMSchafer/FastAPI-09-Frontend-Forms

[Part 10] Authentication - Registration and Login with JWT
- Description: Hashing user passwords securely using passlib/bcrypt, implementing user registration, and issuing JSON Web Tokens (JWT).
- YouTube: https://www.youtube.com/watch?v=Go4wYJJhR3k
- GitHub:  https://github.com/CoreyMSchafer/FastAPI-10-Authentication

[Part 11] Authorization - Protecting Routes and Verifying Current User
- Description: Writing OAuth2 authentication dependencies, decoding JWT tokens to verify active user identity, and route-level protection.
- YouTube: https://www.youtube.com/watch?v=MY0TFMMm9B0
- GitHub:  https://github.com/CoreyMSchafer/FastAPI-11-Authorization

[Part 12] File Uploads - Image Processing, Validation, and Storage
- Description: Handling multipart form file uploads, validating file extensions and sizes, resizing images with Pillow, and local disk storage.
- YouTube: https://www.youtube.com/watch?v=AExumWjfbyo
- GitHub:  https://github.com/CoreyMSchafer/FastAPI-12-File-Uploads

[Part 13] Pagination - Loading More Data with Query Parameters
- Description: Managing large datasets with limit/offset query parameters, calculating page counts, and frontend infinite scroll / pagination.
- YouTube: TODO (paste the Part 13 video URL here)
- GitHub:  https://github.com/CoreyMSchafer/FastAPI-13-Pagination

[Part 14] Password Reset - Email, Tokens, and Background Tasks
- Description: Implementing secure password reset flows, generating time-sensitive reset tokens, and dispatching emails with FastAPI BackgroundTasks.
- YouTube: https://www.youtube.com/watch?v=4HxjBvZMAg8
- GitHub:  https://github.com/CoreyMSchafer/FastAPI-14-Password-Reset-Background-Tasks

[Part 15] PostgreSQL and Alembic - Database Migrations for Production
- Description: Replacing SQLite with PostgreSQL (psycopg3 async), configuring Alembic database migration environments, and running revision schemas.
- YouTube: TODO (paste the correct Part 15 video URL here)
- GitHub:  https://github.com/CoreyMSchafer/FastAPI-15-Postgres-Alembic

[Part 16] AWS S3 and Boto3 - Moving File Uploads to the Cloud
- Description: Migrating local file storage to AWS S3 buckets using boto3, IAM security credentials, and serving cloud-hosted user uploads.
- YouTube: TODO (paste the correct Part 16 video URL here)
- GitHub:  https://github.com/CoreyMSchafer/FastAPI-16-AWS-S3-Image-Uploads

[Part 17] Testing the API - Pytest, Fixtures, and Mocking External Services
- Description: Writing automated test suites with Pytest, using TestClient/AsyncClient, database fixtures, and mocking external services like S3/Email.
- YouTube: https://www.youtube.com/watch?v=SO7m7nod0ts
- GitHub:  https://github.com/CoreyMSchafer/FastAPI-17-Testing

[Part 18] Deploy to a VPS - Security, Nginx, SSL, and Custom Domain
- Description: Provisioning an Ubuntu server, configuring SSH/firewall, setting up Gunicorn/Uvicorn systemd services, reverse proxying with Nginx, and free SSL with Certbot.
- YouTube: https://www.youtube.com/watch?v=wd1wt2d0eus
- GitHub:  https://github.com/CoreyMSchafer/FastAPI-18-Deployment-VPS

[Part 19] Deploy with Docker - Serverless Containers and Custom Domain
- Description: Multi-stage Dockerfile builds, running multi-container stacks with Docker Compose, and deploying serverless containers to cloud services (GCR/Fly.io).
- YouTube: https://www.youtube.com/watch?v=eqjngvKfabg
- GitHub:  https://github.com/CoreyMSchafer/FastAPI-19-Deployment-Docker-GCR