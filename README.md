# Hello world App
Simple React "Hello World" application created as a learning exercise for Git basics, CSS, HTML and Docker.

## Project components.
- HTML
- CSS
- Node js 
- Javascript
- Docker   

## Project Modifications 
  - Remove the starter react code
  - Replace it with "Hello world"
  - Using CSS styling; style the message to different color, display format and font.

## Getting Started
- Fork the repository
- clone it local machine
- Vscode terminal:
    - Navigate to root directory of the app.
    - Also to code the changes

### Create a Dockerfile
 - Add the instructions to build the docker image.
 
### Create .dockerignore file
 - Add the commands need to specify which files and directories should be excluded from the Docker build context

### Build and run Dockerized Hello world App
 - In the root directory run:
      
       docker build -t hello-world-app .
 - Tags image and specify build context
  
## Running the Docker container   
      docker run -p 3000:3000 hello-world-app      
  - Success message will be displayed
## Accessing your application
  - Open the browser and go to
    
        http://localhost:3000
  - You should see a React app running inside a Docker container.

