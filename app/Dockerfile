# app/Dockerfile
FROM python:4
WORKDIR /app
COPY requirements.txt .
RUN pip install -r requirements.txt .
COPY . .
CMD ["python","app.py"]
