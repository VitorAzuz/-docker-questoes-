FROM python:3.12-slim

WORKDIR /app

COPY app.py .

RUN pip install Flask

EXPOSE 5000

CMD ["python", "app.py"]
