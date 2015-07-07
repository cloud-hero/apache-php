cloudhero-docker-php
================
Versions:
Apache/2.4.7 (Ubuntu)
PHP 5.5.9-1ubuntu4.11


Base docker image to run PHP applications on Apache


Building the base image
-----------------------

To create the base image `cloudhero/apache2php55`, execute the following command on the cloudhero-docker-php folder:

    docker build -t cloudhero/apache2php55 .


Running your Apache+PHP docker image
------------------------------------

Start your image binding the external ports 80 in all interfaces to your container:

    docker run -d -p 80:80 cloudhero/apache2php55

Create a Dockerfile like the following:
