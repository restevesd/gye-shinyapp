# gye-shinyapp

Build docker image:
docker build -t gye-shinyapp:latest .

Run docker container for dev:
docker run --rm -p 3838:3838 gye-shinyapp:latest

References:  
https://www.statworx.com/ch/blog/how-to-dockerize-shinyapps/

https://juanitorduz.github.io/dockerize-a-shinyapp/

https://www.r-bloggers.com/2019/02/deploying-an-r-shiny-app-with-docker/
