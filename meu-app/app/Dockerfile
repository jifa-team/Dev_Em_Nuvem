
FROM python:3.11-slim


WORKDIR /app


COPY . /app

RUN pip install --no-cache-dir requests


CMD ["python", "/app/requests_worker.py"]