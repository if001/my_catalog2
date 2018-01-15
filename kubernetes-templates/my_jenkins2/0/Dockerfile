FROM jenkinsci/jenkins:latest

USER root

RUN apt update 

RUN curl -fsSL get.docker.com | bash && \
sudo usermod -aG docker jenkins

TAG myjenkins/jenkins:latest
