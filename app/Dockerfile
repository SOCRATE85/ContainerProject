# your code goes here ...
FROM python:3.9.10-alpine3.14

WORKDIR /app

COPY src/requirements.txt ./
RUN pip install --upgrade pip
RUN pip install --no-cache-dir -r requirements.txt

COPY . /app

EXPOSE 8000

ENV FLASK_APP=src/server.py

CMD [ "flask", "run", "--host", "0.0.0.0", "--port", "8000" ]