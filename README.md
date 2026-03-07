# Simple Notes App – Docker Practice Project

This is a simple Notes application built with **React (frontend)** and **Django (backend)**.
The project is used to practice **Docker image creation and container execution**.

## Prerequisites

Make sure the following tool is installed:

* Docker

## Installation

### 1. Clone the repository

```
git clone https://github.com/Coder-Sourabh/django-notes-app-docker.git
```

### 2. Navigate to the project directory

```
cd django-notes-app-docker
```

### 3. Build the Docker image

```
docker build -t notes-app:latest .
```

### 4. Run the container

```
docker run -d -p 8000:8000 notes-app:latest
```

### 5. Access the application

Open your browser and visit:

```
http://localhost:8000
```

## Nginx (Optional)

You can configure **Nginx as a reverse proxy** to expose the application in a production environment.

Install Nginx:

```
sudo apt update
sudo apt install nginx
```
