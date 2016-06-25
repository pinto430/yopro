FROM python:3.5
ENV PYTHONUNBUFFERED 1
RUN mkdir /cod
WORKDIR /code
ADD requirements.txt /code/
RUN pip3 install -r requirements.txt
ADD . /code/
