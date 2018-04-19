This compose file creates two container:

Web container:
  **Image: apache**

  Reachable via: **localhost:8001/**

Database Container:
  **Image: Mysql**

How to Run?

1) Go into the directory where the docker-compose file resides and use the command.
```
> docker-compose up
```
Working:

The web directory consists of a **index.html** file and a **cloudtech.php**. These files ensure that there is a connection to the mysql database server. 
