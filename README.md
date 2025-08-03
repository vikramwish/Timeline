# Timeline

An interactive job history website enabling users to elegantly display their professional experiences, timelines, and key learnings at various organizations.

## Features

* Interactive, visual timeline representation
* Ability to dynamically add new job experiences
* Persistent data storage using MongoDB
* Responsive design for seamless viewing across devices
* Easy deployment using Docker containers

## Tech Stack

**Frontend:**

* HTML
* CSS
* JavaScript

**Backend:**

* Flask (Python)

**Database:**

* MongoDB

**Deployment:**

* Docker

## Project Structure

```
job-timeline/
├── Dockerfile
├── docker-compose.yml
├── requirements.txt
├── app/
│   ├── app.py
│   ├── static/
│   │   ├── style.css
│   │   └── script.js
│   └── templates/
│       └── index.html
```

## Setup and Installation

### Prerequisites

* Docker
* Docker Compose

### Clone Repository

```bash
git clone <your-repo-url>
cd job-timeline
```

### Run with Docker

```bash
docker-compose up --build
```

### Access the Application

Navigate to:

```
http://localhost:5000
```

## Usage

* Add job experiences through the intuitive input form.
* View added experiences chronologically on the interactive timeline.

## Potential Enhancements

* User authentication and personalized timelines
* Editing and deleting existing timeline entries
* Enhanced UI/UX with animations
* Cloud deployment and hosting
