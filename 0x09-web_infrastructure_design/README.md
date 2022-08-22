# Web infrastructure design

This project involves whiteboard design of web infractures with various components.

## Tasks :page_with_curl:

* **0. Simple web stack**
  * [0-simple_web_stack](./0-simple_web_stack): A whiteboard design of a one server web infrastructure that hosts a website that is reachable via www.foobar.com with the following components:
  * 1 server
  * 1 web server (Nginx)
  * 1 application server
  * 1 application files (code base)
  * 1 database (MySQL)
  * 1 domain name foobar.com configured with a www record that points to your server IP 8.8.8.8

* **1. Distributed web infrastructure**
  * [1-distributed_web_infrastructure](./1-distributed_web_infrastructure): A whiteboard design of a three server web infrastructure that hosts the website www.foobar.com with the following components:
  * 2 server
  * 1 web server (Nginx)
  * 1 application server
  * 1 load-balancer (HAproxy)
  * 1 application files (code base)
  * 1 database (MySQL)

* **2. Secured and monitored web infrastructure**
  * [2-secured_and_monitored_web_infrastructure](./2-secured_and_monitored_web_infrastructure): A whiteboard design of a three server web infrastructure that hosts the website www.foobar.com, secured, serving encrypted traffic, and monitored, with the following additional components:
  * 3 firewalls
  * 1 SSL certificate to serve www.foobar.com over HTTPS
  * 3 monitoring clients (data collector for Sumologic or other monitoring services)

* **3. Scale up**
  * [3-scale_up](./3-scale_up): A whiteboard design of the three server web infrastructure that hosts the website www.foobar.com in [2-secured_and_monitored_web_infrastructure](./2-secured_and_monitored_web_infrastructure) with the following additional components:
  * 1 server
  * 1 load-balancer (HAproxy) configured as cluster with the other one
  * Split components (web server, application server, database) with their own server

## Authors
<details>
    <summary>Oluwatobi Bamidele</summary>
    <ul>
    <li><a href="https://www.github.com/crewseefix">Github</a></li>
    <li><a href="https://www.twitter.com/crewseefix">Twitter</a></li>
    <li><a href="mailto:tostirma@gmail.com">e-mail</a></li>
    </ul>
</details>
<details>
    <summary>Ogundare Abdulahi</summary>
    <ul>
    <li><a href="https://www.github.com/obapythonaire">Github</a></li>
    <li><a href="https://www.twitter.com/obapythonaire">Twitter</a></li>
    <li><a href="mailto:abdulahogundare@gmail.com">e-mail</a></li>
    </ul>
</details>
<details>
    <summary>Kenny David</summary>
    <ul>
    <li><a href="https://www.github.com/kennykded">Github</a></li>
    <li><a href="https://www.twitter.com/kennykded_">Twitter</a></li>
    <li><a href="mailto:kennydavidkded@gmail.com">e-mail</a></li>
    </ul>
</details>
