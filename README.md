# Devops_Project
A HTML page deployed using Docker on an Amazon EC2 instance.

The page in itself is a simple page styled with bootstrap. The webhook has been configured to run a job on Jenkins that will pull the this repo, build an image, push the updated image to dockerhub, pull it back 
and run a container. The webhook has been set to be triggered only by the push events.
