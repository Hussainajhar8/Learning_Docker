# Random Number Generator (RNG)

This project is a simple Python script that generates a random number between a minimum and maximum number that the user enters. If the maximum number is less than the minimum number, the script prints an error message and exits.

## Getting Started
- To get started with this project, you will need to install Docker on your machine.

**Installing** 
To install and run this project, follow these steps:

- Build the Docker image for the application by running the following command in the terminal:
docker build -t rng-app .
This will create a Docker image with the name "rng-app".
- Run the Docker image to create a container:
docker run -it rng-app
- This will start the container and run the rng.py script. The -it flag allows you to interact with the container's terminal.
- The script will prompt you to enter a minimum and maximum number. Enter the desired numbers and press Enter.
The script will output a random number between the minimum and maximum numbers that you entered.

**Built With**
This project was built using Docker.
