# syntax=docker/dockerfile:1
#faltu comment
from python:latest

WORKDIR /app

copy requirements.txt requirements.txt

run python3 -m pip install --upgrade pip

RUN pip3 install -r requirements.txt
copy . .

CMD [ "python3", "manage.py", "runserver" ,"0.0.0.0:80"]
