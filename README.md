# vite-react-js-docker

Implemented as per this [tutorial](https://javascript.plainenglish.io/step-by-step-guide-to-dockerize-react-app-created-using-vite-90772423f7fb)


### To Run this project
- Navigate to git bash and clone the project.

  ```shell
  git clone https://github.com/kcterala/vite-react-js-docker.git
  ```

- Move to vite-react-js-docker folder.
  Build the docker image by this command.

  ```shell
  docker build -t [imagename] .
  ```
  
  - Give any name in the place of [imagename].
  
  
- Run the created image by this command.

  ```shell
  docker run -p 3000:3000 [imagename]
  ```
  
  - [imagename] is the name given in the last step.
  
  
  
Check localhost:3000/ and the react project should be up and running.


