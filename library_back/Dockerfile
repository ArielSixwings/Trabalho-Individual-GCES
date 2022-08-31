FROM python:latest
WORKDIR /gces_ariel
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY . .
EXPOSE 8000