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
## Docker private repository
- ####  Use the Docker run command to download the private registry. This can be done using the following command.
![image](https://user-images.githubusercontent.com/103022040/163169535-c8861596-3b66-4711-8ff0-dfce0c075f4f.png)
- #### Let’s do a docker ps to see that the registry container is indeed running.
![image](https://user-images.githubusercontent.com/103022040/163169884-5ef13202-80db-49f8-95ff-e222ab0d55a6.png)
- ####  In our example, since we have the centos image available locally, we are going to tag it to our private repository and add a tag name of centos.
![image](https://user-images.githubusercontent.com/103022040/163170735-9eae9e8e-7073-4866-8a71-86f7cbb68d09.png)
- #### Now let’s delete the local images we have for centos using the docker rmi commands. We can then download the required centos image from our private repository
![image](https://user-images.githubusercontent.com/103022040/163171695-aa28ec7b-15ff-4728-b721-477754593a59.png)
- ##### Now that we don’t have any centos images on our local machine, we can now use the following Docker pull command to pull centos image from our private repo
![image](https://user-images.githubusercontent.com/103022040/163172451-130fde8f-17dc-4add-8a0a-adb86472d87f.png)

## *DOCKER COMPOSE* 
- #### Run the following command to download the current stable release of Docker Compose
![image](https://user-images.githubusercontent.com/103022040/163757795-4b56580b-33a3-4efd-b317-6bf5ff494d76.png)
- #### Apply executable permissions to the binary:
![image](https://user-images.githubusercontent.com/103022040/163757966-d51e6847-f418-4d65-afcf-de79bfdf5fc2.png)
- #### Test your installation
![image](https://user-images.githubusercontent.com/103022040/163758272-ee9992e9-9fa3-42b0-8f12-257673a75837.png)
### How to create docker compose file
- #### To create a docker compose file first make a file having .yml extension 
![image](https://user-images.githubusercontent.com/103022040/163762460-75f61822-1343-429a-96c5-b542383b5fe7.png)
- edit file using vi editor 
![image](https://user-images.githubusercontent.com/103022040/163769897-70afb6a5-593a-47f2-819d-f16f7438323c.png)
- #### Create docker compose using following command
![image](https://user-images.githubusercontent.com/103022040/163770129-b383f9c1-5cef-4801-a1ce-265934ec3ec6.png)
- #### Adding multiple service in docker compose file
![image](https://user-images.githubusercontent.com/103022040/163771471-f85ac84e-d8a2-49e2-8623-d53a77347b59.png)
- #### If we create docker compose it will start from new service
![image](https://user-images.githubusercontent.com/103022040/163771926-f14435c6-716c-4b39-9526-0c7080471e11.png)






