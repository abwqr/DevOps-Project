FROM python:3.8-slim-buster

WORKDIR /doctors

COPY doctors/requirements.txt /doctors/
RUN pip3 install -r requirements.txt

COPY . .

EXPOSE 9000

CMD [ "python3", "-m" , "app"]
