FROM python:3.8-slim-buster


COPY doctors/requirements.txt .
RUN pip install -r requirements.txt

COPY . .

EXPOSE 9000

CMD [ "python3", "-m" , "flask", "run"]
