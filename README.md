#Week3Exercise3
To build the image, run Docker build from a command line or terminal that is in the root directory of the application.
    $docker build -t <image-name> .
  
After it is built, you can run the image as a container.
    $docker run --name <container-name> -p 5000:5000 <image-name>
