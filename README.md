# Smart Petition System

An AI-powered web-based grievance redressal platform developed using FastAPI, SQLite, HTML, CSS, Bootstrap, JavaScript, and NLP techniques. The system allows citizens to submit petitions online, track status updates, and automatically route complaints to the appropriate government department using AI-based department detection.

## Features

* User Registration & Login
* Department Officer & Admin Dashboards
* AI-Based Department Detection
* AI-Based Urgency Detection
* Duplicate Petition Detection using NLP
* Voice-to-Text Petition Input
* Petition Status Tracking
* Real-Time Petition Map using Leaflet.js
* Department-wise Petition Filtering
* Email Notifications & Reminders
* CSV & PDF Report Download
* High Urgency Escalation System
* File Upload Support
* Responsive UI for Desktop & Mobile

## Technologies Used

### Backend

* FastAPI
* SQLite
* SQLAlchemy
* Uvicorn

### Frontend

* HTML
* CSS
* Bootstrap
* JavaScript
* Leaflet.js

### AI & NLP

* Sentence Transformers
* Cosine Similarity
* Rule-Based NLP

### Other Tools

* APScheduler
* ReportLab
* Passlib
* Jinja2 Templates

## AI Functionalities

### Department Detection

Automatically predicts the correct department based on petition title and description.

### Urgency Detection

Classifies petitions as:

* Low
* Medium
* High

### Duplicate Detection

Uses NLP similarity checking to identify repeated petitions.

## User Roles

### Petitioner

* Submit petitions
* Upload files
* Track petition status
* View submitted petitions

### Department Officer

* View department petitions
* Update status
* Download reports
* Monitor petition locations

### Admin

* Monitor all departments
* Filter petitions
* View analytics
* Download overall reports
* Handle escalations

## Map Functionality

* Displays petition locations using Leaflet Maps
* Department-wise filtering
* Resolved petitions automatically removed from map
* Supports live geolocation

## Email System

The system automatically sends:

* Petition confirmation emails
* Department notification emails
* Reminder emails
* Escalation alerts

## Installation

### Clone Repository

```bash
git clone <your-github-repository-link>
cd Smart_Petition_System
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
uvicorn main:app --reload
```

## Project Structure

```bash
Smart_Petition_System/
│
├── backend/
│   ├── main.py
│   ├── database.py
│   ├── auth.py
│   ├── ai_module.py
│   └── email_service.py
│
├── frontend/
│   ├── index.html
│   ├── admin.html
│   ├── dept.html
│   ├── user_dashboard.html
│   └── petition_detail.html
│
├── uploads/
├── requirements.txt
└── README.md
```

## Future Enhancements

* Multi-language Support
* Mobile Application
* AI Chatbot Integration
* Real-Time Notifications
* Advanced Analytics Dashboard
* Cloud Deployment

## Developed By

Karthiga S
