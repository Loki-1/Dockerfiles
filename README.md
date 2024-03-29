![image](https://github.com/Loki-1/Dockerfiles/assets/134843197/f226b0a2-aebd-464c-b70f-43722e0ddba7)


**Docker File :**
     **A Dockerfile is a text document that contains all the commands a user could call on the command line to assemble an image**. This page describes the commands you can use in a Dockerfile.
     Docker can build images automatically by reading the instructions from a Dockerfile. 

**Docker File Instructions**
Here We have the instructions for dockerfiles to create devops tools containers

**FROM:** Specifies the base image for your Docker image. Choose an official image from Docker Hub or use a custom image.

**WORKDIR:** Sets the working directory inside the container where subsequent instructions will be executed.

**COPY:** Copies the files from your local machine to the specified directory inside the container.

**RUN:** Executes commands in the container during the build process. Use it to install dependencies or perform other setup tasks.

**ENV:** Sets environment variables inside the container.

**EXPOSE:** Informs Docker that the container listens on the specified network ports at runtime.

**VOLUME:** Defines a volume for persistent data. This is optional and depends on your application's requirements.

**CMD:** Specifies the default command to run when the container starts.

**LABEL:** Adds metadata to the image. It is useful for maintaining information about the image and the author.

**HEALTHCHECK:** Configures a health check for container health monitoring. This is optional and depends on your application.

**USER:** Sets the user for the container. This is optional and depends on your security and permission requirements.  




