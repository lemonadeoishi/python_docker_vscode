FROM python:3.10.10

#RUN apt-get update
#RUN pip3 install --upgrade pip

COPY requirements.txt .
RUN pip3 install -r requirements.txt
#RUN apt-get -y update && apt-get -y upgrade && apt-get autoremove -y
RUN apt update && apt install -y zstd