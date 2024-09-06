FROM python:3.12.0a1-alpine
WORKDIR /code
COPY requirements.txt /code/
RUN pip install -r requirements.txt --no-cache-dir
COPY . /code/
ENV FLASK_APP hello.py
CMD flask run --host=0.0.0.0
 