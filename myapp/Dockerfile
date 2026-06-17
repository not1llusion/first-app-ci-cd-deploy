FROM python:3.11-slim
WORKDIR /app
COPY app.py .
HEALTHCHECK --interval=30s --timeout=3s --retries=3 \
  CMD python -c "import urllib.request; urllib.request.urlopen('http://localhost:8080')"
cmd ["python", "app.py"]

