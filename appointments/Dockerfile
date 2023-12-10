FROM python:3.8.2-alpine

COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt
EXPOSE 9000
COPY . .

CMD [ "python3", "-m" , "app"]
