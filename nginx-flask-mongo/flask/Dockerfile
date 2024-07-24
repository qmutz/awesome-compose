FROM python:3.11.9

WORKDIR /src
COPY . .
RUN pip install -r requirements.txt --no-cache-dir

CMD ["./server.py"]
