# Project in Python 🌎

This is a basic program in Python that displays a "Hello World" message on the web. The project uses Docker for containerization and has also been deployed on Heroku.

## Prerequisites

Before you begin, make sure you have **Python** installed on your system. You can download it from the official website:

[Download Python](https://www.python.org)

## Project Cloning

To get started, clone this repository to your local machine using the following command:

```bash
git clone https://github.com/jdhidal/App-Python.git
```

## Installation of Dependencies

Navigate to the project directory and run the following command to install the necessary dependencies (typically using requirements.txt):

```bash
cd App-Python
pip install -r requirements.txt
```

## Run Locally

To run the project locally on your machine:

1. **Navigate to the project directory**:
```bash
cd App-Python
```

2. **Start the application**:
```bash
python app.py
```
This will make the application available at http://localhost:5000

## Build and Run with Docker

1. Build the Docker image: Make sure you are in the project directory and then run:
```bash
docker build -t app-python .
```

2. Run the container: Once the image is built, you can run the container:
```bash
docker run -p 5000:5000 app-python
```
This will make the application available at http://localhost:5000

## Docker Hub

The image for this project is also available on Docker Hub, allowing you to run it without needing to build it locally. You can get it by running:

```bash
docker pull jdhidalgo673/app-python:latest
```

```bash
docker run -p 5000:5000 jdhidalgo673/app-python:latest
```
This will make the application available at http://localhost:5000

## Deployment to Heroku

This project is deployed on Heroku, so you can access the application directly at the following link:

[Visit the Heroku website](https://app-pythons-ef2f354011f3.herokuapp.com/)



Thanks for exploring this Hello World project in Python! 😊