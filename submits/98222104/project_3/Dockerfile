FROM python:3.10-slim-buster

WORKDIR /app

COPY . /app

RUN python -m pip install --upgrade pip

RUN pip install -r requirements.txt

ENTRYPOINT ["python"]

CMD ["app.py"]