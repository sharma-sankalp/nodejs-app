# Hello World App

This application is a simple Node.js web app that displays a static "Hello, World!" page using the Express framework. It is based on the [Express Hello World Example](https://github.com/expressjs/express/tree/master/examples/hello-world).

## Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)

## Getting Started

### Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/your-username/hello-world-app.git
cd hello-world-app

Install Dependencies
Install the required dependencies using npm:

npm install

Run the Application
Start the application by running:

npm start

The application will start and listen on port 8000. You should see the following output:

Express started on port 8000

Access the Application
Open your web browser and go to:

http://localhost:8000

You should see the message "Hello World".

Generating Artifacts
Artifacts refer to the build outputs or any files generated as a result of running your application or build process. In this context, since this is a simple web app, artifacts might include any logs, compiled files, or packaged applications. For this app, the main focus will be on Docker artifacts.

Docker Setup
To generate Docker artifacts, follow these steps:

Build the Docker Image
To containerize the application and generate the Docker image artifact, run:

docker build -t hello-world-app .

Run the Docker Container
Run the Docker container:

docker run -p 8000:8000 hello-world-app


Now, open your web browser and go to:

http://localhost:8000

You should see the message "Hello World".

