FROM python:3.12.6-slim-bullseye

WORKDIR /src

COPY analytics/requirements.txt requirements.txt

RUN pip install -r requirements.txt

COPY ./ .

CMD python app.py