FROM python:3.12-slim

WORKDIR app

COPY requirements.txt .
RUN pip install --no-cache-dir -r /app/requirements.txt

# ENTRYPOINT ["python", "-m", "http.server"]
ENTRYPOINT ["python", "run.py"]
