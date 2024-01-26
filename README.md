# Gruphoo
In this project, we used the Cuckoo Search Optimization algorithm to find the optimal path in a non-oriented graph to go from node x to node y. Follow the instructions in the README file to install both the web application and the Python implementation of the algorithm. The algorithm implementation utilizes threads for ensure efficiency.

### Donwload the Backend file

Download the file "Backend_VF_.ipynb", then execute all the cells to start the backend server.

### Run the docker Engine

#### If you dont have Docker instaled

Make sure you have docker installed on your machine. You can download Docker using [this link](https://www.docker.com/)

Run Docker Desktop and create a account.

After you reboot start Docker desktop again to make sure the Docker Engine started.

#### If you have Docker installed

You only need to start Docker Desktop, and make sure that no other image is using the port 80 on your localhost.

You can check the ports used by other images using the command:
`docker ps`

Now you are goo to go to the next step.

### Run the web application

First you will need to pull the docker image of the application.

For this open your command promp, and run this command: 
`docker pull auragfouad/gruphooapp:v3`

After that you will need to start the docker image on the port 80 of your local machine using this command:
`docker run -p 80:80 auragfouad/gruphooapp:v3`

Now all you have to do is visit the this link: http://localhost:80/user

Enjoy.
