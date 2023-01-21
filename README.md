This template uses terraform to launch an ec2 instance, deploy docker on the instance, build the docker image, push the image to docker-hub, start the container and output the website url in terraform to test the website is running properly. Security best practice is to use arguments, env variables etc to pass secrets for codes to be committed to repositories for collaborative projects.
