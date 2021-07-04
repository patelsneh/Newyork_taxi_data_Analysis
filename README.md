# Newyork_taxi_data_Analysis
 
For Downloading the Docker please refer the installation guide and download link which is below:-

Installation Guide:- https://docs.docker.com/get-docker/

Download docker from:- https://www.docker.com/products/docker-desktop

For installing the custom Docker container it is already uploaded on this repository please clone or download it.

There is certain requirements inorder to install this docker container:-
1)There must be enough space on HardDisk like nearly 20Gb.
2)Docker must be installed and running Successfully.

For installing the docker container:-

Step-1: Go to the repo and open terminal or Shell window where you had clone the code.

Step-2: Type docker in order to check whether the docker is running or not. If not open docker desktop app it will make docker run.

Step-3: Type Command:-  docker-compose up -d

Step-4: For accessing the python jupyter notebook type the following command:  docker logs --tail 50 newyork_taxi_data_analysis

It will provide you the custom link to access the jupyter notebook inorder to work with the spark on python.
