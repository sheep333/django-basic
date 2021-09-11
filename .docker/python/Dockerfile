FROM python:3.9-alpine
ENV PYTHONUNBUFFERED=1

WORKDIR /var/www/html/
COPY ../../requirements.txt /var/www/html/
RUN pip install -r requirements.txt

