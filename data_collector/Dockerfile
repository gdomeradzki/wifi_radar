FROM ubuntu:latest
RUN apt-get -y update
RUN apt-get -y install python3 python3-pip
RUN pip3 install aiohttp
COPY . .
ENTRYPOINT [ "python3", "-u", "collect.py" ]