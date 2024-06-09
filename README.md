# sample
sample repository

Dockerfile :
FROM python
WORKDIR /app
COPY . /app
CMD ["python3","app.py"]
