# DotNetIsolatedDockerApp
Sample dotnet isolated(out of process) function app with DOCKER support.
 - NET 6.0
 - Function V4 runtime.
 
### To build the image

To build the image, run the following command from the root of the project(where `.Dockerfile` is present).

`docker build -t yourappname -f .\Dockerfile .`

### To run the container

`docker run -p 8080:80 {imageName}`

Open a browser and check `http://localhost:8080/api/function1`
