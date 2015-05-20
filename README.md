Docker Projects
===

Some Docker project files, Dockerfile, Compose templates, etc.


# compose-haproxy-web
This demo compose project will boot 3 web containers as the backend of 1 standard haproxy container. 
The web container (depends on the python:2.7 image) will start a python application to return webpage indicating the visitor ip and the true destination ip. The haproxy container will listen on local port 80 for web access and 70 for status checking.
