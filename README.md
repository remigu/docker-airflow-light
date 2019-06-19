# README

## git :

git init =&gt; init a git folder git clone [https://github.com/remigu/docker-airflow-light.git](https://github.com/remigu/docker-airflow-light.git)

## docker :

docker build --rm -t remigo/airflow-light . =&gt; build a docker image based on Dockerfile in the current folder docker ps =&gt; list of working container docker images =&gt; list of available container on computer docker stop/start XXX =&gt; stop/start container XXX docker-compose -f docker-compose-LocalExecutor.yml up -d =&gt; run the compose file description docker exec -it XXX bash =&gt; bash cmd \(exit to leave\) docker system prune =&gt; delete unused images tutorial =&gt; [https://github.com/puckel/docker-airflow](https://github.com/puckel/docker-airflow)

docker exec -ti b8ded5a19b6f airflow variables -i variables.json

