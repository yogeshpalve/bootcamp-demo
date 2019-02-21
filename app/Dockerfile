FROM python:3-slim

WORKDIR /
STOPSIGNAL SIGINT
CMD ["python", "/app.py"]
RUN pip install flask prometheus_client
COPY app.py /app.py
