# This dockerfile will generate an image to server at 80 port for web application, which is written in python to return web page including the source and destination ip addresses.
FROM python:2.7
WORKDIR /code
ADD . /code
EXPOSE 80
CMD python index.py
