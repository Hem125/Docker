# Docker
## *Installation of Docker in Ubuntu*
- #### Type sudo apt install docker.io or sudo snap install docker to initialize the process of installing docker
![image](https://user-images.githubusercontent.com/103022040/162896996-a32d2d1f-dbdc-4ec1-a0b4-906ccba617ed.png)
- #### After installation we can check the docker version
![image](https://user-images.githubusercontent.com/103022040/162897960-bbf099b0-97d4-42e0-8ad5-341f3f57ef04.png)
- #### Go to docker hub and sign in , in case you dont have account sign up
![image](https://user-images.githubusercontent.com/103022040/162900493-b5f6b06d-4777-4736-9525-e1033628f433.png)
##  Docker Image
- #### to download a Docker image called CentOS 7, issue the following command
![image](https://user-images.githubusercontent.com/103022040/162904904-b3fadc0c-159c-420d-a72d-8aaa4a0d43d3.png)
 - #### download it locally by running the below command
 ![image](https://user-images.githubusercontent.com/103022040/162905194-4cc1d63a-7a30-49f3-bd19-6a06c51ea6d6.png)
- #### To list all the available Docker images on your host run the following command.
![image](https://user-images.githubusercontent.com/103022040/162905465-f7528c0a-ace9-42b0-9606-dbad9318fd9e.png)
- #### use the below command to delete or remove docker image
![image](https://user-images.githubusercontent.com/103022040/162906041-d954c65c-98e5-4c1a-8070-c0f21350f950.png)
## Run a Docker Container in Ubuntu
- #### To run the containers again, first you need to get the Container ID or Name by running the following command
![image](https://user-images.githubusercontent.com/103022040/162923275-d46225b5-ad9d-471b-a0cc-607bb62fca19.png)
- #### Once the Container ID or Name has been acquired, you can start the container using the following command:
![image](https://user-images.githubusercontent.com/103022040/162923845-87e67c3a-269b-4bed-9352-dbbd74fa491e.png)
- #### To stop the running container run docker stop command by specifying the Container ID or Name.
![image](https://user-images.githubusercontent.com/103022040/162924356-328574eb-fc91-4482-9604-1ff1791cd83a.png)
## DockerFile
- #### create a file using vi editor and cat command to display its content
 ![image](https://user-images.githubusercontent.com/103022040/162944146-c6a8645d-e091-4460-a7cd-bda16e24c02e.png)
- #### than build using docker build command the file will execute stepwise
![image](https://user-images.githubusercontent.com/103022040/162944524-8e54ca01-b708-4397-8252-197ebd678d3e.png)
## Managing port
- #### logged into docker hub 
![image](https://user-images.githubusercontent.com/103022040/162949102-3628e0a6-9d51-4f39-9874-81ded48fb4b7.png)
- #### Next, let’s browse and find the Jenkins image 
![image](https://user-images.githubusercontent.com/103022040/162949730-e35b56f1-2f77-4a1c-af51-542015fbe91e.png)
- #### see the Docker pull command. This will be used to download the Jenkins Image onto the local Ubuntu server.
![manage port second step](https://user-images.githubusercontent.com/103022040/162950235-ffac7b6d-7b6f-428e-8730-7e24a30885c2.PNG)
- #### Now go to the Ubuntu server and run the command 
![image](https://user-images.githubusercontent.com/103022040/162951565-1267478c-3612-4cdf-9c9b-f20eea309d04.png)
- #### To understand what ports are exposed by the container, you should use the Docker inspect command to inspect the image.
![image](https://user-images.githubusercontent.com/103022040/162952091-930dd3b4-947b-40f1-a1a8-23d4b424180a.png)
## Docker Network
- #### This command can be used to list all the networks associated with Docker on the host.
![image](https://user-images.githubusercontent.com/103022040/162958666-f50f18f2-c90e-4c6c-b0af-83a01c717307.png)
- #### The command will output all the details about the network.
![image](https://user-images.githubusercontent.com/103022040/162960066-ab5799a2-12df-4560-805b-7fcfca0cdcd6.png)
- #### One can create a network in Docker before launching containers. This can be done with the following command
![image](https://user-images.githubusercontent.com/103022040/162960412-8849288e-64fc-4b68-ba24-b76e3ae7d49e.png)
- #### we can inspect details about our new network just created
![image](https://user-images.githubusercontent.com/103022040/162960755-acd5f654-22ac-4cbb-8c58-949f6c02ac0f.png)





