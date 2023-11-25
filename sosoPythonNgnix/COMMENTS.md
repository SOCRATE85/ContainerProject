This is where I suppose to add all the Comments Or Suggestion 

I Launched the Linux VM on AWS and installed Docker and Docker-composed

this is the link I followed to do so : 
  -- https://www.cyberciti.biz/faq/how-to-install-docker-on-amazon-linux-2/

  Start the Docker service:
sudo systemctl start docker.service

The reason we dont keep python 2, is because on 
the DockerHub ,
the fact that I decide to go with Alpine because 
the size is smaller that the other docker images , to 
reduce the size of image

Open the port 443 to the inbound traffic 
to run the docker-compose , use the command 
" "
To see the application on the browser use the public Ip address and attached the port 
where teh application is listening to : 
 - http://3.15.145.228:8880/


 