FROM python:3.9-slim
WORKDIR /app
COPY backend.py /app
RUN pip install flask mysql-connector-python
CMD ["python", "backend.py"]

