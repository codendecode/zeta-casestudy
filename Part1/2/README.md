<h1>Problem Statement</h1>
Create a Dockerfile and docker-compose to run a 3 Tier application with backend api(node, python or any sample backend application), database and a nginx server. Mount volumes for persistent data for database Server.

<h1>Solution</h1>
Build a 3-Tier application with backend api (python), a database and a nginx server


* Configure nginx to enable https
* Redirect http to https
* Create a self signed certificate - document how to do it.
* Whitelist Ip’s
* Any other important configurations



<h1>Highlights</h1>

* Nginx is configured to enable https
* A self signed certificate has been created

<h1>Instructions</h1>
To bring up the application, do the following:

```
    cd Part1/2
    docker-compose up -d
```
