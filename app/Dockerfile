# syntax=docker/dockerfile:1
FROM python:latest
COPY . /app
WORKDIR /app
ENV FLASK_APP=warehouse.py
ENV FLASK_RUN_HOST=0.0.0.0
RUN apt-get -y install gcc python3
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
EXPOSE 5000
COPY . .
CMD ["flask", "run"]
ENTRYPOINT ["python"]
CMD ["warehouse.py"]