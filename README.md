# Gruphoo
In this project, we used the Cuckoo Search Optimization algorithm to find the optimal path in a non-oriented graph to go from node x to node y. Follow the instructions in the README file to install both the web application and the Python implementation of the algorithm. The algorithm implementation utilizes threads for ensure efficiency.

### Donwload the Backend file

Download the file "Backend_VF_.ipynb", then execute all the cells to start the backend server.

### Run the web application

The website is deployed in Docker. For this you will need to download and install Docker.

In the command promp, run this command: 
> docker pull auragfouad/gruphooapp:v2

After the execution ends, run this command: 
> docker run -p 80:80 auragfouad/gruphooapp:v2

Now all you have to d is visit the this link: http://localhost:80 

Now you are good to go.
