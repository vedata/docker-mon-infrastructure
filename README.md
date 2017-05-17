##  Monitoring Infrastructure with Docker

**This project is for learning/staging/testing purposes only.** 

### Images

* OpenNMS 18.0.4
* PostgreSQL 9.6.1
* Grafana latest
* Jboss Wildfly
* Nginx latest


## Requirements

* docker 1.11+

## Usage

```
    1.  Set Environment Variables in ./env directory

    2.  Pull Docker image

      $ docker pull $IMAGE

    3.  Run Docker container
  
      $ docker-compose up

    5.  Login
        
      $ admin:admin

      $ change this password to a more secure one

    7.  Custom config files for opennms can be found:

      $ on container: /opt/opennms/etc

      $ on host system: /myhost/opennms/etc 
      

```

## Author
Vedat Karaaslan 
