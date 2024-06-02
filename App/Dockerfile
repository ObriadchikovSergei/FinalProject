# Использование официального базового образа Python
FROM python:3.8
WORKDIR /app
COPY . /app
RUN pip install -r requirements.txt
EXPOSE 5001
CMD ["python", "server.py"]