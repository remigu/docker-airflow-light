#git :
git init => init a git folder

#docker :
docker build --rm -t remigo/airflow-light . => build a docker image based on Dockerfile in the current folder
docker ps => list of working container
docker images => list of available container on computer
docker stop/start XXX => stop/start container XXX
docker-compose -f docker-compose-LocalExecutor.yml up -d => run the compose file description
docker exec -it XXX bash => bash cmd (exit to leave)
docker system prune => delete unused images
tutorial => https://github.com/puckel/docker-airflow