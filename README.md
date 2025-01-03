# Flask Application with Docker Integration

This project demonstrates the creation of a Flask web application that is containerized using Docker. It provides a lightweight and portable environment for running the application seamlessly across different systems.

---

## Overview

This Flask application is a simple yet effective demonstration of using Docker to ensure consistent deployment. The project includes steps for setting up the environment locally or via Docker, making it reproducible and easy to share.

---

## Features

- **Flask Web Application**: A lightweight and functional Python web app.  
- **Dockerized Environment**: Ensures consistent deployment across various systems.  
- **Scalable and Portable**: Easily deployable on local or cloud platforms.  

---

## Technologies Used

- **Flask**: A Python web framework for building web applications.  
- **Docker**: For containerization and consistent deployment.  
- **Python 3.9**: Programming language.  

---

## Setup Instructions

### Clone the Repository
Clone the repository from GitHub:
```bash git clone https://github.com/<your-username>/flask-cicd.git cd flask-cicd```

## Run the Application

### Using Docker

**Build the Docker Image**:
```docker build -t flask-app ```

**Run the Docker Container**:
```docker run -p 5000:5000 flask-app```

**Access the Application**: Open your browser and navigate to 
```http://127.0.0.1:5000```

**Without Docker**
Install Dependencies: Make sure you have Python 3.9 installed, then run:
```pip install flask```

**Run the Application**:
```python app.py```

**Access the Application: Open your browser and navigate to**:
```http://127.0.0.1:5000```


## Future Enhancements
- **Add CI/CD Pipeline**: Implement a CI/CD pipeline using GitHub Actions to automate testing and deployment.

- **Feedback Form**: Add a dynamic feedback form to collect user data and store it in a database.

- **Cloud Deployment**: Host the application on a cloud service like Heroku or AWS for live access and scalability.







