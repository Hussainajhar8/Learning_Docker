# Node.js Course Goal App
This project is a simple Node.js application that allows the user to set a course goal and displays it on the page. The application is built using the Express framework and uses body-parser to parse form data. The application is intended to be used as a teaching tool for learning about Docker.

## Getting Started
To get started with this project, you will need to install Docker on your machine.

## Installing
To install and run this project, follow these steps:

1. Build the Docker image for the application by running the following command in the terminal:
docker build -t nodejs-course-goal-app .
This will create a Docker image with the name "nodejs-course-goal-app".
2. Run the Docker image to create a container:
docker run -p 80:80 nodejs-course-goal-app
This will start the container and run the server.js script. The -p flag exposes port 80 on the host machine and maps it to port 80 on the container.
3. Open your web browser and navigate to http://localhost to access the application.
Built With
This project was built using the following tools and technologies:

- Node.js
- Express
- body-parser
- Docker
