FROM python:3.9-slim

WORKDIR /app

RUN pip install --no-cache-dir Flask

COPY . /app/

EXPOSE 5002

CMD ["flask", "run", "--host=0.0.0.0", "--port=5002"]

