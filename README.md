# Gruphoo

### Welcome to Gruphoo Project!

In this project, we implemented the Cuckoo Search Optimization algorithm to find the optimal path in a non-oriented graph, navigating from node x to node y. Follow the instructions in this README file to install both the web application and the Python implementation of the algorithm. The algorithm implementation utilizes threads to ensure efficiency.

## DEMO of the application

You can watch a Demo of our application by downloading the Gruphoo Demo zip file, which contains a use case video of our application. **We highly recommend it** to get an idea of how the application looks.

## Download the Backend File

Download the file "Backend_VF.ipynb" and execute all the cells to start the backend server.

## Run the Docker Engine

### If Docker is Not Installed

Make sure you have Docker installed on your machine. You can download Docker using [this link](https://www.docker.com/)

Run Docker Desktop and create an account.

After a reboot, start Docker Desktop again to ensure the Docker Engine is running.

### If Docker is Installed

Simply start Docker Desktop and verify that no other images are using port 80 on your localhost.

You can check the ports used by other images using the command: 
```bash
docker ps
```

Now you are good to proceed to the next step.

## Run the Web Application

First, pull the Docker image for the application. Open your command prompt and run the following command: 
```bash
docker pull auragfouad/gruphooapp:v3
```

After that, start the Docker image on port 80 of your local machine using this command:
```bash
docker run -p 80:80 auragfouad/gruphooapp:v3
```

Now, visit this link: http://localhost:80/user

Enjoy!
