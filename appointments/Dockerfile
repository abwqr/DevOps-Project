FROM python:3.8.2-alpine

COPY . .

RUN pip3 install -r requirements.txt
EXPOSE 9000

CMD [ "python3", "-m" , "app"]
