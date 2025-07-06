FROM ubuntu:22.04

RUN apt-get update && \
    apt-get install -y python3 && \
    apt-get clean

COPY process.py .

CMD ["python3", "process.py"]
