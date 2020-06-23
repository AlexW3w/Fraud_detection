FROM python:3.6

COPY requirements.txt ./
WORKDIR ./


RUN pip install -r requirements.txt
ADD ./ ./

CMD ["python", "app.py"] 