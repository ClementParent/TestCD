FROM ubuntu:latest

MAINTAINER Angello Maggio "angellom@frog.com"

RUN apt-get update -y
RUN apt-get install -y python3-pip

COPY . .
RUN pip3 install -r requirements.txt

ENTRYPOINT ["python3"]
CMD ["./flask-docker.py"]
