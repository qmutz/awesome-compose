FROM python:3.10.14

WORKDIR /src
COPY . .
RUN pip install -r requirements.txt --no-cache-dir

CMD ["./server.py"]
