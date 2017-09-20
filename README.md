# Docker-common-config
Docker **stack.yml** file template for various applications

## How to use
- Create a folder named ***the program you are using***
- Inside that folder create a folder named **data**
- Copy the corresponding **stack.yml** file into that folder
- Config the **stack.yml** file as you wish
- To start the application using **Docker Swarm** mode run the command:  
    ```
    docker swarm init  
    docker stack deploy -c stack.yml <the-program-you-are-using>
    ```
- **Alternatively** you can run **Docker Compose** command:  
    ```
    docker-compose -f stack.yml up
    ```
