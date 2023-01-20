# Dockerized-Website 

It is beginner friendly project which gives the overview of the dockerization. 

Follow the steps to run the project in your environment.

Step 1 : Download the repository in your system

Step 2 : Download the desktop desktop and make the setup for runing the docker project.

Step 2 : you can run docker in wsl2 , linux , windows , or mac environment 

Step 3 : follow the below commands to run the project 

Step 4: first you have a to create a custom docker image for running the docker project . so we use dockerfile to run with has required dependencies.
        
        COMMAND : docker build -t website:latest .  
        
        /*(build -> command , -t-> which stands for tag , website ->(image name) . -> represent current location)*/
        
        COMMAND : docker images    
        
        /*(to view our images with has corresponding imaged id and size)*/
        
Step 5: To run a docker container 

        COMMAND : docker run --name demowebsite -p 8080:80 -d webiste:latest
        
                    /* ( --name -> name of the container , -p -> port , -d -> to run container in deatch mode )*/
                     
Step 6 : Type http://localhost:8080/ in your web browser 

Step 7 : Dont forget  to stop the container 
   
         COMMAND : docker stop demowebsite   
         
         /*(you stop container using container id or  container name )*/
