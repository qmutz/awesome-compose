FROM python:3.8.18

WORKDIR /src
COPY . .
RUN pip install -r requirements.txt --no-cache-dir

CMD ["./server.py"]
