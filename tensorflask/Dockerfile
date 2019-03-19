FROM python:3

RUN apt-get update -y
RUN apt-get install -y python-pip python-dev build-essential 
COPY . /tensorflask
WORKDIR /tensorflask
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["app.py"]
