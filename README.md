

python -m venv .env

https://dev.to/mvillarrealb/creating-a-spark-standalone-cluster-with-docker-and-docker-compose-2021-update-6l4

funcionaa pra sistemas arm-based!! 

docker build -t cluster-apache-spark:3.0.2 .

docker-compose up -d

export SPARK_MASTER=spark://spark-master:7077

SPARK_LOCAL_IP=0.0.0.0

Spark Master

http://localhost:9090/

Spark Workers

http://localhost:9091/

http://localhost:9092/