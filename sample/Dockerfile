FROM ubuntu:latest
MAINTAINER masaru
RUN apt-get update -y
RUN apt-get install -y nginx curl git
EXPOSE 80
RUN git clone https://oauth2:c3PGLyogquYcjF4PPwah@gitlab.com/K8SLOVE/3layer-test.git
RUN cp 3layer-test/sample/sample.html /usr/share/nginx/html/index.html

CMD ["service","nginx","start"]#this line doesn't work:(
CMD ["bash"]
<<<<<<< HEAD
=======
CMD ["service" "nginx" "start"]#CMD doesn't work in k8s
>>>>>>> e1bedea4e04acf6cce8d0aa5154fca9c266d1e70

#sudo docker login registry.gitlab.com 
#sudo docker tag <tag> registry.gitlab.com/k8slove/3layer-test/<container name>
#sudo docker push registry.gitlab.com/k8slove/3layer-test/<container name>

