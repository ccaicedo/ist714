FROM python:3.10.0-slim-buster

WORKDIR /simple-webapp

COPY . .

RUN pip3 install -r requirements.txt

ENV FLASK_APP=webapp2.py

CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0"]
