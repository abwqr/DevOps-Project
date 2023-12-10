FROM python:3.8.2-alpine

COPY . .

RUN pip install -r requirements.txt
EXPOSE 9090

CMD [ "python3", "-m" , "app"]