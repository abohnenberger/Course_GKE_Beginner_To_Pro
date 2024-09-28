FROM python:3.12.6

COPY . /app
WORKDIR /app

RUN pip install -r requirements.txt

CMD ["python", "-u", "server.py"]
