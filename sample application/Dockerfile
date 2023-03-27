FROM python:3.10.5
WORKDIR /app
COPY requirements.txt .
RUN pip3 install -r requirements.txt
COPY . /app/

CMD ["python3","app.py"]