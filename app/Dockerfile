FROM python:3.11-slim

EXPOSE 8000

RUN apt update

RUN apt install -y postgis proj-bin gdal-bin

WORKDIR /usr/src/app

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

CMD [ "python", "manage.py", "runserver", "0.0.0.0:8000" ]
