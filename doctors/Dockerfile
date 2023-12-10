FROM python:3.8-slim-buster


#COPY doctors/requirements.txt requirements.txt
RUN pip3 install flask

COPY . .

EXPOSE 9000

CMD [ "python3", "-m" , "app.py"]
