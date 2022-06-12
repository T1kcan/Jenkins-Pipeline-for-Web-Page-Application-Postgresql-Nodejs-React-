# Jenkins-Pipeline-for-Web-Page-Application-Postgresql-Nodejs-React-
This project aims to create a Jenkins pipeline to deploy web-page written Nodejs and React Frameworks on AWS Cloud Infrastructure using Ansible. Building infrastructure process is managing with control node utilizing Ansible. This infrastructure has 1 jenkins server (`Amazon Linux 2 AMI`) as ansible control node and 3 EC2's as worker node (`Red Hat Enterprise Linux 8 with High Availability`). These EC2's will be launched on AWS console. Web-page has 3 main components which are postgresql, nodejs, and react. Each component is serving in Docker container on EC2s dedicated for them. Postgresql is serving as Database of web-page. Nodejs controls backend part of web-side and react controls frontend side of web-page. The code was written by Clarusway's Developers and architecture will be created by Clarusway's AWS &amp; DevOps Team.
