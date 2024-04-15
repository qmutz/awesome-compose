FROM python:3.12.3-alpine
WORKDIR /code
COPY requirements.txt /code/
RUN pip install -r requirements.txt --no-cache-dir
COPY . /code/
ENV FLASK_APP hello.py
CMD flask run --host=0.0.0.0
 