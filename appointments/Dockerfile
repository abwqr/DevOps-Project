FROM python:3.8-slim-buster

WORKDIR /appointments

COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

COPY . .

EXPOSE 9000

CMD [ "python3", "-m" , "app"]
