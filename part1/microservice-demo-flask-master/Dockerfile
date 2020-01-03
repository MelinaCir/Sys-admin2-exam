FROM python:latest

LABEL maintainer="mc222ap@student.lnu.se"

ENV PYTHONDONTWRITEBYTECODE 1
ENV FLASK_APP "app.py"
ENV FLASK_ENV "development"
ENV FLASK_DEBUG True

RUN mkdir /app
WORKDIR /app

COPY . /app/

RUN alias python="python3"

RUN pip install -r requirements.txt

ADD . /app

EXPOSE 6000

CMD python ./src/app.py

