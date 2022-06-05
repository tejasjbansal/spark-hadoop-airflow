
### Purpose
This docker container is meant to be used for learning purpose for programming PySpark. It has the following components.

* Hadoop v3.2.1
* Spark v2.4.4
* Conda 3 with Python v3.7

After running the container, you may visit the following pages.

* HDFS
* YARN
* Spark
* Spark History
* Jupyter Lab

To run the docker container, type in the following.
```
bash ./start-docker-container.sh
```

Else

```
docker pull avnish327030/spark-hadoop-airflow
```

```
docker run docker run -it -p 9870:9870 -p 8088:8088 -p 8080:8080 -p 18080:18080 -p 9000:9000 -p 8888:8888 -p 9864:9864 -p 8085:8085 -p 8793:8793 -p 8081:8081 -v notebook:/root/ipynb -v airflow:/home/airflow -v data:/data <IMAGE ID>
```

Click on below link to access portal

[Name Node](http://localhost:9870/)

[Hadoop Cluster](http://localhost:8088)

[Spark Master](http://localhost:8080)

[History Server](http://localhost:18080)

[Jupyter lab](http://localhost:8888)

[Hadoop Data Node](http://localhost:9864)

[Airflow Image](http://localhost:8085)

[Spark Worker Node](http://localhost:8081)

[Airflow Scheduler](http://localhost:8793)
