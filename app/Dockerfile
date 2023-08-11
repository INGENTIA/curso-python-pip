FROM python:3.8

WORKDIR /app
COPY requirements.txt requirements.txt

RUN pip isntall --no-cache-dir --upgrade -r requirements.txt

COPY . / app/

CMD bash -c "while true; do sleep 1; done"