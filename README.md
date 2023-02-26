# jenkins-elera-server

* sudo yum update -y
* sudo amazon-linux-extras install docker
* sudo service docker start
* sudo usermod -a -G docker jenkins
* docker run -p 8080:8080 -p 50000:50000 --restart=on-failure jenkins/jenkins:lts-jdk11
