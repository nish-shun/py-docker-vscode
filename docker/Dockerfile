FROM python:3.10

# Update pacakge list, not package. I don't know What's package list
RUN apt-get update 
# Upgrade to newest pip
RUN pip install --upgrade pip

# Maybe, The place to execute RUN etc.
WORKDIR /var/docker-python
COPY requirements.txt /var/docker-python

# install python libraries
RUN pip install -r requirements.txt
