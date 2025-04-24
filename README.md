
# Ticket Management Application – Multi-Environment Deployment with Docker

This project is a **multi-environment ticket management system** composed of:

-  A Flask **development backend**
-  A Flask **production backend**
-  A React **frontend**
- A **MongoDB** database

The application is containerized using **Docker** and deployed using **Docker Compose**, supporting clean separation between development and production backends.

---

---

## Prerequisites

Before you begin, ensure you have the following installed:

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

---
## Environment Configuration

Create the following `.env` files in the root directory:

### `.env.dev`
```env
MONGO_URI=mongodb://mongo:27017/devdb
REACT_APP_API_URL=http://localhost:5001




  



---


