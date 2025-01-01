FROM python:3.8-slim-buster

WORKDIR /app

RUN pip3 install flask requests redis minio jsonpickle

COPY rest-server.py /app

ENTRYPOINT [ "python3", "rest-server.py"]