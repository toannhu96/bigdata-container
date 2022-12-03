# big data All-In-One
Docker-compose contains the most common big data systems like: Apache Hadoop, Apache Hive, Apache Spark, Jupyter and Tensorflow  

## All images and configurations are in docker-compose.yml

 Run
  ```
  $ make
  $ docker-compose up -d
  ``` 

you can access the services throug the exposed ports as the following :

| Service Name  | Port Number |
| ------------- | ------------- |
| Hadoop name node  | 50070  |
| Hadoop data node  | 50075  |
| Hive server | 10000 |
| Postgres | 5433 |
| Jupyter | 8889 |
| PySpark | 4040 |

- To list the containers run ```$ docker ps```

- To run commands inside container run ```$ docker exec -it <containerName>```
