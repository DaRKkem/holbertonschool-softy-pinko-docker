FROM ubuntu:latest

RUN apt-get update && apt-get upgrade -y
RUN apt-get install -y python3 python3-pip

RUN pip3 install flask --break-system-packages

RUN mkdir /app
COPY ./flask_app.py /app/flask_app.py

CMD ["python3", "/app/flask_app.py"]
