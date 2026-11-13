FROM ubuntu

RUN apt-get update && apt-get install -y python3

WORKDIR /app

COPY app.py .

ENV APP_ENV=production

EXPOSE 80

CMD ["python3", "/app/app.py"]